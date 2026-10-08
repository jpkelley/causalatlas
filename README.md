# Causal Atlas of Ecology — Quarto website

A complete, editable Quarto website for a developing research program of the Behavioral Complexity and Causality Lab at the University of Wyoming.

## Contents

- Six public navigation pages: Home, Vision, Research, Development, Perspectives, People.
- Three introductory research-perspective essays.
- An About page explaining the site's editorial conventions.
- Original SVG diagrams and favicon in `assets/`.
- `_quarto.yml` site configuration and `styles.scss` academic styling.
- GitHub Actions workflow for deployment to GitHub Pages.

## Preview locally

1. Install [Quarto](https://quarto.org/docs/get-started/).
2. Open the project folder in RStudio or a terminal.
3. Run `quarto preview` (or use RStudio's **Render Website** command).
4. Run `quarto render` to generate the `_site/` directory.

## Publish on GitHub Pages

1. Create a GitHub repository (for example, `causal-atlas`).
2. Upload the **contents** of this folder to the repository root, including `.github/workflows/publish.yml`.
3. Edit `website.site-url` in `_quarto.yml` to your real URL, e.g. `https://USERNAME.github.io/causal-atlas/`.
4. In repository **Settings → Pages**, select **GitHub Actions** as the build and deployment source.
5. Push to the `main` branch. The included workflow installs Quarto, renders the site, and publishes the result.

## Before going public

- Confirm the current affiliations, names, and consent of all people listed on `people.qmd`.
- Replace placeholder project contact information if you wish to provide an email address.
- Check and update the October 2026 development-status note as needed.
- Check `site-url` for the actual GitHub Pages address.
- Review all language about plans versus completed work.
- Add citations or references to Perspectives essays if converting them into more formal scholarly commentaries.

## Editing the design

- `styles.scss`: colors, fonts, spacing, cards, and responsive layout.
- `assets/*.svg`: editable vector diagrams; no proprietary images or external image files are needed.
- `index.qmd`: home-page hero, cards, and introductory text.
- `development.qmd`: phase descriptions and current status.

## Notes

The Google Fonts import is optional. The site has system-font fallbacks and otherwise requires no remote assets. This package is source-ready; rendering requires Quarto to be installed. The site is not an operational database or search application.
