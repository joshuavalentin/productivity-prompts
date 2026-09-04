# Today

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Create one concise, actionable overview of what matters today across all relevant connected productivity sources.

## Sources

Use the relevant available sources, normally:

- Todoist for tasks and due dates;
- Google Calendar for today's events and time constraints;
- Gmail for genuinely actionable or time-sensitive communication;
- GitHub for active development work, assigned/open issues, and recently active work when relevant;
- relevant ChatGPT context for commitments or work explicitly established in the current conversation.

Do not query a source merely to fill a section. Query it because it can materially change today's priorities.

## Workflow

1. Determine the user's local date and current time when needed.
2. Retrieve today's calendar commitments and identify fixed time blocks.
3. Retrieve tasks due today, overdue tasks, and high-priority active tasks.
4. Identify email threads that require action today or are blocking another commitment. Do not equate unread with important.
5. Identify active GitHub work that is currently in progress, due, blocking, or directly relevant to today's stated work.
6. Merge duplicates across sources.
7. Classify items into executable work, waiting states, schedule commitments, and optional/backlog work.
8. Prioritize using `contracts/PRIORITIZATION.md`.
9. Return one compact overview, not one report per source.

## Default output

Prefer:

- `Must` — normally no more than three items;
- `Next` — useful work after Must;
- `Agenda` — fixed appointments and meaningful preparation blocks;
- `Waiting` — only if something important depends on another person/system;
- `Attention` — conflicts, overdue risks, deadlines, or important unanswered follow-ups;
- `Focus` — one concise recommendation for what to do first.

Omit empty sections.

## Rules

- Distinguish facts from recommendations.
- Never invent task priority, deadlines, meeting details, or email urgency.
- Keep optional ideas and distant backlog out of `Must` unless the user explicitly elevates them.
- If the day is overloaded, say what should move rather than pretending everything fits.
- If a relevant source is unavailable, continue with available data and mention the missing source briefly.
