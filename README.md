# Jonah Mallard — Portfolio

Jonah Mallard's personal portfolio site: a single-page site listing his projects with live demo and source links.

**Live site:** https://jonahmallard.github.io/

## What's in here

- `index.html` — the whole page: intro, contact links, and one card per project.
- `style.css` — the site's styling (dark theme).
- `.nojekyll` — tells GitHub Pages to serve the files exactly as they are, skipping Jekyll processing.

## Running locally

No build step and no dependencies — it's plain HTML and CSS. Either open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server
```

then visit http://localhost:8000/. Edit `index.html` or `style.css` and refresh to see changes.

## Deploying

Push to the `master` branch and GitHub Pages publishes the site automatically at https://jonahmallard.github.io/.
