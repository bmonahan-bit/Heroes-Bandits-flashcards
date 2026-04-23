# Heroes-Bandits Flash Cards

A standalone web app for training the mental game of golf using the **Five Heroes vs. Five Bandits** framework from Paul Monahan's *The Most Important Game*.

## What's inside

- **Learn** — concept cards explaining each Hero (Love, Acceptance, Commitment, Vulnerability, Grit) and each Bandit (Fear, Frustration, Doubt, Shame, Quit), plus their matchups
- **Practice** — four flash card drills:
  - Identify the Bandit
  - Identify the Hero
  - Counter the Bandit (pick the Hero that answers a scenario)
  - Rapid Fire — Hero or Bandit?
- Streak tracking, screen effects, confetti on strong scores, light/dark theme

## Tech

Single-file HTML app. React + Babel loaded via CDN. No build step. Just open `index.html`.

## Deploy

Drop the repo into Netlify — it auto-detects the static site and serves `index.html`. The included `netlify.toml` sets the publish directory.

## Local preview

Any static server works:

```bash
npx serve .
# or
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Companion to

The Mental Game Scorecard — hole-by-hole tracking app for the same framework.
