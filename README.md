# LevelUp Wallpapers — GitHub Pages Upload Fix

IMPORTANT: Every file in this package is at the same level. This fixes the previous issue where the published HTML referenced a `wallpapers/` folder that was not present in the repository.

## Upload these files
Extract this ZIP, select ALL contents, and upload/commit them in the ROOT of `mexiaeon/levelup-wallpapers` (not inside a subfolder). This includes:
- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `icon-192.png` and `icon-512.png`
- all 12 `.jpg` wallpaper files
- `.nojekyll`, `README.md`, and `ARTWORK_MANIFEST.json`

After committing, open your GitHub Pages site in a private/incognito window or hard-refresh with Ctrl+F5 so the old cached page doesn't appear.

This is an installable web-app prototype, not a native Android app, and advertising is not integrated yet.
