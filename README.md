# InZition

The InCyZn marketing website: a single scroll-driven page built with
[ScrollCraft](https://github.com/nateherkai/scroll-craft).

## Running locally

```bash
npx serve .
# or any static file server pointed at the repo root
```

Open the printed URL. The page has no build step: `index.html`,
`scrollcraft.css` and `scrollcraft.js` are served as-is.

## Structure

- `index.html`, `scrollcraft.css`, `scrollcraft.js` — the live site.
- `assets/` — the InCyZn logo (mark and lockup), extracted losslessly from
  the client's own brand files.
- `scrollcraft/builds/incyzn/` — the ScrollCraft build workspace: `BRIEF.md`
  (the design brief and feeling curve this page was built from), the same
  engine/page files, and `lab/` (verification screenshots from the
  desktop, mobile and reduced-motion passes).
- `scrollcraft/FINGERPRINTS.md` — the fingerprint registry for future
  ScrollCraft builds in this repo.
