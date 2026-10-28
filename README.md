# GCOB Prompt Helper by jGuru

Static product, privacy, terms and support website. No scripts, external fonts, analytics, forms, cookies or browser storage.

## GitHub Pages

Publish from `main`, root folder `/`, under repository Settings → Pages → Deploy from a branch. The `.nojekyll` file serves the existing static files.

## Local preview

Run `python3 -m http.server 8000` from the repository root and open `http://localhost:8000`.

## Files

- `index.html`: product homepage
- `privacy/index.html`: privacy policy
- `terms/index.html`: terms of use
- `support/index.html`: support instructions
- `assets/site.css`: responsive styles
- `assets/favicon.svg`: local vector icon

The plugin itself is not included in this website repository.

## Languages

English pages remain at the repository root. Slovak pages are under `sk/`, with equivalent privacy, terms and support paths. Each page includes EN/SK links to its counterpart, a canonical URL and reciprocal hreflang metadata. Both languages share the local CSS and icon.

## ChatGPT plugin release

Version 1.0.10 published 2026-10-28. ZIP download: https://github.com/passanger68/gcob-prompt-helper/releases/download/v1.0.10/plugin.zip
