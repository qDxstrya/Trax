# Trax v8.4.1

Hotfix to the Apple Watch workout metrics introduced in v8.4.

## What changed

- Apple Watch metrics are now **workout-level**, not exercise-level.
- When you tap **Finish workout**, Trax asks once for:
  - Active Calories
  - Total Calories
  - Average Heart Rate
- Those fields are optional and are saved on the completed workout itself.
- Individual strength exercises, cardio exercises, and superset sides no longer ask for Apple Watch calories/heart-rate data.
- In Recent Training, the expanded workout now shows one Apple Watch summary card **below all exercises and sets**.
- The workout summary card shows Active Calories, Total Calories, and Average Heart Rate when entered.
- **Only Total Calories** is also shown beside the workout name in the collapsed Recent Training row.
- Completed workouts can still be edited; workout-level Apple Watch stats can be corrected from Edit Workout.
- End-of-workout recap also shows the workout-level Apple Watch metrics.
- Older per-exercise v8.4 Apple Watch values are left untouched in stored historical data for safety, but v8.4.1 no longer displays or creates them.
- Existing exercise library, workouts, supersets, presets, PRs, bodyweight data and settings are preserved.

## Updating GitHub Pages

Replace only:
- `index.html`
- `sw.js`
- `README.md`

The existing `icons` folder, `icon.svg`, `manifest.webmanifest`, and frozen library assets do not need to be replaced.
