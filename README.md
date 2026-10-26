# GaleriFahmi — Neo-Brutalist Media Gallery

A responsive HTML gallery with **58 verified Aceimg CDN files** in two categories:

- **Hannapunzel:** 28 WebP photos
- **miamiaof:** 20 WebP photos and 10 H.264 MP4 videos downloaded from the pCloud `Foto/miamiaof` folder

## Open the project

Open `index.html` in any modern browser and click a category to reveal its collection. Click the active category again to close all media, or click the other category to switch collections. No media elements or CDN requests are created while every category is closed. An internet connection is needed to load the photos and videos from `cdn.aceimg.com`.

## Video playback

The 10 miamiaof videos use native HTML `<video controls>` players directly in the grid. Use **Open in viewer** to play them in the lightbox, or **Full Screen** to open the video in the browser's full-screen mode. If the Fullscreen API is blocked by an embedded preview, the gallery falls back to a full-viewport player. Playback starts only when you press Play; no video autoplays.

## Features

- Neo-Brutalist visual system with thick borders, hard offset shadows, bright accents, and a grid background
- 48 WebP photos and 10 directly playable MP4 videos
- Independent **Hannapunzel** and **miamiaof** category toggles
- **58 unique Aceimg CDN links**, each verified with HTTP 200 and an MD5 match against its local source file
- Random-media button for the active category
- Full-screen viewer with previous/next controls for photos and videos
- **Copy direct link** and **Open original** actions for every item
- Keyboard support: Left/Right arrows, Escape, and focus containment in the viewer
- Responsive layouts and reduced-motion support

## Project files

- `index.html` — complete gallery, styles, scripts, metadata, and CDN URLs
- `README.md` — project notes

No build tooling, analytics, tracking scripts, web fonts, or JavaScript dependencies are used. Only the media files are loaded from an external host.
