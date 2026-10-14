# King’s Bread by Krys — GitHub Pages package

This is a buildless static website. No Node installation, build command, server, or Sites account is required.

## Publish using GitHub Pages

1. Unzip this download.
2. Create a GitHub repository (for example, kings-bread-by-krys).
3. Upload the extracted contents to the repository root. Keep index.html, style.css, app.js, and the assets folder together. Upload the files, not the ZIP itself or an extra enclosing folder.
4. Commit the files to main.
5. Open Settings > Pages. Under Build and deployment, choose Deploy from a branch.
6. Select main and /(root), then Save.
7. Wait for deployment. The Pages settings screen will show the published URL, typically https://YOUR-USERNAME.github.io/kings-bread-by-krys/.

The included .nojekyll file bypasses Jekyll. All local asset paths are relative, so the site works at a repository subpath or a custom domain. If browser upload skips .nojekyll, create an empty file named .nojekyll in GitHub.

Official instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Edit the website

- index.html: page copy, logo, photo framing, navigation, posts, and contact links.
- style.css: colors, typography, spacing, and responsive layout.
- app.js: products, flavors, prices, basket, and order-request behavior. Product definitions are at the top.
- assets/: Krys’s logo and supplied Instagram screenshots, framed within the site using SVG viewBoxes.

Menu prices reflect the supplied October 14, 2026 post. Flavor-specific prices, pickup arrangements, availability, and full allergen information still need confirmation with Krys.

## How orders work

Customers can select quantities and flavors, choose One-time / Weekly / Monthly, and save their request in their own browser. They can copy it or open an email draft to Krys. They must review and send the email themselves. Requests do not reserve stock, charge cards, or create recurring subscriptions. No customer details are sent to a backend.

## Local preview

From this extracted folder, run: python -m http.server 8000
Then visit http://localhost:8000 . Use HTTPS hosting for clipboard support in production.

Google Fonts are loaded over the internet; serif and sans-serif fallbacks apply when offline. Email draft buttons require a configured email app. This package includes no credentials or hosting account configuration.
