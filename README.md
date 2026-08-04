# Portfolio

Simple, static portfolio site split by project category. Plain HTML/CSS, no build process.

Published via GitHub Pages from the root of the `main` branch.

## Structure

- `index.html` — landing page with bio and category links
- `app.html` — App category projects (Journal Onboarding, Micro Walk)
- `assets/css/style.css` — shared styles for all pages
- `assets/img/` — screenshots
- `assets/video/` — demo recordings

New categories (e.g. ML) get their own `<category>.html` page, linked from the `.categories` nav in `index.html`.

## Local preview

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8000
```

and visit `http://localhost:8000`.
