# colours

A visual reference library of **76 design styles**: each one rendered *live in its own aesthetic*, so you can actually see the look before you pick it. Built for designers who need to browse and shortlist visual languages quickly.

## Features

- **76 design styles**, from Brutalism, Memphis and Bauhaus to Glassmorphism, Y2K, Vaporwave, Guochao, Solarpunk and more, each with a hand-built CSS demo in that exact style.
- **Live search** across names, eras, traits, moods and use-cases.
- **Category filters**: Minimal, Maximal, Retro, Modern, UI Style, Experimental, Cultural.
- **Tone filter**: show all designs, or only light- or dark-backed ones.
- **Light & dark mode**: persisted, respects your OS preference.
- **Favorites / Shortlist** ⭐, save the styles you like (persisted in your browser).
- **Compare mode**: pin up to 3 styles and view their demos, palettes and traits side by side.
- **Click-to-copy palettes**: click any swatch to copy its hex code.
- **Export shortlist**: download your shortlist as a moodboard PNG.
- **Detail view** for each style: palette with hex codes, recommended typography, mood, best-use cases, and "see real examples" links (Google Images, Dribbble, Pinterest).
- **Optional reference images**: drop a file into [`images/`](images/) named after a style id and it appears automatically, with click-to-enlarge. See [images/README.md](images/README.md).
- **Responsive**: works on desktop and mobile.

## Run locally

It's a single self-contained `index.html` (only external dependency is Google Fonts), so any static server works:

```bash
python3 -m http.server 4599
# then open http://localhost:4599
```

## Adding your own reference images

Drop an image into the `images/` folder named after the style's id (e.g. `brutalism.jpg`, `vapor.jpg`). Supported formats: `.jpg`, `.png`, `.jpeg`, `.webp`, `.avif`. If no image exists for a style, its live CSS demo is shown instead. Full filename list in [images/README.md](images/README.md).
