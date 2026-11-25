# PlayPrompt 3D Lab

Can a one-line idea become a 3D game? We gave the same 25 game ideas, each a single plain
sentence, to several AI models inside [PlayPrompt](https://playprompt.org)'s creation flow and
asked for real 3D games that run in the browser. This site holds every game that came back
playable, plus a short write-up of what we learned.

**Live site:** https://anselmotalotta.github.io/playprompt-3d-games/

- [`index.html`](index.html): the gallery. One row per idea, one column per model setup. Click a tile to play.
- [`article.html`](article.html): the story. What we tried, the results and our conclusions.
- [`credits.html`](credits.html): third-party software, models and sounds, with their licenses.

3D is an experiment, not a PlayPrompt feature yet. The PlayPrompt app itself is in beta at
[playprompt.org](https://playprompt.org).

## Run it locally

No build step. Open `index.html` in a browser, or serve the folder with any static server,
for example `python3 -m http.server`. Every game in `games/` is a single self-contained HTML
file that also works on its own.

## Layout

```
index.html      gallery
article.html    write-up
credits.html    credits and licenses
style.css       shared styles
games/          one self-contained HTML file per game
thumbs/         gallery thumbnails
licenses/       full license texts
```

## Licenses

- three.js: MIT License, © 2010-2026 three.js authors ([licenses/three.js-MIT.txt](licenses/three.js-MIT.txt)).
- 3D models and sounds by [Kenney](https://kenney.nl/): CC0 1.0 ([licenses/CC0-1.0.txt](licenses/CC0-1.0.txt)).
- The games, this site and PlayPrompt's runtime libraries: © PlayPrompt. All rights reserved.
