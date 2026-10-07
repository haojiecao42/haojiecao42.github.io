# haojiecao42.github.io

Personal website of Haojie Cao: <https://haojiecao42.github.io>

A single static page with no build step. GitHub Pages serves these files as-is.

| File | What it is |
| --- | --- |
| `index.html` | All page content |
| `css/style.css` | All styling |
| `assets/photo.jpg` | Profile photo (square, 600×600) |
| `assets/favicon.svg`, `assets/apple-touch-icon.png`, `favicon.ico` | Site icons |
| `404.html` | Page shown for missing URLs |
| `googlecab6fd098812e788.html` | Google Search Console verification (keep) |
| `.nojekyll` | Tells GitHub Pages to skip its Jekyll build |

## Editing

Edit `index.html` directly on GitHub (pencil icon). Each list item is a small block you can copy, paste, and change:

- **Publication**: copy one `<li>` under *Selected Publications*. Wrap your name in `<span class="me">…</span>` and put the DOI link in `<a class="doi" href="…">DOI</a>`.
- **Presentation** or **media item**: copy one `<li class="entry">` block. Badge classes are `badge-oral`, `badge-poster`, `badge-invited`, `badge-news`, and `badge-policy`.
- **Award**: add an `<li>` to the right year, or copy a whole year block.
- **Photo**: replace `assets/photo.jpg` with a square image (about 600×600) using the same name.

Links to other sites open in a new tab automatically.

## Preview locally

```sh
python3 -m http.server
```

Then open <http://localhost:8000>.
