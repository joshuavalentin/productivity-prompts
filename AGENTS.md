# AGENTS.md

## Project

Productivity Prompts is a standalone prompt repository for orchestrating personal productivity data across connected services.

## Version

Current foundation: `0.1.0`.

## Repository principles

1. Keep prompts small, composable, and source-aware.
2. Prefer one combined answer over app-by-app reports.
3. Treat source applications as authoritative for their own data.
4. Never invent unavailable task, mail, calendar, or GitHub data.
5. State source availability or uncertainty when it materially affects the result.
6. Deduplicate the same commitment when it appears in multiple sources.
7. Separate read/analysis behavior from mutations.
8. Do not modify external systems without explicit user intent.
9. Keep repository-facing content in English unless explicitly requested otherwise.
10. Preserve backward-compatible commands through `prompts.json` when renaming workflows.

## Prompt design

Every canonical workflow must:

- resolve through `prompts.json`;
- load all required shared contracts;
- query only sources relevant to its objective;
- synthesize across sources before presenting output;
- prioritize actionable information over completeness;
- keep default output concise and scannable;
- identify blockers, deadlines, waiting states, and schedule conflicts when relevant;
- avoid turning low-value ideas or backlog items into urgent work.

## Connected services

Initial target sources are Todoist, Google Calendar, Gmail, GitHub, and relevant ChatGPT conversation context. Additional sources may be added later through shared contracts and resolver metadata.

## Safety and privacy

Personal productivity data may contain private or sensitive information. Retrieve the minimum relevant data, avoid unnecessary reproduction of message contents, and prefer summaries over raw dumps. Mutations must follow `contracts/ACTION-SAFETY.md`.

## Versioning

Use semantic versioning. Update `CHANGELOG.md` when behavior or command contracts change materially.
