# Mohammadali Mohammadkhani — Personal Website

Source for my personal academic website, hosted with **GitHub Pages** at
[moalimkh.github.io](https://moalimkh.github.io).

## Overview

A single, self-contained `index.html` — no build step, no framework, no dependencies
to install. It uses only:

- Inline CSS (with a light/dark theme) and inline SVG icons
- [Google Fonts](https://fonts.google.com) (Inter + Fraunces), loaded from a CDN
- A small amount of vanilla JavaScript for the theme toggle, scroll-reveal, and
  active-section navigation

## Structure

```
.
├── index.html                 # the entire site
├── favicon.ico
└── assets/
    └── images/
        └── resume-profile.jpg  # profile photo
```

## Editing

All content lives directly in `index.html`. Update the relevant section
(About, Research, Publications, Experience, Education, Skills) and save.

To preview locally, just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

GitHub Pages serves `index.html` from the repository root automatically. To publish
changes, simply commit and push:

```bash
git add -A
git commit -m "Update website"
git push
```
