# Kids Art Box — template

A hand-drawn-style PWA for saving a kid's paintings: snap a photo, record the
child telling the story behind it, auto-tag the time and place, browse a
gallery, hang favorites on a clothesline "wall." Everything is stored on-device
(IndexedDB) — no accounts, no server.

## Make it yours

Edit **one file**: [`app/src/config.ts`](app/src/config.ts). Set the child's
name, age, app title, and the deploy path (`base`, which must match your
GitHub repo name if you deploy to GitHub Pages).

## Run locally

```bash
cd app
npm install
npm run dev
```

## Deploy

Push to your own GitHub repo — the included `.github/workflows/deploy.yml`
builds and publishes to GitHub Pages automatically. You'll need to enable
Pages once via the repo's Settings → Pages (build type: "GitHub Actions").

## Stack

Vite + React + TypeScript, Dexie (IndexedDB), vite-plugin-pwa. MIT-style —
use it freely.
