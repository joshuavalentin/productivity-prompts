# Action Safety

## Principle

**Analyze freely. Mutate deliberately.**

## Read mode

Commands in version `0.1.0` are read/analysis-first. They may retrieve, compare, summarize, deduplicate, and prioritize information from connected services without modifying those services.

## Mutation mode

Only modify an external system when:

1. the user explicitly asks for the change;
2. the exact target is identifiable;
3. the requested mutation is supported by an available connected tool;
4. the change is consistent with the source-of-truth contract;
5. destructive or broad changes are not inferred from a read-only productivity command.

## Examples

Allowed after explicit request:

- create or update a Todoist task;
- create or update a calendar event;
- prepare or send an email when explicitly requested;
- update a GitHub issue when explicitly requested.

Not allowed from a read-only command alone:

- reschedule tasks because `plan-day` recommended a different order;
- move calendar events automatically;
- archive or send email automatically;
- close or reprioritize GitHub issues automatically.

## Confirmation

For consequential or ambiguous mutations, present the intended change before applying it unless the user's instruction is already precise enough to execute safely.

## Privacy

Retrieve and expose only the information needed for the current productivity objective. Prefer summaries over reproducing full private messages or unrelated personal details.
