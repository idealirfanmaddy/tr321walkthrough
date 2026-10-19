# TR 321 Smart Classroom walkthrough

Static site: open `index.html` in a browser, or host the folder on GitHub Pages.

- `index.html`: the whole viewer (3D model, photo spots, guided narrated tour)
- `audio/`: narration for each tour chapter
- `pano/`: 360° photo spots (Middle as cube faces, Front as an equirectangular panorama)
- `models/`: detailed 3D furniture and fittings (a glTF binary, base64 inside JSON)
- `photos/`: close-up photos shown during the tour and on feature cards

Loads Three.js from cdn.jsdelivr.net and fonts from Google Fonts, so it needs an internet connection.
