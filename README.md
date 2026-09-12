# Trax v8.3.1

Rollback hotfix for the v8.3 status-bar/safe-area change.

## What changed
- Restores the pre-v8.3 black iPhone status-bar area.
- Restores the larger safe-area spacer so Trax content sits below the clock, signal, Wi-Fi and battery exactly as before.
- Removes the black-translucent status-bar treatment introduced in v8.3.
- Keeps every v8.2.3 feature and all saved data unchanged.
- Bumps the service-worker cache so iPhone receives the rollback immediately.

## GitHub update
Replace only:
- `index.html`
- `sw.js`
- `README.md`

Your icon assets, manifest and local Trax data do not need to change.
