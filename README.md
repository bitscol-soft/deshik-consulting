# Deshik Consulting

Static, self-contained website for Bangladesh RMG and textile teams exploring Trusted Data Gateway (TDG), Digital Product Passport (DPP), and related product-data workflows.

## Live preview

[Open the GitHub Pages preview](https://bitscol-soft.github.io/deshik-consulting/)

The `Publish GitHub Pages preview` workflow deploys updates pushed to the Arena working branch `arena/01a10b12-deshik-consulting`. The workflow run exposes the deployed page URL in its `github-pages` environment. [View workflow runs](https://github.com/bitscol-soft/deshik-consulting/actions/workflows/deploy-pages.yml).

## Pages

The site includes the home, about, solutions, industries, insights, tools and contact pages; standalone PLM, ERP, MES, SCM and QMS examples; and a blog index with RMG, DPP and TDG articles. Each page carries its own inline CSS and essential JavaScript.

## Run locally

From this directory, start a static HTTP server:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/` in a browser. No build step or dependency installation is required.
