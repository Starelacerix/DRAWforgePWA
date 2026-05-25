# Drawforge — Procreate Drawing Companion PWA

Drawforge is a single-page, static, offline-first PWA for learning to draw in Procreate. It generates beginner-safe drawing missions, traceable blueprints, layer recipes, shape drills, style studies, saved practice cards, and optional OpenRouter AI Muse Mode.

## Files

- `index.html` — complete app code
- `manifest.webmanifest` — install metadata and icon references
- `sw.js` — offline cache service worker
- `ICON-192x192.png` — app icon
- `ICON-512x512.png` — app icon

## Deploy on GitHub Pages

1. Upload these files into the root of a GitHub repository.
2. Commit the files.
3. Open **Settings → Pages**.
4. Choose **Deploy from branch**.
5. Select `main` and `/root`.
6. Save.

## OpenRouter AI Mode

Open the app, tap the settings gear, and paste your own OpenRouter API key into the local settings panel. Do not hard-code your API key into the source code. The key is stored only in your browser with `localStorage`.

Default model: `openrouter/free`
