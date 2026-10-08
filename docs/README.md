# OctoAcme Project Management Documentation

This directory is the central guide to OctoAcme's project management processes, from proposing and planning work through release and continuous improvement.

## Overview

OctoAcme uses a structured, iterative approach to deliver customer value with clear ownership, transparent communication, and decisions informed by evidence. The process is guided by five principles:

- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments.
- **Clear ownership:** Name accountable roles and make responsibilities explicit.
- **Data-informed decisions:** Measure outcomes and adapt based on evidence.
- **Psychological safety:** Encourage candid feedback, learning, and improvement.

## Process management summary

OctoAcme's project lifecycle has five phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Initiation validates the need and aligns stakeholders around a one-pager with goals, success measures, and initial risks. Planning turns approved work into a prioritized and estimated backlog, with acceptance criteria, dependencies, milestones, and a Definition of Done. The team then executes in iterative increments, releases against agreed criteria, and closes by capturing learnings and next steps.

During execution, teams use a project board such as GitHub Projects to track work through Backlog, Ready, In Progress, In Review, QA, and Done. Daily standups surface progress and blockers; weekly delivery syncs review delivery and risks; sprint or milestone demos provide review points. Small pull requests, automated tests and linting in CI, peer review, and at least one approval help maintain quality. Unit, integration, and end-to-end smoke tests, security scanning, and manual acceptance QA are used as appropriate.

The Project Manager (PM) coordinates delivery, schedules, risks, and communications; the Product Manager (PdM) defines outcomes, prioritizes the backlog, and measures success. Developers build and test features and participate in design and code review; QA validates quality and acceptance criteria. Stakeholders provide input and approvals. Communication includes a weekly PM–PdM sync, regular delivery standups and syncs, monthly stakeholder updates, and timely escalation when needed, using shared project records and status updates to keep decisions visible.

Risk management continues throughout the lifecycle: teams maintain a Risk Register with owners and mitigations, review it weekly, and escalate issues from the team through the PM and Product Lead to the Sponsor as needed. Releases follow a checklist that covers readiness, staging smoke tests, backups where applicable, production verification, stakeholder announcements, and rollback plans. After a sprint, release, milestone, or incident, a retrospective captures what went well and what to improve; a small set of owned action items is tracked and reviewed to support continuous improvement.

## Process documentation

### Getting started

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, principles, roles, lifecycle, and key artifacts.

### Project lifecycle

- [Project Initiation](./octoacme-project-initiation.md) — Validate and authorize new work, align stakeholders, and prepare the project one-pager.
- [Project Planning](./octoacme-project-planning.md) — Shape approved work into a prioritized backlog, delivery plan, and Definition of Done.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Coordinate day-to-day delivery, team rhythm, quality practices, reporting, and blockers.
- [Release & Deployment](./octoacme-release-and-deployment.md) — Prepare, deploy, verify, and—if needed—roll back a release.

### Supporting processes and reference

- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Maintain the Risk Register, communicate status, and follow escalation paths.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Run retrospectives and track improvement actions.
- [Roles & Personas](./octoacme-roles-and-personas.md) — Reference responsibilities, goals, and communication patterns for common project roles.

## Getting started

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then consult [Roles & Personas](./octoacme-roles-and-personas.md) to understand responsibilities.
- **Starting a new project?** Follow [Project Initiation](./octoacme-project-initiation.md), then use [Project Planning](./octoacme-project-planning.md) to prepare the work for delivery.
- **Looking for specific guidance?** Use the links above to open the relevant lifecycle or supporting-process guide; the overview explains how the documents fit together.

## Document structure

Process documents use clear headings to explain their purpose and applicable scope, followed by the relevant activities, workflows, artifacts, templates, or checklists. The exact sections vary by process so each guide can provide practical, process-specific instructions while keeping guidance easy to scan and apply.
