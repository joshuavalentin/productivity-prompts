# GitHub Work

Resolve this workflow through root `prompts.json` and load every required shared contract before execution.

## Purpose

Create a compact overview of development work that currently deserves attention across relevant GitHub repositories.

## Workflow

1. Identify the repositories relevant to the user's current work context or explicit request.
2. Retrieve active issues, pull requests, and recent work that can materially affect current priorities.
3. Distinguish `In progress`, `Ready next`, `Blocked/waiting`, and `Backlog`.
4. Prefer work with explicit target releases, milestones, blockers, or current activity over unrelated open issues.
5. Merge related issue/PR information into one logical work item when appropriate.
6. Recommend one next development focus.

## Rules

- An open issue is not automatically active work.
- Do not elevate Future/Backlog work merely because it is recent or interesting.
- Preserve GitHub as the authoritative source for issue and PR state.
- Do not modify issues, labels, milestones, or pull requests without explicit user instruction.
