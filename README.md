# DRAWforge — Procreate Learning PWA

DRAWforge is a single-page, offline-first Procreate drawing companion for beginner icon, character, texture, lettering, and shape practice.

## What changed in this amplified version

- More organized tab structure:
  - Daily Draw
  - Trace Blueprint
  - Layer Recipe
  - Shape Gym
  - Style Mixer
  - AI Muse
  - Saved Relics
- Each mode now has its own option deck instead of sharing one generic control panel.
- Added mode-specific selectors for object, shape, focus, skill, style, material, and repetition type.
- Added clearer mini guidance cards inside each mode.
- Added an AI Muse tab with direct command buttons for Deepen, Beginner Version, Trace Blueprint, and Layer Stack.
- Kept the app static, client-side only, and GitHub Pages friendly.

## Files

```text
index.html
manifest.webmanifest
sw.js
ICON-192x192.png
ICON-512x512.png
README.md
```

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder into the repo root.
3. Commit the files.
4. Go to Settings → Pages.
5. Choose Deploy from branch.
6. Select `main` and `/root`.
7. Save.

## OpenRouter AI Muse

The app can work fully offline with local generators. To use AI Muse, open the settings gear in the app and paste your own OpenRouter API key. The key is stored only in your browser localStorage.

Do not hard-code your API key into the GitHub files.
