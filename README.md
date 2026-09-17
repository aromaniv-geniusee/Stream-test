# TaskFlow — Feature Specifications

This folder holds feature specs for **TaskFlow**, a lightweight team task-management app (fictional — used here as practice material for the Git/GitHub session).

## Conventions

- One file per feature: `feature-<short-name>.md`
- Each spec follows the same structure:
  - **Status** — Draft / In Review / Approved
  - **Overview** — one or two lines on what the feature does and why
  - **User Story** — "As a ___, I want ___, so that ___"
  - **Acceptance Criteria** — Given/When/Then, one per line
  - **Out of Scope** — explicitly excluded behavior
  - **Open Questions** — unresolved items for the client or dev team

## Current Specs

| File | Feature | Status |
|---|---|---|
| `feature-user-registration.md` | User Registration | Approved |
| `feature-task-creation.md` | Task Creation | In Review |
| `feature-task-reminders.md` | Task Reminders | Draft |

## Suggested Practice Exercises

- **Update**: add a new acceptance criterion to `feature-user-registration.md`, commit with a clear message.
- **Remove**: delete `feature-task-reminders.md` on a branch to simulate a descoped feature, open a PR.
- **Add**: create `feature-task-search.md` following the same structure, commit and push.
