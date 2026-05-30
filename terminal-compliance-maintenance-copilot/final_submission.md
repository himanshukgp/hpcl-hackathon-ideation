# HPCL Hackathon Submission: Terminal Compliance & Maintenance Deadline Copilot

## Use case title
Terminal Compliance & Maintenance Deadline Copilot

## Problem statement
HPCL terminals manage hundreds of periodic operational, maintenance, safety, and statutory compliance tasks. Currently, these are often scattered across Excel sheets, physical registers, and email threads, leading to several critical pain points:
- **Safety & Compliance Risk:** Missing a task (like fire equipment testing or tank inspection) creates significant safety exposure and audit gaps.
- **Manual Overhead:** Supervisors spend excessive time manually tracking deadlines and following up with various teams.
- **Visibility Gaps:** Management lacks a real-time, consolidated view of terminal readiness and upcoming deadlines.
- **Evidence Management:** Retrieving physical or digital evidence (certificates, photos, reports) for audits is often slow and difficult.

## Approach
Our solution implements a seamless automation and AI layer using the following platforms and data:

**Platforms:**
- **Microsoft Power Apps:** Serves as the operational front-end for task tracking, mobile-based completion entry, and evidence (photo/document) upload.
- **UiPath RPA:** Automates the background workflow—generating recurring tasks, sending automated reminders to owners, escalating overdue items to managers, and archiving evidence files.
- **Fluid AI:** Acts as a conversational "Compliance Copilot" that allows managers to ask natural language questions (e.g., "What is our compliance status for fire safety this week?") and get instant summaries.

**Data:**
- Task master schedules (frequency, owners, statutory requirements).
- Completion records with timestamps and remarks.
- Digital evidence (photographs, calibration certificates, inspection reports).

## Expected business impact
- **Zero Missed Deadlines:** Automated reminders and escalations ensure 100% compliance with statutory and safety requirements.
- **Enhanced Safety Culture:** Real-time visibility of maintenance status directly reduces operational risks.
- **Increased Productivity:** Automating follow-ups and reporting saves significant man-hours for supervisors and managers.
- **Audit Readiness:** A centralized, digital repository of evidence makes internal and external audits faster and more transparent.
- **Data-Driven Decisions:** Fluid AI provides instant insights into compliance trends, helping managers allocate resources more effectively.
