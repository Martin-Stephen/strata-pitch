# Strata — Pitch Website

The regulated retail rails for AU/NZ private credit.

**Live:** https://martin-stephen.github.io/strata-pitch/

## Variants
- Investor view: `/`
- Acquirer view: `/?mode=acquirer`

## Local dev
This is a single-file static site. Open `index.html` directly in a browser or serve with any static server (e.g., `python3 -m http.server 8765`).

## Hosting
Deployed via GitHub Pages from `main` branch, root directory. Pages config lives in the repo's Settings → Pages.

## Stack
- HTML + CSS + vanilla JS (no build step)
- Google Fonts: Fraunces (display serif), Geist (body sans), JetBrains Mono (data)
- Plausible analytics slot (update `data-domain` when a real domain is pointed)

## Ownership
© 2026 Martin van Blerk. All rights reserved.
