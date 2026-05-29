# Solution Design

## Components

- Power Apps shift entry form
- Shift dashboard with latest handover summary
- UiPath email or Teams distribution flow
- Fluid AI summary and action extraction assistant

## Workflow

1. Outgoing shift submits handover.
2. Fluid AI summarizes key points and extracts action items.
3. UiPath sends summary to incoming shift and supervisors.
4. Incoming shift acknowledges handover.
5. Pending actions remain visible until closed.

