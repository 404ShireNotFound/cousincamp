# 🏅 Cousin Camp Olympics 2026

The home page / agenda hub for Cousin Camp — Olympics theme, Virginia & Washington DC, June 14–20, 2026.

`index.html` is the master hub. Each day links through to its own site as we build them. Day 2 (Science Day) links to the **scavenger-hunt-june-15** folder.

## Adding a new day's site

1. Make a folder for it (e.g. `G-Dubs - June 16/`) with its own `index.html`.
2. In `index.html`, find that day in the `DAYS` array and set its `link`, e.g.
   `link: "G-Dubs - June 16/"`
3. Save. The card automatically flips from **SOON 🔒** to **LIVE** with a working button.

## Publishing to GitHub Pages

1. Create a new repo on GitHub and push this whole folder (keep `index.html` at the root).
   ```
   git init
   git add .
   git commit -m "Cousin Camp Olympics site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
2. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, pick `main` / `root`, Save.
3. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.

That's it — the scavenger hunt and every future day work automatically because all links are relative.
