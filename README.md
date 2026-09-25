# GameVault — Game Currency Store (Demo)

A single-page demo storefront for topping up game currency — Roblox Robux, Mobile Legends Diamonds and Valorant Points. Built as a design and front-end sample, not a live store.

**Live demo:** add your GitHub Pages link here once it's published, e.g. `https://YOURUSERNAME.github.io/gamevault-demo/`

## ⚠️ This is a demo

- No real payments are taken and no game currency is delivered.
- Order tracking is simulated and stored only in your own browser.
- Not affiliated with Roblox, Moonton or Riot Games. Logos and artwork belong to their owners and are used here for demonstration only.

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

## Run locally

Download `index.html` and open it directly in a browser, or serve it with any static file server.

## Deploy on GitHub Pages

1. Push `index.html` to this repository.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save, wait a minute, then open the link shown at the top of the Pages settings page.

## Before using this for a real store

This project is a UI/UX sample. Turning it into a real store needs, at minimum:

- A backend and a licensed payment gateway
- A legitimate supplier or distributor agreement for each game's currency (each game has its own rules on who may resell it)
- Real order storage and status updates (not localStorage)
- Terms, Privacy and Refund pages reviewed for your actual business and jurisdiction
- Your own support contact in place of the placeholder WhatsApp number in the code

## License

Add a license of your choice, or mark this repository as "all rights reserved" if you don't want others to reuse the code.
