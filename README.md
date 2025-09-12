# Glyppo Landing Page

This is a lightweight static site based on the `WEB/mira-pages` template, adapted for Glyppo.

- Entry point: `index.html`
- Styles: `styles.css` (Tailwind via CDN + small custom tweaks)
- Assets: placeholders in `assets/` and `assets/screens/`
- App Store badge: `download_cta/`

Local preview: open `index.html` in a browser or serve the folder with a simple HTTP server.

Deployment: this repo includes a GitHub Actions workflow to publish this folder to GitHub Pages.

Steps:
1. In GitHub → Settings → Pages, set Source to “GitHub Actions”.
2. Push to `main` with changes under `WEB/glyppo-pages/` or run the workflow manually.
3. The site will be deployed to `https://slowbrewedmacchiato.github.io/getglyppo/`.

Notes:
- `.nojekyll` disables Jekyll processing (needed for clean static hosting).
- `404.html` provides a simple not‑found page.
- Update OG/social image later once final assets are provided.

> Note: Social images and real app screenshots are placeholders. Replace when assets are ready.
