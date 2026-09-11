# Trax v4

Trax v4 keeps all v3 workout/session functionality and cleans up the main interface.

## v4 changes
- Added a fifth bottom navigation tab: Settings.
- Settings sits directly to the right of Weight.
- Moved rest timer settings, backup export and backup restore off the Home page and into Settings.
- Removed the Data & Settings card from Home.
- Changed the Home hero eyebrow from `Trax Training` to `Trax`.
- Replaced the old `T` app icon with a black-background / red-dumbbell Trax icon.
- Keeps v3's blank safe-area spacing at the top, named workouts, grouped workout history, category icons, cardio timing, custom-exercise deletion, custom presets, PR logic, backup/restore, and offline PWA support.
- Uses the same `trax_*` localStorage keys, so updating the same GitHub Pages URL preserves your existing locally stored data.

## Updating the existing GitHub Pages version
Replace these files in the existing Trax repository:
- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `icon.svg`
- `README.md`

Commit them to `main`, wait for GitHub Pages to redeploy, then open Trax online once to allow the v4 service worker to cache the new files.

If iOS keeps showing the old Home Screen icon after the website updates, remove the Home Screen shortcut and add the same Trax URL to the Home Screen again. This does not change the website URL or its stored browser data.
