# Trax v8.3.2

Small icon hotfix built on v8.3.1.

## Changes
- The existing red heart **Cardio** icon is now included as a selectable icon alongside the 24 muscle icons.
- Exercise Add/Edit icon picker now lets you explicitly choose the Cardio heart icon.
- Cardio remains the default icon when creating/editing an exercise in the Cardio category unless you choose something else.
- Custom preset icon picker can also use the Cardio heart icon.
- Completed workouts that contain only cardio exercises automatically use the Cardio heart icon on Home / Recent Training.
- Workouts started from a preset preserve that preset's chosen icon, including the Cardio icon.
- Active-workout / Next Up display respects the workout icon when available.
- No exercise-library reset or saved-data changes.
- Offline cache bumped to v8.3.2.

## GitHub update
Replace only:
- `index.html`
- `sw.js`
- `README.md`

The existing `icons` folder, `icon.svg`, manifest, frozen library and user data remain unchanged.
