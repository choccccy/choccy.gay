# choccy.gay

Personal homepage, served by GitHub Pages straight from the repo root (no build step).
It's a hand-written port of the original Carrd site with the same layout, breakpoints and links.

- `index.html`: markup, plus an inline SVG sprite for the button icons
- `style.css`: all styles
- `assets/`: avatar, footer image, icons
- `CNAME`: custom domain for GitHub Pages
- `.nojekyll`: serve files as-is

## Local preview

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.
