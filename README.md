# Scrollytelling Page

Static scrollytelling page prepared for GitHub Pages.

## Local preview

Open `index.html` directly in your browser.

## GitHub Pages deployment

This repository includes a workflow at `.github/workflows/deploy-pages.yml`.

1. In GitHub, open `Settings` -> `Pages`.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push to `main` (already configured), or run the workflow manually from `Actions`.
4. Your site URL will be:
   - `https://tc-20minutes.github.io/scrolly/`

If deployment fails once, re-run the workflow after enabling Pages.
