# GaleriFahmi — Neo-Brutalist Photo Gallery

A responsive HTML gallery for the 28-photo Hannapunzel collection, served through verified direct Aceimg CDN links.

## Open the project

Open `index.html` in any modern browser. No server, build step, external JavaScript package, or external stylesheet is required. An internet connection is needed to load the photographs from `cdn.aceimg.com`. The page also works as a GitHub Pages site.

## Features

- Neo-Brutalist visual system with thick borders, hard offset shadows, bright accents, and a grid background
- Responsive grid with 28 original WebP photographs
- **28 unique Aceimg CDN links**, each verified with HTTP 200 and an MD5 match against the original file
- Search by photo number, date, source ID, or original filename
- Portrait, landscape, and square filters
- Collection-order, newest, oldest, and filename sorting
- Random-photo button and one-click filter reset
- Full-screen viewer with previous/next controls
- **Copy direct link** and **Open original** actions for every photo
- Keyboard support: Left/Right arrows, Escape, and focus containment in the viewer
- Responsive layouts and reduced-motion support

## Project files

- `index.html` — complete gallery, styles, scripts, metadata, and CDN URLs
- `README.md` — project notes

No build tooling, analytics, tracking scripts, web fonts, or JavaScript dependencies are used. Only the photo images are loaded from an external host.
