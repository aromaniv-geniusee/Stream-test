# Feature: Task Reminders

**Status:** Draft

## Overview

Sends the user a reminder notification ahead of a task's due date.

## User Story

As a user with an upcoming task,
I want to receive a reminder before it's due,
So that I don't miss the deadline.

## Acceptance Criteria

- Given a task has a due date, when it's 24 hours before due, then the user receives an email reminder.
- Given a user has disabled reminders in settings, when a task becomes due soon, then no reminder is sent.
- Given a task is marked complete, when a reminder would otherwise fire, then it's suppressed.

## Out of Scope

- SMS or push notification reminders — email only at this stage.
- Configurable reminder timing (e.g. "remind me 2 days before").

## Open Questions

- Is this feature still in scope for the initial release, or does it move to a later phase?
- Who owns the notification infrastructure — is it reused from another product?
