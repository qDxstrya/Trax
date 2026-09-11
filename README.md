# Trax v7

Trax v7 adds per-exercise icon selection.

## v7 changes
- Every exercise now has three editable fields: **Name, Category, and Icon**.
- The Add/Edit Exercise screen includes the same **24-icon selector** used for custom workout presets.
- New exercises store the chosen icon permanently.
- Existing built-in and custom exercises can be edited and assigned any of the 24 icons.
- The selected icon follows the exercise through the Exercises library, workout exercise picker, preset builder, active workout, and new workout history entries.
- Existing exercises without an explicitly chosen icon keep their current category-based default until edited.
- Existing cardio exercises without a custom icon retain the red heart icon; if edited, you can choose any of the 24 muscle icons.
- Keeps all Trax v6 functionality and the same `trax_*` storage keys.

## Updating from v6
The 24 PNG files are unchanged, so if your v6 `icons` folder is already installed correctly, you only need to replace these root files in your existing Trax GitHub repo:
- `index.html`
- `sw.js`
- `README.md`

`manifest.webmanifest`, `icon.svg`, and the `icons` folder can stay as they are.

Commit to `main`, let GitHub Pages redeploy, then open Trax online once so the v7 service worker refreshes the offline cache.
