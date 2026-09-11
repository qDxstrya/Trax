# Trax v6

Trax v6 is a visual polish update to v5.

## v6 changes
- All 24 muscle-image selector assets now use **black backgrounds instead of white** so they match the black/red Trax interface.
- Replaced the Trax Home Screen/app icon with a **black-background, red dumbbell** based on the rounded dumbbell reference image.
- Keeps every v5 feature: Exercises tab, add/edit/rename/delete exercises anytime, cardio exercises, Bodyweight inside Progress, custom preset icon selection, named workouts, grouped history, PRs, backups, and offline PWA support.
- Keeps the same `trax_*` localStorage keys, so updating the same GitHub Pages URL should preserve existing stats.

## Updating your current Trax site
Replace/upload the v6 files into the same GitHub repository:
- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `icon.svg`
- `README.md`
- replace the entire `icons` folder with the v6 `icons` folder

Commit to `main`, wait for GitHub Pages to redeploy, then open Trax online once so v6 is cached for offline use.

If iOS keeps the previous Home Screen icon, remove only the Home Screen shortcut and add the same live Trax URL to Home Screen again. Your stored data remains tied to the same website origin.
