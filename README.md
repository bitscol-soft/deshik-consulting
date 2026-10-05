# Deshik Consulting

Static, self-contained website for Bangladesh RMG and textile teams exploring Trusted Data Gateway (TDG), Digital Product Passport (DPP), and related product-data workflows.

## Live preview

Target URL: [https://bitscol-soft.github.io/deshik-consulting/](https://bitscol-soft.github.io/deshik-consulting/) (available once GitHub Pages is enabled for this repository).

The `Publish GitHub Pages preview` workflow deploys updates pushed to the Arena working branch `arena/01a10b12-deshik-consulting`. GitHub Pages is not enabled yet: a repository admin must open [Settings → Pages](https://github.com/bitscol-soft/deshik-consulting/settings/pages) and set **Build and deployment → Source** to **GitHub Actions**. Then rerun the workflow from the [Actions page](https://github.com/bitscol-soft/deshik-consulting/actions/workflows/deploy-pages.yml). The workflow will publish the 16 HTML pages and expose the live URL in its `github-pages` environment.

## Pages

The site includes the home, about, solutions, industries, insights, tools and contact pages; standalone PLM, ERP, MES, SCM and QMS examples; and a blog index with RMG, DPP and TDG articles. Each page carries its own inline CSS and essential JavaScript.

## Run locally

From this directory, start a static HTTP server:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/` in a browser. No build step or dependency installation is required.
