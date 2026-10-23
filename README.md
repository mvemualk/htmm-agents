# htmm-agents

Six independent agents, each in its own folder under `agents/`. Run one as needed.

| Folder | What it does | Schedule |
|---|---|---|
| `agents/content-repurposer` | One long-form piece into newsletter, thread, posts, script | Mondays 08:00 |
| `agents/lead-researcher` | Researches prospects against an ideal-customer profile | Mondays 07:00 |
| `agents/site-updater` | Verifies directory listings, drafts weekly newsletter | Tuesdays 07:00 |
| `agents/inbox-triage` | Sorts messages, drafts FAQ-based replies | Weekdays 07:30 |
| `agents/competitor-report` | Monthly competitor pricing and positioning report | First business day, 09:00 |
| `agents/review-checker` | QA gate: checks any draft against the review checklist | On demand |

Each folder has a `README.md` (how to run), `agent.md` (the brief), and `routine.md` (schedule).

## Rules for all agents

- Drafts only. No agent publishes, sends, or contacts anyone.
- Client data never goes in this repo. Keep `clients/` and `site/` data outside git.
