# joeliu996.github.io

Personal homepage of Joe (Nazhou) Liu — a plain static site (`index.html` + `styles.css`), no build step.

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

1. Create a GitHub repo named `joeliu996.github.io` and push this folder to `main`.
2. In the repo: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. Every push to `main` redeploys via `.github/workflows/pages.yml`.

## Editing

- Content: `index.html` (each section is clearly marked).
- Photo: replace `assets/images/profile.svg` with e.g. `profile.jpg` and update the `<img>` src.
