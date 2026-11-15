# VENDMATRIX

A simple static landing page for a company named VENDMATRIX.

## Included
- A modern one-page site with an About section and contact email
- VendMatrix branding and icon using the supplied JFIF file
- GitHub Pages deployment workflow for automatic publishing

## Local preview
Open `index.html` in a browser, or run:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000

## GitHub Pages deployment
1. Push this project to a GitHub repository.
2. In the repository, go to Settings > Pages.
3. Select the branch `main` and keep the default folder `/`.
4. Save the settings.
5. The workflow in `.github/workflows/deploy-pages.yml` will publish the site automatically.
