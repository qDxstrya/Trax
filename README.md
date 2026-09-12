# Trax v8.2 — final build

A major quality-of-life, logging and analytics update built on the frozen v8.1 exercise library.

## Core upgrades
- Welcome-back Home greeting for Mohamed with one fresh training line chosen per app launch.
- Beat Last Time progression targets.
- One-tap Repeat Last Set.
- +/- weight and rep controls with a live, typeable kg increment. Default is 5 kg; type 10 for +/-10 kg, type 1 for +/-1 kg, etc.
- Editable completed workouts: rename the session, correct weights/reps, change set type, delete sets/exercises, or delete the whole workout.
- Persistent exercise notes.
- End-of-workout summary with duration, working sets, volume, PRs, cardio minutes, muscles trained and comparison with the previous workout of the same name.
- Optional set types: Warm-up, Working, Drop, Failure and AMRAP. Warm-ups are excluded from PR, volume, weekly-set and strength-progress analytics.
- Reorder completed workout exercises and reorder preset-plan exercises while training.
- Swap a currently selected exercise before saving it, or replace an already logged exercise mid-workout.
- Weekly working-set dashboard by muscle group.
- Optional muscle heatmap covering the major muscle categories.
- Optional simple recovery indicators based on time since each muscle group was last trained.
- Rich exercise detail/history screen with latest performance, best weight, best reps, best e1RM, total entries and a trend graph.
- Presets can save target sets, rep ranges and rest times per exercise.
- Built-in Push / Pull / Legs presets only reference exercises that still exist in the frozen library.
- Compact Home Next Up card with last-workout and current-week context.
- Mid-workout autosave for unsaved sets, supersets and active rest timers.
- Smart keyboard flow: Enter/Next goes weight -> reps -> complete set where the iPhone keyboard supports it.
- Active-workout quick actions: move, replace, note or remove.
- Workout-vs-last-workout comparison.
- Favourite and recent exercise quick picks.
- Schema v82 migration layer with a one-time pre-v8.2 safety snapshot.
- All new v8.2 user-facing features are individually toggleable in Settings.

## Preserved from v8.1
- Your frozen/refined exercise library remains the source of truth. Deleted exercises are not silently re-added.
- Proper A/B supersets with rest starting only after both sides of the round are completed.
- One-set-per-line workout history formatting.
- Cardio time tracking.
- Rest timer sound, vibration where supported, and best-effort Home Screen notification alerts.
- Existing black/red styling, icons, backups and offline PWA behaviour.

## Updating your existing GitHub Pages install
Replace/upload these files in the existing Trax repo:
- `index.html`
- `sw.js`
- `README.md`

You do **not** need to replace the `icons/` folder, `icon.svg`, or `manifest.webmanifest`; they are unchanged from the current build.

Open the live Trax site online once after GitHub Pages deploys so the new v8.2 service worker caches the updated app for offline use.

`frozen-library.json` is included in this ZIP only as a readable reference copy. It is **not required** on GitHub because the frozen library is embedded directly in `index.html`.
