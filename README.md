# Trax v8.4

Trax v8.4 adds optional Apple Watch workout metrics to exercise logs.

## New in v8.4
- Cardio still records duration, and can now also store **Active Calories**, **Total Calories**, and **Average Heart Rate**.
- Strength exercises can store the same three Apple Watch metrics.
- Apple Watch fields are optional; leave them blank when you do not want to record them.
- Supersets support separate Apple Watch stats for Exercise A and Exercise B.
- Saved Apple Watch stats appear in current workout summaries, completed workout history, exercise history, and Progress history.
- Completed workouts can be edited later to add or correct Apple Watch stats.
- Backup/restore automatically includes the new metrics because they are saved directly with each exercise log.
- Existing Trax data and the frozen exercise library are preserved.
- Offline cache bumped to v8.4.

## GitHub update
Replace only:
- `index.html`
- `sw.js`
- `README.md`

Your existing `icons` folder, `icon.svg`, `manifest.webmanifest`, frozen library, and saved app data do not need to be replaced.
