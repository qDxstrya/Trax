# Trax v8.2.1

Hotfix release focused on the Exercises screen and icon selectors.

## Fixes
- Rebuilt the exercise Add/Edit icon selector as a compact black/red 4-column grid.
- Icon selector scrolls vertically inside its own area; Save/Cancel remain reachable.
- Applied the same clean icon selector to preset creation.
- Removed horizontal scrolling from the Exercises library.
- Exercise action buttons now wrap into a mobile-safe row beneath each exercise.
- Exercise library is grouped by muscle, then alphabetically inside each group.
- Exact group order: Chest, Shoulders, Triceps, Back, Biceps, Forearms, Legs, Core, Cardio, Other.
- Removed Full Body from selectable exercise categories. Existing Full Body entries are safely mapped to Other.
- Bumped the PWA cache so GitHub Pages/iPhone picks up the hotfix.

## Updating from v8.2
Replace `index.html`, `sw.js`, and `README.md` in the existing Trax GitHub repository. The `icons` folder, app icon, manifest and saved Trax data remain unchanged.
