# LevelUp Wallpapers — Individual Art Build

This build replaces the earlier collage-derived wallpaper crops with **12 standalone AI-generated portrait artworks**. Each artwork is a separate image file, not cropped out of a collage.

## Artwork included
- Neon Metropolis
- Rain Racer
- Neon Motorcycle
- Bloodmoon Ronin
- Inferno Dragon
- Ringed Planet
- Armored Vanguard
- Moonlit Castle
- Winter Wolf
- Jungle Tiger
- Aurora Cabin
- Cyberpunk Overlook

## Image handling
- Source images retain their original generated dimensions; this build does not upscale them or stretch downloads to a fixed canvas size.
- The app gallery uses local image files in `wallpapers/`.
- Selecting **Download art** exports a PNG using the exact pixel width and height of the selected source image. The downloaded filename includes those dimensions.
- JPG assets are stored at high quality to keep the website package smaller and loading faster.
- There are 12 wallpapers in this quality-focused build. The former 25-image collage-derived pack is not included as wallpaper assets.

## Run and test
1. Extract the ZIP.
2. Open `index.html` in Chrome to test the gallery and PNG downloads.
3. For install/offline testing, serve the folder via HTTPS or localhost; `file://` URLs do not fully support PWA installation.

With Python installed, open a terminal in this folder and run `python -m http.server 8000`, then visit `http://localhost:8000`.

## Launch notes
This is an installable web app (PWA) prototype, not a native Android app; there is no live AdMob integration or ad revenue yet. For commercial use, review every image for unintended recognizable logos or copyrighted characters, and verify applicable image-generation commercial-use terms before release.
