# Agenda Week

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Show the current week's calendar commitments in a compact, chronological view.

## Workflow

1. Determine the current local week boundaries.
2. Retrieve Google Calendar events for the week.
3. Group by day and order chronologically.
4. Flag overlaps, unusually dense days, and meaningful preparation needs when supported by the data.
5. Keep all-day informational events visually subordinate to timed commitments unless they affect action.

## Output

Use one compact section per day that contains relevant events. Finish with a short weekly schedule observation when useful.

## Rules

- Calendar is authoritative for event times.
- Do not create, move, or delete events automatically.
- Do not turn calendar density into a productivity judgment.
