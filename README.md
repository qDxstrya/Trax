# Trax v8.3

Visual safe-area hotfix for the iPhone status bar.

## Changes
- Removes the oversized black spacer above Trax content.
- The black/red Trax background now extends flush behind the iPhone status area.
- The clock, signal, Wi-Fi and battery remain unobstructed.
- Actual app content still respects the iPhone safe area, so buttons and text do not sit underneath the Dynamic Island/status bar.
- Applies consistently to Home, Log, Progress, Exercises and Settings because all screens share the same safe-area shell.
- Changes standalone Home Screen status-bar mode to `black-translucent` so the Trax background can visually continue behind the system status area.
- Keeps every v8.2.3 feature and all existing saved data unchanged.
- Offline cache bumped to v8.3.

## GitHub update
Replace only:
- `index.html`
- `sw.js`
- `README.md`

Your icons folder, manifest, app icon, frozen exercise library and saved Trax data do not need to change.
