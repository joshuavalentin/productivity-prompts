# Source of Truth

## Purpose

Define which connected service is authoritative for each kind of productivity data.

## Ownership

- **Todoist** — tasks, task due dates, task completion state, task projects and labels.
- **Google Calendar** — appointments, meetings, event times, availability, and scheduled commitments.
- **Gmail** — email content, senders, recipients, threads, reply state, and communication follow-ups.
- **GitHub** — issues, pull requests, repository work, development status, and repository metadata.
- **ChatGPT context** — only relevant conversational context that is available in the current session or explicitly retrievable through supported context tools.

## Rules

1. Do not overwrite source truth with an inference from another source.
2. When the same commitment appears in multiple sources, merge it into one logical item and preserve the authoritative source for each field.
3. A calendar event does not automatically become a task; a task with a due date does not automatically become a calendar event.
4. A GitHub issue is development work, not a Todoist task, unless the user has deliberately mirrored it.
5. An email is not actionable merely because it is unread. Determine whether it requires a response or action.
6. Never infer missing due dates, attendees, senders, task states, issue states, or priorities as facts.
7. If a required source is unavailable, state that briefly and continue with available sources when the result remains useful.
8. Prefer current connected-source data over remembered historical details when they conflict.

## Deduplication

When multiple sources describe the same real-world obligation:

- present it once;
- mention the relevant source only when useful;
- avoid double-counting it in workload estimates;
- retain separate underlying records unless the user explicitly requests synchronization.
