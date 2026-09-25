# ÉLANORA Fragrances

A responsive fragrance-commerce website for perfumes, attars, candles, discovery sets, and bundles in Pakistan.

## Run locally

No build step is required. Open `index.html` directly, or serve the repository with any static web server:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Project structure

- `index.html` — root entry point for GitHub Pages and ordinary static hosting
- `app.js` — catalogue, cart, wishlist, checkout, search, finder, bundle builder, journal, and demonstration admin logic
- `styles.css`, `images.css`, `alignment.css` — responsive visual system
- `assets/` — generated fragrance imagery
- `dist/` — identical deployable build used by ChatGPT Sites
- `.openai/hosting.json` — ChatGPT Sites project configuration

## Demonstration data

Cart, wishlist, orders, enquiries, newsletter subscriptions, and storefront settings use browser `localStorage`. Production launch requires a backend database, authentication, payment gateways, transactional email, and WhatsApp integration.

## Administration

Open `?page=admin` for the demonstration dashboard. This route is not production-secure until authentication and authorization are connected.

## Live site

[elanora-fragrances-pakistan.abuzz-luck-6134.chatgpt.site](https://elanora-fragrances-pakistan.abuzz-luck-6134.chatgpt.site)
