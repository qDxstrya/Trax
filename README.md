# Trax v8

Trax v8 is a focused iPhone UI fix for the exercise/preset icon chooser.

## v8 fixes
- The 24-icon selector now scrolls inside its own compact panel instead of stretching the modal excessively.
- **Cancel / Save** stays pinned to the bottom of the modal so it is always reachable.
- Icon tiles are smaller and use four columns on iPhone to reduce vertical space.
- Improved iOS scrolling with `100dvh`, momentum scrolling, and overscroll containment.
- The same fix also improves the custom workout preset icon chooser.
- Updated the service-worker cache to `trax-v8` so the new patch replaces older cached UI files reliably.
- Keeps all v7 features and the same `trax_*` data keys.

## Updating from v7
The icon PNGs, app icon, and manifest are unchanged. Replace only:
- `index.html`
- `sw.js`
- `README.md`

Commit to `main`, wait for GitHub Pages to deploy, then open Trax online once so v8 is cached for offline use.
