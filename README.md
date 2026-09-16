# Sound-Net Website

This repository contains a simple [Quarto](https://quarto.org/) website for the Sound-Net project.

## Local development

Render the full site:

```bash
quarto render
```

Run a local preview server:

```bash
quarto preview
```

## Publishing

A GitHub Actions workflow at `.github/workflows/deploy-pages.yml` renders the site and deploys the generated `_site/` output to GitHub Pages on pushes to `main`, and also supports manual runs via `workflow_dispatch`.

## TODOs

- Placeholder icons currently live in `images/icons/` and should be replaced with the real/current icons for each tool once available.
- Download links on the homepage currently use placeholder anchors/URLs and should be updated to direct macOS/Windows release assets once release automation exists.
