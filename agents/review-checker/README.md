# review-checker

A QA gate for every other agent in this set. It checks a deliverable against the five-point review checklist and returns a list of flagged issues. A human still makes the final call.

Source: "The Review Checklist" section of the Grok Bot article. This is the agent that most directly carries over from QA work.

## Run it

Run on any draft before a human reviews it. Other agents can call it as a last step.

1. Point it at a draft file (for example `clients/<client>/drafts/*.md`).
2. Optionally point it at the client's `voice.md`, `never.md`, and source material.
3. Run `agent.md`. It writes `review-report.md` next to the draft.

## Rules

- It flags; it does not fix. It never edits the draft.
- It never marks anything as approved. Approval is always a human decision.

## Files

- `agent.md`: the checklist and procedure
