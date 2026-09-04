# Task Inbox

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Create one triage view of actionable inbox items across task, communication, and work sources.

## Workflow

1. Retrieve Todoist Inbox tasks and uncategorized actionable tasks when available.
2. Retrieve email threads that contain a concrete action or decision for the user.
3. Retrieve newly relevant GitHub work that requires triage rather than execution.
4. Include explicit current-conversation commitments only when they are concrete and unresolved.
5. Deduplicate overlapping items.
6. Classify each item into `Do`, `Schedule`, `Waiting`, `Backlog`, or `Ignore/archive recommendation`.

## Output

Keep each category compact. Put the most actionable items first and finish with one recommendation for clearing the inbox.

## Rules

- Do not classify unread mail as actionable without evidence.
- Do not modify, archive, schedule, or create tasks automatically.
- If a classification is uncertain, mark it as such rather than guessing.
