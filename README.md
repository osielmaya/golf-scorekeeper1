# 9-Hole Golf Scorekeeper PWA

Installable, offline-ready app for tracking 9-hole golf rounds.
- Vertical scorecard (rows = Holes 1–9, columns = players)
- Stroke play only (no pars)
- Preset players, named course
- Save rounds + Live Leaderboard + Season Standings

---

## 🚀 Deploy on GitHub Pages (step-by-step)

1. **Create a repo** at https://github.com/new  
   - Name: `golf-scorekeeper`  
   - Public → *Create repository*

2. **Upload these files** (exactly at the repo **root**):  
   - `index.html`  
   - `manifest.webmanifest`  
   - `service-worker.js`  
   - `icons/` folder (contains PNG icons)

   In GitHub, click **Add file → Upload files**, drag everything from this ZIP (don’t upload the ZIP itself), then **Commit changes**.

3. **Enable Pages:**  
   - Repo **Settings → Pages**  
   - **Source:** `main` branch, **Folder:** `/ (root)` → **Save**

4. **Open your site:**  
   https://osielmaya.github.io/golf-scorekeeper/

5. **Install the app:**  
   - **Android/Chrome:** menu (⋮) → **Install app**  
   - **iPhone/Safari:** **Share** → **Add to Home Screen**

---

## 🔁 Updating later
Upload new versions of the same files and **Commit**.  
If changes don’t appear immediately, bump the cache name inside `service-worker.js` (e.g., `golf9-vertical-v1` → `golf9-vertical-v2`) and refresh.

## 🧰 Project structure
```
index.html
manifest.webmanifest
service-worker.js
icons/
```

## 🆘 Troubleshooting
- **404 page**: Files must be in the repo **root**, and Pages must point to `/(root)`.  
- **Old version showing**: Your browser may be using the service worker cache; do a hard refresh, or bump the cache name in `service-worker.js` and reload.

---

© You own your copy. Enjoy the Sunday rounds!
