Architecture
============

This repository is intentionally small and optimized for clarity. It contains the following top-level files and directories:

- `index.html` — Single-page HTML file containing the markup for the landing page.
- `css/` — Stylesheets.
  - `normalize.css` — Reset/normalize rules to reduce browser inconsistencies.
  - `styles.css` — Project styles including layout and responsive rules.
- `img/` — Static images used by the site (hero image and any icons).

Design Notes
------------

- The page uses a mobile-first responsive approach.
- Visual assets are kept in `img/` for simplicity; for larger projects split into `img/` and `assets/`.

Extending the Project
---------------------

- To add JavaScript, create a `js/` directory and include a small bundle or individual scripts.
- To componentize the page, split sections of `index.html` into partials and use a static site generator.
