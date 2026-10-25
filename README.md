# Henry Tse's personal website

A responsive, static personal homepage, separate from the existing academic website.

Website: https://dongchuxie8-source.github.io/henry-tse/

## Edit

- Content and contact links: `site/index.html`
- Layout, colors, and mobile styles: `site/styles.css`
- Avatar: `site/assets/avatar.jpg` (copied from the supplied `22.jpg`)

## Preview

Run `python -m http.server 8080 --directory site`, then open http://localhost:8080/.
No build or package installation is required. Google Fonts are optional; system
fonts are used if they cannot load.

## Deploy

GitHub Pages uses the GitHub Actions source. Pushes to `main` deploy only the
`site` directory using `.github/workflows/pages.yml`.
