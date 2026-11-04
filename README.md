# Field Echo — Presentation Deck

A 5-slide story deck for the Digital Green FarmerChat MEL Survey Agent, built for AWS Breaking Barriers 2026 (Team 37).

Plain HTML, CSS, and JavaScript. No build step, no dependencies.

## Files

| File | What it is |
|---|---|
| `index.html` | Slide content and structure |
| `styles.css` | Styling and animations |
| `app.js` | Navigation, counters, dot nav |

All three must stay in the same folder.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on Vercel

Import the repo, set **Framework Preset: Other**, leave the build command and output directory empty, and deploy. Vercel serves `index.html` at the root.

## Controls

- `←` `→` or swipe — move between slides
- `Space` — next slide
- `F` — fullscreen
- Dots at the bottom — jump to a slide
