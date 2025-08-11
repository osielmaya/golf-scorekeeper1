# 9-Hole Golf Scorekeeper PWA

Installable, offline-ready app for tracking 9-hole golf rounds.
- Vertical scorecard (rows = Holes 1–9, columns = players)
- Stroke play only (no pars)
- Preset players & nameable course
- Save rounds + Live Leaderboard + Season Standings

## Deploy to GitHub Pages (for `golf-scorekeeper1`)

1. Create a repo named **golf-scorekeeper1** (Public).
2. Click **Add file → Upload files** and upload these files at the **root**:
   - `index.html`
   - `manifest.webmanifest`
   - `service-worker.js`
   - `icon-192.png`
   - `icon-512.png`
   - `apple-touch-icon.png`
   - `README.md`
3. **Settings → Pages** → Source: `main` → Folder: `/ (root)` → **Save**
4. Open: `https://osielmaya.github.io/golf-scorekeeper1/`
5. Install:
   - Android/Chrome: menu (⋮) → **Install app**
   - iPhone/Safari: **Share** → **Add to Home Screen**

If an update doesn’t appear immediately, open `service-worker.js` and change the `CACHE_NAME` value (e.g., `-v2` → `-v3`), commit, and refresh.
