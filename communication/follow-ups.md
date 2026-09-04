# Follow Ups

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Find communication and work items that need a follow-up, either from the user or from another party.

## Workflow

1. Search relevant Gmail threads for replies owed, promises, unanswered requests, and waiting states.
2. Check upcoming calendar commitments for follow-ups tied to meetings or deadlines when relevant.
3. Check GitHub issues or pull requests where a response, review, or next action is pending when relevant.
4. Deduplicate the same obligation across sources.
5. Classify into `You need to follow up`, `Waiting on others`, and `Upcoming follow-up`.
6. Rank by consequence and age, not age alone.

## Rules

- Do not assume silence requires chasing unless there is a concrete dependency or expected response.
- Keep sensitive message details summarized.
- Do not send follow-up messages automatically.
