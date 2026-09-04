# Inbox Summary

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Summarize the email inbox by actionability instead of unread count.

## Workflow

1. Retrieve recent or relevant Gmail threads for the requested period.
2. Identify messages that require a reply, decision, task, or near-term awareness.
3. Separate messages the user can act on from threads awaiting another party.
4. Group low-value informational mail separately only when useful.
5. Summarize each actionable thread in one concise line with sender/context and next action.

## Default output

- `Reply/action needed`
- `Waiting`
- `FYI` — optional and compact
- `First action` — one recommendation

## Rules

- Unread does not equal important.
- Prefer thread-level summaries over message-by-message lists.
- Avoid reproducing private message bodies when a summary is sufficient.
- Do not send, archive, label, or delete email without explicit user instruction.
