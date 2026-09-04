# Productivity Prompts

A personal productivity prompt system for ChatGPT that combines tasks, calendar, email, GitHub, and conversation context into concise, actionable overviews.

## Version

`0.1.0`

## Author

Joshua Valentin

## License

Proprietary / no public license. All rights reserved.

## Core principle

**One overview, not one report per app.**

The source applications remain the source of truth. These prompts orchestrate, interpret, prioritize, and summarize information across connected services.

## Primary commands

| Command | Purpose |
| --- | --- |
| `today` | Show what matters today across all available sources. |
| `this-week` | Show the relevant commitments, deadlines, and focus for the current week. |
| `plan-day` | Turn today's commitments into a realistic execution order. |
| `open-loops` | Find unfinished commitments, pending replies, and unresolved work. |
| `inbox` | Triage actionable items across task, mail, and work inboxes. |
| `weekly-review` | Review the past week and prepare the next one. |

## Initial sources

- Todoist — tasks and task deadlines
- Google Calendar — appointments and time commitments
- Gmail — communication and follow-ups
- GitHub — development work and issue state
- ChatGPT context — relevant current-conversation context when available

A source may be unavailable in a specific ChatGPT session. Prompts must state missing sources explicitly and continue with the sources that are available.

## Structure

- `contracts/` — shared behavior, prioritization, source ownership, and action-safety rules
- `daily/` — daily overview and planning workflows
- `weekly/` — weekly overview and review workflows
- `tasks/` — task triage and prioritization workflows
- `calendar/` — agenda and meeting workflows
- `communication/` — inbox and follow-up workflows
- `work/` — GitHub and development-focus workflows
- `prompts.json` — canonical command registry and resolver

## Usage

Ask ChatGPT for a command directly, for example:

```text
today
```

or:

```text
open-loops
```

The prompt should load the shared contracts, query the available connected sources that are relevant to the command, deduplicate overlapping information, and return one compact overview.

## Mutation policy

Version `0.1.0` is analysis-first. Read and summarize freely. Never modify Todoist, Gmail, Calendar, GitHub, or another connected service unless the user explicitly requests the change and the mutation is supported safely.
