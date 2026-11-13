# Zakaria Ech.Chifaouy — Portfolio

Static portfolio site (plain HTML + CSS, no build step).

## Deploy on GitHub Pages

1. Create a repo named **`zech-chi.github.io`** (your site will be at `https://zech-chi.github.io`), or any name (site at `https://zech-chi.github.io/<repo>`).
2. Upload everything in this folder to the repo root (keep `.nojekyll`):
   ```bash
   git init && git add . && git commit -m "portfolio"
   git branch -M main
   git remote add origin https://github.com/zech-chi/zech-chi.github.io.git
   git push -u origin main
   ```
3. Repo → **Settings → Pages** → Source: *Deploy from a branch* → `main` / `(root)` → Save.

## Structure

```
index.html
assets/style.css
assets/img/                          screenshots & sprites
assets/Zakaria_Ech_Chifaouy_Portfolio.pdf   downloadable PDF version
```
