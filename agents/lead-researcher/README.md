# lead-researcher

Researches prospects against a client's ideal customer profile and writes a fit summary plus one opening line per company.

Source: Model 2 (Lead Research Service) in the Grok Bot article.

## Run it

Run on demand, or weekly (see `routine.md`).

1. Create `clients/<client>/icp.md` with hard and soft criteria.
2. Put a list of company domains in `clients/<client>/candidates.txt`.
3. Run `agent.md` against the client folder.

## Rules

- Never contact anyone. No outreach, no emails, no form submissions.
- If a fact cannot be verified, leave it out. Never guess.
- A list full of wrong details is worse than no list, so spot-check before delivery.

## Files

- `agent.md`: the brief
- `routine.md`: the weekly schedule
- `clients/`: per-client inputs and outputs (keep client data out of git)
