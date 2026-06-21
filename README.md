# Soft Reset — XenoROM Voice (landing page)

Static landing page for the XenoROM Voice download. It's the **canonical link** to put in videos
and posts — it points at the live download mirrors (itch.io + GitHub Releases) so your shared
links never break if a host changes or pulls the file.

> Kept as its own repo, separate from the private promo workspace — this repo is public-safe only.

## Publish on GitHub Pages (no CLI needed)
1. Create a **new public repo** on github.com (e.g. `softreset-xenorom`), empty.
2. On the repo page → **Add file → Upload files** → drag in everything from this folder
   (`index.html`, `README.md`, `.nojekyll`, and the `assets/` folder) → Commit.
3. **Settings → Pages → Source:** "Deploy from a branch", branch `main`, folder `/ (root)` → Save.
4. ~1 minute later it's live at `https://<your-user>.github.io/softreset-xenorom/`.

## Before sharing the link
- Replace the two `href="#"` download buttons in `index.html` with the real **itch.io** and
  **GitHub Releases** URLs.
- Optional, later: point `softreset.gg` at this page for a short, on-brand URL.

Free, non-commercial fan project. AI-generated voices. Not affiliated with or endorsed by Square Enix.
