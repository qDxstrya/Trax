# Trax v8.4.2

Cardio logging is now flexible enough for outdoor cardio, treadmill work, circuits and rep-based conditioning.

## New cardio fields
Every cardio entry can optionally record:
- Time (minutes)
- Distance (km)
- Reps (no weight)
- Pace (minutes:seconds)
- Speed (km/h)

Only values you actually enter are displayed in workout history, exercise history and the current workout summary. Empty cardio metrics stay hidden. A cardio entry can be completed with any one or more of these metrics; time is no longer mandatory.

The same cardio fields also work when a cardio exercise is part of a superset and when editing a completed workout.

Workout-level Apple Watch stats from v8.4.1 remain unchanged: Active Calories, Total Calories and Average Heart Rate are entered once when finishing the whole workout.

## Updating GitHub Pages
Replace only `index.html`, `sw.js`, and `README.md` in the existing Trax repository. The exercise library, icon folder and saved data are not reset.
