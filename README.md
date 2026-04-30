# Pitch Lie Detector

A single-page bingo scorecard for evaluating agency AI pitches.

Three tests, two boards each (Conviction · Fugazi). Mark squares as the pitch happens. Five in a row calls bingo. Conviction bingos greenlight; fugazi bingos walk.

## Run

Open `index.html` in any browser. No build step.

## Deploy

Push to `main` → Vercel auto-deploys as a static site.

## Notes

- All state is in-memory and per-session; refresh resets the board
- Print button (top right) renders a clean black-on-white version for hard-copy follow-up
- Reset clears all squares + notes
