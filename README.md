# Agency AI Lie Detector 🤔

Calculate the probability your agency is lying about AI.

Twelve quick yes/no questions across three tests:

1. **Interrupt the prerecorded video** — did they show a real working tool, or theatre?
2. **Bait problems and risks** — did they admit failure modes, or stay vague?
3. **Probe belief, not technique** — do they have a philosophy, or a tech stack?

Each "No" counts as a lying signal. The overall score is the average across the tests you've answered.

| Score | Verdict |
|---|---|
| 0-25% | Substance — sign them |
| 25-50% | Mostly real — scope tightly |
| 50-75% | Theatre suspected — push back |
| 75-100% | Almost certainly lying — walk |

## Run

Open `index.html` in any browser. No build step.

## Deploy

Push to `main` → Vercel auto-deploys as a static site.
