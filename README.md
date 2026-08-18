# ein Gedankensprung — Redesign

A redesign exploration of the one-page site for Mag. Lisa Kuhn's project management, coaching, and consulting practice ([eingedankensprung.at](https://www.eingedankensprung.at)).

**Live preview:** https://einseitensprung.github.io/ein-gedankensprung-redesign/

## About

Static site — no build step, no dependencies.

- `index.html` — markup
- `assets/styles.css` — all styling, including embedded base64 `@font-face` fonts so the page renders identically everywhere without external font requests
- `assets/main.js` — hero carousel, mobile nav, and small page behaviors

The hero carousel slides its panels in/out directionally (next/prev/dots/swipe all agree on direction) and falls back to a plain crossfade under `prefers-reduced-motion`.

## Local development

Open `index.html` directly in a browser, or serve the folder with any static server (e.g. `python -m http.server`) — no build tools required.

## Deployment

Hosted via GitHub Pages, served directly from the `master` branch root.

## Workflow

All changes in this repo are committed and pushed to GitHub automatically as they're made — no separate confirmation needed for `git add` / `git commit` / `git push` here.
