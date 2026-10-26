# Ember Impact Report 2025

Interactive web version of Ember's Impact Report 2025 – open data and analysis that contributed to policy changes across four continents.

- **Live page:** https://ember-labs-org.github.io/impact-report/
- **On Ember Labs:** https://ember-labs.org/experiments/impact-report2025

## What's in this repo

| File | Purpose |
| --- | --- |
| `index.html` | The whole report: a single self-contained HTML file with CSS, JavaScript and images inlined |
| `impact-report-2025-thumbnail.png` | Thumbnail used for the Ember Labs listing |
| `README.md` | This file |

There is no build step and nothing to install.

## Updating the report

1. Edit `index.html`, or replace it with a new version. Keep the file name `index.html`, as GitHub Pages serves that file at the site address.
2. Commit to `main`.
3. GitHub Pages redeploys automatically within a few minutes. Hard-refresh (Cmd/Ctrl + Shift + R) to see the change.

To preview locally, open `index.html` in a browser.

## Hosting and embedding

The page is hosted with GitHub Pages (Settings → Pages → deploy from `main`, root folder) and embedded on the Ember Labs site through its CMS link field.

The page scrolls inside `body` rather than the browser window (`html { overflow: hidden }`, `body { overflow-y: auto }`). This lets it scroll when embedded in an iframe with page scrolling turned off. Keep these rules if you restyle the page.

## Licence

All content is released under a Creative Commons Attribution Licence ([CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)).

Ember is the trading name of Ember Energy Research CIC, a Community Interest Company registered in England & Wales #06714443.
