# GameVault — Game Currency Store (Demo)

A single-page demo storefront for topping up game currency — Roblox Robux, Mobile Legends Diamonds and Valorant Points. Built as a design and front-end sample, not a live store.

**Live demo:**[`https://malvinn209.github.io/gamevault-demo/`](https://malvinn209.github.io/Selling-ingame-Currency-Website/)

⚠️ This is a demo

- No real payments are taken and no game currency is delivered.
- Order tracking is simulated and stored only in your own browser.
- Not affiliated with Roblox, Moonton or Riot Games. Logos and artwork belong to their owners and are used here for demonstration/sample of the website only.

## Features

- Game menu with a dedicated store page per game (Roblox, Mobile Legends, Valorant)
- Cart with quantity controls, saved between visits
- Checkout with per-game player ID validation (Roblox username, ML `ID (Zone)`, Riot `Name#TAG`)
- Region and currency switcher: USD, IDR (Rp), MYR (Ringgit), SGD, JPY (Yen), CNY (Yuan)
- Payment method selection: Visa/Mastercard, QRIS, GoPay, Indomaret/Alfamart (Indonesia-only methods are marked)
- Order tracking page with a simulated status timeline
- FAQ, Terms, Privacy and Refund policy pages (template text — not legal advice)
- WhatsApp support button
- Light/dark theme toggle, saved between visits
- Fully responsive, built for mobile

## Tech

Plain HTML, CSS and JavaScript in a single file — no build step, no dependencies, no framework. Everything runs client-side.

## Before using this for a real store

This project is a UI/UX sample. Turning it into a real store needs, at minimum:

- A backend and a licensed payment gateway
- A legitimate supplier or distributor agreement for each game's currency (each game has its own rules on who may resell it)
- Real order storage and status updates (not localStorage)
- Terms, Privacy and Refund pages reviewed for your actual business and jurisdiction
- Your own support contact in place of the placeholder WhatsApp number in the code

## License

Add a license of your choice, or mark this repository as "all rights reserved" if you don't want others to reuse the code.
