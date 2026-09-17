# Feature: Task Creation

**Status:** In Review

## Overview

Allows a logged-in user to create a new task with a title, optional description, and due date.

## User Story

As a logged-in user,
I want to create a task with a title and due date,
So that I can track work I need to complete.

## Acceptance Criteria

- Given a logged-in user on their task list, when they enter a title and save, then a new task appears at the top of the list.
- Given a user tries to save a task with no title, when they submit, then they see a validation error and no task is created.
- Given a user sets a due date in the past, when they submit, then they see a warning but are still allowed to save the task.
- Given a task is created, when it appears in the list, then it defaults to status "Not Started."

## Out of Scope

- Recurring tasks (daily/weekly repeats) — tracked as a separate feature.
- Task templates.

## Open Questions

- Is there a maximum title length we should enforce?
- Should tasks support attachments at launch, or is that a later phase?
