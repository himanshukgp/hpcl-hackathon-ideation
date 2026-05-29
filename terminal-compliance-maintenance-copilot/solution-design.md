# Solution Design

## Overview

The solution has three layers: a Power Apps operational dashboard, UiPath automation flows, and a Fluid AI assistant.

## Power Apps Layer

Power Apps provides the user interface:

- Task register with task name, category, owner, frequency, due date, status, and risk level
- Views for due today, due this week, overdue, completed, and upcoming
- Mobile task completion form with remarks and evidence upload
- Manager dashboard showing compliance percentage and overdue count

## UiPath Layer

UiPath handles repetitive workflow automation:

- Import task schedules from Excel or email attachments
- Generate recurring task instances based on frequency
- Send reminders before due dates
- Escalate overdue items to supervisors
- Create weekly compliance reports
- Rename and archive uploaded evidence files

## Fluid AI Layer

Fluid AI acts as the conversational copilot:

- Answers questions about due and overdue work
- Summarizes compliance status by category or owner
- Drafts reminder and escalation messages
- Identifies high-risk overdue tasks
- Converts manager questions into filtered views or reports

## Invariants

- A task must always have an owner, due date, status, and category.
- Completed tasks must have completion date and optional evidence.
- Overdue status should be calculated from due date and completion status.
- Automation should not delete original records.

## Failure Handling

- If an imported file has missing fields, route it to a correction queue.
- If an email reminder fails, log the failure and retry.
- If AI confidence is low, show source records instead of making unsupported claims.

