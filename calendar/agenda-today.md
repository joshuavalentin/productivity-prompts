# Agenda Today

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Show today's calendar commitments in a compact operational view.

## Workflow

1. Determine today's local date and current time when relevant.
2. Retrieve today's Google Calendar events.
3. Order chronologically.
4. Flag overlaps, tight transitions, travel/preparation needs when supported by event details or relevant context.
5. Mention meaningful free blocks only when useful for planning.

## Output

Show time, event title, and only the context needed to act. Finish with one short schedule observation when useful.

## Rules

- Calendar is authoritative for event times.
- Do not add or move events automatically.
- Do not infer preparation requirements without evidence.
