# HoeGang.github.io

Basic static homepage for GitHub Pages.

This repository provides a stable public domain homepage for NohGang Works,
NGST project information, support contact, and policy pages.

## Files

- `index.html`: the public front page GitHub Pages serves at the site root.
- `projects.html`: a list view for public projects.
- `ngst.html`: the first project page for NGST, short for Noh Gang Smart Tools.
- `privacy/index.html`: the NohGang Works website privacy policy served at `/privacy/`.
- `privacy/ngst-express-it.html`: the NGST Express It app privacy policy.
- `privacy.html`: redirect for the previous privacy URL.
- `styles.css`: responsive styling for the homepage.
- `assets/hero-background.png`: local visual asset for the homepage hero.
- `.nojekyll`: keeps GitHub Pages in plain static-file mode.

## Local preview

Run a small local server so root-relative links such as `/privacy/` work:

```powershell
python -m http.server 8000
```
