# Trax v8.2.3

Hotfix for faster set-to-set logging.

## Changes
- Applies to both normal single-exercise logging and supersets.
- Set 1 / Round 1 stays blank so you can type your starting weight and reps manually.
- After completing a strength set, the next set is automatically pre-filled with the same weight and reps.
- In supersets, Exercise A and Exercise B each independently inherit their own values from the previous round.
- The weight `+ / -` buttons now naturally work from the pre-filled value using your currently selected weight increment (5 kg by default, or whatever you type).
- Rep `+ / -` buttons work from the pre-filled rep count in steps of 1.
- Cardio entries remain blank between rounds/entries because this patch specifically targets strength weight/reps logging.
- Previous-session values still appear as placeholders/reference for the first set, but are not automatically entered.
- Keeps all v8.2.2 searchable-superset, permanent library-add, grouped exercise library, frozen library, analytics, supersets, autosave, workout editing and settings features.
- Offline cache bumped to v8.2.3.

## GitHub update
Replace only:
- `index.html`
- `sw.js`
- `README.md`

Your existing icons, manifest, frozen library and saved Trax data do not need to change.
