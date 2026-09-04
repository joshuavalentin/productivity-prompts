# This Week

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Create one concise overview of the current week across commitments, deadlines, active work, and likely follow-ups.

## Workflow

1. Determine the user's local week boundaries.
2. Retrieve calendar events for the current week and identify important fixed commitments.
3. Retrieve tasks due this week, overdue tasks that still matter, and high-priority active work.
4. Identify meaningful email follow-ups or promised responses that affect this week.
5. Identify active GitHub work, milestones, issues, or pull requests that materially affect near-term workload.
6. Merge duplicates and separate fixed commitments from flexible work.
7. Identify overloaded days, deadline clusters, preparation needs, and waiting states.
8. Recommend a realistic weekly focus using the shared prioritization model.

## Default output

- `Week at a glance` — key appointments and deadlines by day.
- `Must finish this week` — normally no more than five items.
- `Prepare` — meetings or commitments needing advance work.
- `Waiting` — meaningful external dependencies.
- `Risks` — overload, conflicts, overdue commitments, or missing decisions.
- `Weekly focus` — one concise recommendation.

## Rules

- Do not list every low-value task or GitHub issue.
- Treat backlog as background unless it is explicitly promoted into this week.
- Prefer exact dates for commitments.
- Continue with partial coverage if a source is unavailable and state that briefly.
