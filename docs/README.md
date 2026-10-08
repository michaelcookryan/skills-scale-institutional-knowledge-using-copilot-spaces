# OctoAcme Project Management Documentation

Welcome to the central hub for OctoAcme's project management processes. Use these guides to navigate cross-functional projects from initiation through delivery and continuous improvement.

## Overview

OctoAcme uses a structured, iterative approach that aligns teams around measurable outcomes, clear responsibilities, and transparent communication. Five core principles guide the work:

- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments.
- **Clear ownership:** Each project has a named Project Manager and Product Lead.
- **Data-informed decisions:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback and learning.

## Process documentation

### Getting started

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to the approach, core roles, lifecycle, key artifacts, and communication cadence.
- [Roles & Personas](./octoacme-roles-and-personas.md) — Responsibilities, goals, and communication practices for Developers, Product Managers, and Project Managers.

### Project lifecycle

- [Project Initiation](./octoacme-project-initiation.md) — Validate the business need, align stakeholders, prepare a Project One-pager, and decide whether to proceed to planning.
- [Project Planning](./octoacme-project-planning.md) — Turn an approved initiative into a prioritized, estimated backlog with acceptance criteria, a Definition of Done, dependencies, and release milestones.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Coordinate daily delivery, track work on the project board, review and test changes, report progress, and escalate blockers.
- [Release & Deployment](./octoacme-release-and-deployment.md) — Check release readiness, deploy and verify changes, communicate releases, and handle rollback or incidents.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture lessons after sprints, releases, milestones, or incidents and track improvements with owners and due dates.

### Throughout the lifecycle

- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Maintain the Risk Register, manage dependencies, share status and incident updates, and follow escalation paths.

## Process management summary

OctoAcme's lifecycle moves through Initiation, Planning, Execution, Release, and Close & Retrospective. Initiation validates the business need and aligns stakeholders through a lightweight Project One-pager covering the problem, objectives, success metrics, timeline, risks, and resource needs. Teams move into planning when metrics are clear, stakeholders agree on priority, and team availability is confirmed. Planning translates the approved initiative into shippable increments: a prioritized, estimated backlog with acceptance criteria, named owners, dependencies, a Definition of Done, and release milestones.

Clear roles support delivery: Project Managers (PMs) coordinate schedules, risks, dependencies, and communications; Product Managers (PdMs) define outcomes, prioritize the backlog, and measure success. Developers design, implement, test, document, and review changes, while QA/Testing validates quality and acceptance criteria. Stakeholders provide input and approvals, with Product Leads and sponsors involved in alignment and escalation. Teams track work on a project board such as GitHub Projects, using Backlog, Ready, In Progress, In Review, QA, and Done, and demonstrate progress at sprint or milestone reviews.

Communication combines weekly PM–PdM alignment, delivery syncs, and monthly stakeholder updates, with weekly or milestone-based status reporting tailored to stakeholder needs. Teams agree on their standup cadence: the overview suggests twice-weekly standups or an agreed schedule, while the execution guide recommends daily 15-minute standups. Status updates cover progress, next steps, risks and blockers, and decisions needed. Risk management continues throughout planning and execution through a Risk Register recording impact, likelihood, ownership, mitigation, and status, reviewed at weekly syncs. Escalations move from the team to the PM, Product Lead, and sponsor; security incidents follow the security incident runbook and notify Security on-call.

Quality assurance combines small pull requests (400 lines or fewer when possible), peer approval, automated tests and linting, and security scanning in CI. Teams use unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and manual QA when needed. Releases require met acceptance criteria, passing CI and security scans, release notes, and a documented rollback or mitigation plan; deployment includes staging smoke tests, backups or snapshots when applicable, production verification, and stakeholder announcements. Retrospectives after sprints, releases, milestones, and incidents capture learning and prioritize a few actionable improvements, tracked in the backlog or issues with owners, due dates, and measurable success criteria.

## Getting started

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then consult [Roles & Personas](./octoacme-roles-and-personas.md) to understand responsibilities.
- **Starting a new project?** Follow [Project Initiation](./octoacme-project-initiation.md), then use [Project Planning](./octoacme-project-planning.md) to prepare the work for delivery.
- **Looking for specific guidance?** Use the links above to open the relevant lifecycle or supporting-process guide; the overview explains how the documents fit together.
- **Suggesting improvements?** Use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes.

## Document structure

Process documents use clear headings to explain their purpose and applicable scope, followed by the relevant activities, workflows, artifacts, templates, or checklists. The exact sections vary by process so each guide can provide practical, process-specific instructions while keeping guidance easy to scan and apply.
