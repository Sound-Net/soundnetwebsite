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

A GitHub Actions workflow at `.github/workflows/publish.yml` publishes the rendered site to the `gh-pages` branch on pushes to `main` using `quarto-dev/quarto-actions/publish`.

## TODOs

- Placeholder icons currently live in `images/icons/` and should be replaced with the real/current icons for each tool once available.
- Download links on the homepage currently point to placeholder release URLs and should be updated to direct macOS/Windows release assets once release automation exists.
