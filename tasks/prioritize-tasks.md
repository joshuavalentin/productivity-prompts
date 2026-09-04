# Prioritize Tasks

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Prioritize a set of tasks using deadlines, dependencies, external commitments, active-work state, and realistic capacity.

## Workflow

1. Retrieve or use the task set named by the user.
2. Preserve explicit user priorities.
3. Identify hard deadlines, blockers, dependencies, waiting states, and active work.
4. Apply `contracts/PRIORITIZATION.md`.
5. Group tasks into `Now`, `Next`, `Later`, and `Waiting` when useful.
6. Recommend what should not be active yet.

## Rules

- Do not change task priority or due dates automatically.
- Do not make every overdue task high priority.
- Prefer a small active set over a long ranked list.
- State when insufficient context prevents confident prioritization.
