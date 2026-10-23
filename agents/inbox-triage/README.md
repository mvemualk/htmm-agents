# inbox-triage

Sorts incoming messages by urgency, drafts replies to routine questions from the client's FAQ, and writes a morning summary. The client sends every reply.

Source: Model 5 (Inbox and Support Triage) in the Grok Bot article.

## Read this first

This agent touches private, sensitive data. Do not run it on a shared computer for clients with confidential inboxes. Use a restricted account the client controls, and keep each client's data separate. Revoke access and delete files when a client leaves.

## Run it

Run each morning (see `routine.md`).

1. Create `clients/<client>/faq.md` and `clients/<client>/escalation.md`.
2. Export or forward the day's messages into `clients/<client>/inbox/`.
3. Run `agent.md` against the client folder.

## Rules

- Never send. Every reply is a draft for the client to approve.
- Anything matching the escalation rules goes to the top, unanswered.
- Never store passwords, card numbers, or account numbers in these files.

## Files

- `agent.md`: the brief
- `routine.md`: the morning schedule
- `clients/`: per-client data (never commit; keep out of git)
