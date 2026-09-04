# Open Loops

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Find meaningful unfinished commitments across connected sources and reduce mental load by separating what needs action from what is merely open.

## Sources

Use Todoist, Gmail, Google Calendar, GitHub, and relevant ChatGPT context when available and relevant.

## Workflow

1. Find overdue or unfinished tasks.
2. Find important email threads where the user owes a reply or action, and threads where the user is waiting on someone else.
3. Find active GitHub issues or pull requests that appear genuinely in progress, blocked, or awaiting follow-up.
4. Find upcoming commitments that require preparation.
5. Include explicit commitments from relevant current ChatGPT context only when they are concrete enough to act on.
6. Merge duplicates and remove stale ideas that have no current obligation unless they are clearly active.
7. Classify each remaining loop.

## Default output

### Action needed
Items the user can act on now.

### Waiting
Items blocked by another person, service, or decision.

### Upcoming
Near-term commitments that are not actionable today but should remain visible.

### Backlog
Only include this section when a small number of active-but-not-urgent items are useful to preserve.

Finish with one concise recommendation about which open loop to close first.

## Rules

- Do not treat every unread email, open issue, or backlog task as an open loop.
- Prefer obligations with a clear next action.
- Avoid reproducing sensitive email contents when a short summary is sufficient.
- This command is read-only unless the user explicitly requests changes.
