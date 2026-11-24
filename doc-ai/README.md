# n-fit — documentation

n-fit is an Android app (React Native) that shows the user's health and activity statistics (steps and similar metrics) using the data Android already collects.

It exists because the author owns a Nothing Phone, and Nothing has no health app. The author had this on an iPhone through Apple's Health app and wants the same view on Nothing. The UI follows Nothing's visual style; the author will write `design/DESIGN.md` for it.

## Status

Idea captured. The rest of the documentation is not generated yet.

## Decisions so far

- Platform: Android, React Native.
- Language of docs, code and comments: English.
- Has a UI: yes (Nothing-style aesthetic, `DESIGN.md` provided by the author).

## Open questions

- Which metrics beyond steps (distance, calories, sleep, heart rate, workouts)?
- Data source on Android (e.g. Health Connect) and how history is read.
- Does it need its own database / local storage, or only reads from the OS?
- Is it built from scratch in phases (`core/plan/`)?
- Target users: just the author, or published publicly?
