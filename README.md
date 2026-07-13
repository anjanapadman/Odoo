# Anjana P V — Portfolio

A single-page portfolio site for Anjana P V, Python / Odoo Developer.
Built as a static HTML file — no build step, no dependencies beyond Google Fonts.

## Files
- `index.html` — the full site (open directly in a browser, or deploy as-is)

## Deploy on GitHub Pages
1. Push this repo to GitHub (see commands below).
2. In the repo: **Settings → Pages → Source** → select the `main` branch and `/ (root)` folder → Save.
3. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

## Push to your GitHub repo

```bash
# from inside this folder
git init
git add .
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

If the repo already exists and has commits, skip `git init` and instead:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cp index.html README.md <repo-name>/
cd <repo-name>
git add .
git commit -m "Add portfolio site"
git push
```
