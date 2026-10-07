# Bianabuur Lifestyle

A lightweight static lifestyle journal. No build step or package installation is required.

## Pages

- `index.html` — home page and recent stories
- `journal.html` — searchable-by-category journal archive
- `story.html?post=<slug>` — individual journal entries

## Preview locally

From the repository directory, run:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000> in a browser. Using a local server also ensures the story URLs work as expected.

## Publish

The site can be served with GitHub Pages by selecting the `main` branch and the repository root (`/`) under **Settings → Pages**.