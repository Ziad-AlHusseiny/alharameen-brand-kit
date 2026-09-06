# Al Harameen Steel — Brand Kit (static site)

Single-file presentation of the new brand identity: `index.html` + `assets/`.
No build step. Works on GitHub Pages, Vercel, Netlify, or by opening `index.html` directly.

## Deploy to GitHub Pages (public repo)

```bash
# from inside the brand-kit folder
git init
git add .
git commit -m "feat: Al Harameen Steel brand kit v1"
git branch -M main
git remote add origin https://github.com/<your-user>/alharameen-brand-kit.git
git push -u origin main
```

Then on GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
The page will be live in about a minute at `https://<your-user>.github.io/alharameen-brand-kit/`.

`.nojekyll` is included so GitHub serves the files as they are.

## Contents

| Path | What |
|---|---|
| `index.html` | The whole presentation (Arabic RTL, animations, scroll and hover effects) |
| `assets/*.svg` | Vector emblem and lockups |
| `assets/round*-contact-sheet.png` | The three exploration rounds |
| `assets/mockups/*.jpg` | Six photorealistic applications (hard hat, truck, facade, jacket, steel plate, lobby) |
| `assets/logo-old.png` | The previous logo, for the before/after slider |

## Sections

01 Story (before/after) · 02 Brand brief · 03 Four directions with scores · 04 Three rounds · 05 Mark anatomy (hover shows the grid) · 06 Lockups · 07 Colors (click to copy) · 08 Typography · 09 Interactive CSS mockups · 10 Photo mockups · 11 Do & Don't · 12 Files
