# Mohammadali Mohammadkhani — Personal Website

Personal academic website at [moalimkh.github.io](https://moalimkh.github.io), hosted on GitHub Pages.

The site is a single `index.html` with inline CSS and vanilla JavaScript. No build step or package installation is needed. Typography uses system fonts; the site has no external font dependencies.

The page introduces current research, lists publications, and summarizes education, engineering, teaching, and technical skills. It supports mobile layouts, light and dark themes, keyboard navigation, and reduced-motion preferences. Content remains readable without JavaScript.

## Content

The source of truth is the CV in `assets/documents/mohammadali-mohammadkhani-cv.pdf` (copied from the supplied CV on October 17, 2026). When updating it, also reconcile the biography, research roles and dates, publication titles/authors/venues/statuses/links, education, awards, teaching, and skills in `index.html`.

The website is intentionally selective: it expands on research and engineering in readable prose, while the downloadable CV contains the complete coursework, earlier schooling, and references. Avoid adding claims or results that the CV does not support.

- `index.html` — content, styling, and interactions
- `assets/images/resume-profile.jpg` — original portrait
- `assets/documents/mohammadali-mohammadkhani-cv.pdf` — downloadable CV
- `favicon.ico` — site icon

## Preview

Open `index.html` in a browser, or serve the repository:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish

Commit and push the reviewed changes to the branch configured for GitHub Pages.
