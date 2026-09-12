# Trax v8.2.2

Hotfix for the superset builder.

## Changes
- Replaced the huge Exercise A / Exercise B dropdown menus with dedicated search pickers.
- Search by exercise name or muscle category.
- Tap a result to select it, with a compact selected-exercise card shown above the search field.
- Exercise A and Exercise B are validated so the same exercise cannot be selected twice.
- Added **Add new exercise to library** directly under both superset search fields.
- New exercises created from the superset builder are saved to the main Trax exercise library permanently.
- After saving a new exercise, Trax returns to the superset builder and automatically selects it on the side you were editing.
- If the typed name already exists exactly, Trax reuses the existing library exercise instead of creating a duplicate.
- Keeps all v8.2.1 library grouping, icon-picker, frozen-library, v8.2 features, supersets, autosave, history and settings.
- Offline cache bumped to v8.2.2.

## GitHub update
Replace only:
- `index.html`
- `sw.js`
- `README.md`

Your existing icons folder and other PWA files do not need to change.
