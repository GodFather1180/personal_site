# Personal Site

Static portfolio site — plain HTML/CSS/JS, no build step.

## Run locally

Open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. Repo Settings → Pages → Deploy from branch → `main` / root.
3. Site will be live at `https://<username>.github.io/<repo>/`.

## Structure

- `index.html` — all page content
- `styles.css` — theming (light/dark) and layout
- `script.js` — theme toggle, mobile nav
- `assets/` — resume PDF, favicon
