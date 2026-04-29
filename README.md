# Tatun Birthday Website

A static, single-page birthday website built with plain HTML/CSS/JS.

## Structure

- `index.html` — the entire site (HTML, CSS, and JS inline)
- `uploads/` — photos used in the page

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

This is a static site. It works on any static host:

- **GitHub Pages** — push to GitHub, then enable Pages in *Settings → Pages* (deploy from `main`, root).
- **Netlify** / **Vercel** / **Cloudflare Pages** — drag the folder in, or connect the repo.
