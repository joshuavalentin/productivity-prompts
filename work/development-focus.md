# Development Focus

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Choose the most logical development focus when several repositories, issues, or workstreams compete for attention.

## Workflow

1. Retrieve the relevant active GitHub work.
2. Include calendar deadlines, client commitments, and blocking communication when they materially affect development priority.
3. Apply the shared prioritization model.
4. Prefer completing active work and release-critical dependencies over starting optional new work.
5. Recommend one primary issue/workstream and, when useful, one secondary fallback.
6. Explain the choice in no more than a few concise sentences.

## Default output

- `Primary focus` — repository/issue/workstream and why.
- `After that` — optional next item.
- `Do not start yet` — only when a competing workstream should explicitly remain parked.

## Rules

- Do not equate newest issue with highest priority.
- Do not move target releases, milestones, statuses, or labels automatically.
- If source data is insufficient to choose confidently, state the uncertainty and give the best bounded recommendation.
