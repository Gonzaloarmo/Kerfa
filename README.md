# Kerfa — concept e-commerce

Static site. No build step, no dependencies.

## Run locally
Serve the folder with any static server (opening the file directly won't load the page components):

    npx serve .

## Deploy to Vercel
1. Push this folder to a GitHub repo (files at the repo root).
2. In Vercel: Add New → Project → import the repo.
3. Framework preset: **Other**. Build command: empty. Output directory: `.`
4. Deploy.

Navigation uses hash routes (`#/shop`, `#/product/desk`…), so no rewrites are needed.

Concept project by Gonzalo Armocida. No real payments.
