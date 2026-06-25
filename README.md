# Kelly & Paulin — Liste de Cadeaux

A single-page wedding gift-list site. Pure HTML/CSS/JS, no build step, no dependencies
except Google Fonts. Loads instantly and works anywhere.

## Files
- `index.html` — the whole site
- `kelly.jpg`, `paulin.jpg` — the couple's hero photos

## Preview locally
Just double-click `index.html`, or:
```bash
open index.html
```

## Deploy to GitHub Pages
1. Create a new repo on GitHub (e.g. `kelly-paulin-mariage`).
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Wedding gift list"
   git branch -M main
   git remote add origin https://github.com/<your-username>/kelly-paulin-mariage.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source: `main` / root → Save**.
4. After ~1 minute the site is live at:
   `https://<your-username>.github.io/kelly-paulin-mariage/`

## Editing
- **Gift list:** edit the `gifts = [...]` array near the bottom of `index.html`.
- **Names / date / message:** all in the HTML near the top (search for "Kelly", "08 Août", "conviés").
- **Colors:** the palette is the `:root { --gold ... --green ... }` block at the top of the `<style>`.
- **Add real photos (optional):** the hero currently uses a "K & P" monogram. To use photos
  instead, drop `kelly.jpg` / `paulin.jpg` in this folder and ask to wire them into the hero.
