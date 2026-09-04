# Prepare Meetings

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Identify upcoming meetings that need preparation and produce a compact prep checklist.

## Workflow

1. Retrieve relevant upcoming calendar events for the requested period.
2. Select meetings that plausibly require preparation based on title, description, attendees, linked context, or explicit user instruction.
3. Retrieve related Gmail or GitHub context only when it materially improves preparation.
4. Summarize the meeting objective, decisions needed, relevant open items, and a short preparation checklist.
5. Prioritize meetings by proximity and consequence.

## Rules

- Do not invent an agenda from a vague event title.
- Distinguish known facts from suggested talking points.
- Avoid reproducing full email threads; summarize relevant context.
- Do not modify calendar events or send preparation material automatically.
