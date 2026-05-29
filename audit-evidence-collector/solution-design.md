# Solution Design

## Workflow

1. Audit checklist is loaded into Power Apps.
2. Teams upload or link evidence.
3. UiPath scans configured folders and emails for matching files.
4. Files are renamed and organized by audit clause.
5. Fluid AI summarizes missing evidence and readiness.
6. UiPath generates final audit packet.

## Controls

- Never overwrite original evidence files.
- Keep source file link and upload date.
- Require owner for every missing evidence item.

