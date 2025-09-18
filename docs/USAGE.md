
# Usage

## Local Preview

The simplest way to preview the site is to open `index.html` in your browser. For a better development experience, run a lightweight HTTP server from the project root:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Customizing Content

- Edit `index.html` to change text, sections, and structure.
- Update styles in `css/styles.css`. Keep `css/normalize.css` as the reset layer.

## Assets

- Replace `img/hero.jpg` with your own hero image. Keep the same filename or update `index.html`.

## Deployment

- GitHub Pages: push the repository and enable Pages on the repository settings.
- Netlify / Vercel: connect the repository and deploy the main branch.

## Troubleshooting

- If images don't show, ensure the path is `img/hero.jpg` and the file exists.
- If CSS changes don't appear, clear your browser cache or hard-refresh (Ctrl+Shift+R).
