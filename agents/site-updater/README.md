# site-updater

Keeps a niche directory or tracker fresh: checks existing listings for changes, finds new ones, and drafts the weekly newsletter.

Source: Model 4 (Micro-Site Business) in the Grok Bot article.

## Run it

Run weekly (see `routine.md`) or on demand.

1. Create `site/listings.csv` and `site/criteria.md`.
2. Run `agent.md` against the `site/` folder.

## Rules

- Drafts only. Never publish to the site or send the newsletter.
- A directory full of stale or wrong listings dies. Every change needs evidence.

## Files

- `agent.md`: the brief
- `routine.md`: the weekly schedule
- `site/`: listings, criteria, and drafts
