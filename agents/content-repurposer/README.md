# content-repurposer

Turns one long-form piece (video transcript, podcast, article) into a newsletter section, a thread, five standalone posts, and a 60-second script, all in the client's voice.

Source: Model 1 (Content Repurposing Service) in the Grok Bot article.

## Run it

Run on demand, or weekly on Monday mornings (see `routine.md`).

1. Create `clients/<client>/` with `source/`, `drafts/`, `voice.md`, and `never.md`.
2. Drop the newest source file into `clients/<client>/source/`.
3. Give the agent `agent.md` as its brief and point it at the client folder.

## Rules

- Drafts only. Never publish or send.
- Quote the source accurately; never invent a quote.
- Follow `voice.md` exactly and avoid everything in `never.md`.
- Human edit and approval happen before delivery.

## Files

- `agent.md`: the brief the agent runs on
- `routine.md`: the weekly schedule
- `clients/`: per-client inputs and outputs (not committed; keep client data out of git)
