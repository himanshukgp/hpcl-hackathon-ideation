# Solution Design

## Components

- Permit request form in Power Apps
- Permit approval dashboard for supervisors and safety officers
- UiPath workflow for approval routing, reminders, and permit PDF creation
- Fluid AI assistant for checklist validation and safety guidance

## Workflow

1. User submits permit request in Power Apps.
2. Fluid AI checks for missing or inconsistent fields.
3. UiPath routes approval to required authorities.
4. Approved permit is generated as a PDF.
5. Work completion and closure evidence are uploaded.
6. Closed permit is archived for audit.

## Failure Modes

- Missing safety checklist: block submission.
- Approval delay: send reminder and escalation.
- Expired permit: mark inactive automatically.

