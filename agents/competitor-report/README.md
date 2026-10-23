# competitor-report

Produces a fixed-format monthly report on a client's competitors: pricing, launches, and positioning changes, with sources and a diff against last month's snapshot.

Source: Model 6 (Productized Research Report) in the Grok Bot article.

## Run it

Run monthly (see `routine.md`).

1. Create `clients/<client>/competitors.txt` with up to five domains.
2. Keep last month's snapshot in `clients/<client>/snapshots/`.
3. Run `agent.md` against the client folder.

## Rules

- Every claim needs a source URL and a capture date.
- The analyst verifies every fact before delivery. The agent drafts; the interpretation is human work.

## Files

- `agent.md`: the brief
- `routine.md`: the monthly schedule
- `clients/`: per-client inputs, snapshots, and reports
