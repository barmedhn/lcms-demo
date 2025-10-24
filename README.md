# LCMS — Single-file Case Management System (SPA)

This is the exact `index.html` you edited in chat, saved so you can run it locally or deploy to GitHub Pages.

## Run locally
1. Download `index.html` below.
2. Double-click to open in Chrome/Edge/Firefox.
3. Data is stored in your browser (localStorage). Use **Settings → Export Backup** to save JSON.

## Deploy to GitHub Pages
1. Create a new repo (e.g., `lcms-spa`) on GitHub.
2. Upload `index.html` to the repo root.
3. In **Settings → Pages**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`) / root
4. Your app will be live at `https://<your-user>.github.io/<repo>/`.

## Notes
- Includes all modules: Cases, Document Writing (templates + versions), Client Portal, Workflow, Reports, Proposals, Settings.
- Uses CDN-only dependencies (Chart.js, QRCode). No build step required.
