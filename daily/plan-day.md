# Plan Day

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Turn today's commitments into a realistic execution order.

## Workflow

1. Determine current local date/time when needed.
2. Retrieve today's fixed calendar commitments.
3. Retrieve relevant Todoist tasks, overdue work, and high-priority active work.
4. Retrieve actionable communication and blocking GitHub work only when it can affect sequencing.
5. Estimate sequencing from known deadlines, dependencies, meeting preparation, and context-switching cost. Do not invent duration when unknown.
6. Protect fixed calendar events.
7. Recommend one primary focus and a small number of secondary actions.
8. If the workload exceeds available time, identify what should be deferred.

## Default output

- `Start with` — the first concrete action.
- `Execution order` — short ordered list.
- `Fixed agenda` — today's immovable calendar items.
- `Move/defer` — only when needed.
- `Reasoning` — one or two concise sentences explaining the sequencing.

## Rules

- This command plans; it does not modify Todoist or Calendar by itself.
- Prefer finishing active work before optional new work.
- Do not fill every free hour unless the user asks for time blocking.
- Keep the plan realistic and compact.
