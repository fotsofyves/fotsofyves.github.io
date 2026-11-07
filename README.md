# Academic website — Yves Fotso Fotso

Static site (HTML + CSS, no build step) for GitHub Pages. English only.

Pages: `index.html` (Home), `about.html`, `research.html`, `publications.html`, `events.html` (Scientific events), `teaching.html`, `cv.html`, `contact.html`. Each menu entry opens its own page.

## Files to add

- **Photo**: `assets/photo.jpg` (square preferred, e.g. 800×800 px; it is shown in a circle, face centred towards the top). A placeholder appears until it is added.
- **CV**: `cv.pdf` at the root of the repository (used by the “Download CV” button).

## Publishing

1. Create a GitHub repository (`<your-username>.github.io` gives `https://<your-username>.github.io`).
2. Upload the whole folder content to the root, including `assets/` and `.nojekyll`.
3. Settings → Pages → *Deploy from a branch* → `main`, folder `/ (root)` → Save.

## To complete

Search the `.html` files for square brackets `[ ... ]`: career, CV, publications, events, courses, supervision, email, address, ORCID / Scholar / ResearchGate links.
Colours can be changed in the variables at the top of `style.css`.

## Illustrations

The pest illustrations in `assets/` (`coffee-borer.svg`, `aphids-leaf.svg`, `whitefly-leaf.svg`) are original vector drawings. To use real photographs instead, put them in `assets/` and change the `src` of the three images in `index.html`.
