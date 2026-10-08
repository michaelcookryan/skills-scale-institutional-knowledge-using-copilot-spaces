# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA/Test Engineer

### Role Summary
QA and Test Engineers design, implement, and execute testing strategies to ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Design comprehensive test plans aligned with acceptance criteria
- Execute manual and automated testing across platforms
- Identify, document, and track defects
- Collaborate with Developers on test automation and edge cases
- Validate that Definition of Done is met
- Coordinate with DevOps/Release Engineers on test environment provisioning

### Goals
- Ensure high-quality releases with minimal defects
- Enable fast feedback loops on quality status
- Reduce defect escape rate to production

### Typical Communication
- Sprint planning and daily standups
- Test plan reviews and acceptance criteria walkthroughs with Product Managers
- Defect reports and quality metrics dashboards for Developers and Project Managers
- Release readiness sign-off with Product Managers and DevOps/Release Engineers

### Interactions
QA/Test Engineers work with Product Managers to translate acceptance criteria into test plans, and with Developers to automate tests, investigate defects, and validate fixes. They coordinate test environments with DevOps/Release Engineers and share quality status and release readiness with Project Managers.

---

## Product Lead

### Role Summary
Product Leads provide strategic direction, make tie-breaker decisions on feature prioritization, and ensure alignment between product vision and execution.

### Responsibilities
- Define and communicate product vision and strategy
- Make final trade-off decisions when Product Managers and stakeholders disagree
- Approve major scope changes and feature decisions
- Serve as escalation point for cross-team dependency conflicts
- Review milestones and provide strategic guidance

### Goals
- Ensure product strategy is clear and consistently applied
- Maximize strategic value of project delivery
- Reduce time spent on unaligned decisions

### Typical Communication
- Weekly alignment with Product Managers and Project Managers
- Monthly stakeholder strategy reviews with Sponsors
- Escalation discussions and decision documentation

### Interactions
Product Leads guide Product Managers on strategy and resolve prioritization trade-offs, while working with Project Managers on scope, milestones, and cross-team dependencies. They align strategic choices with Sponsors and provide Developers with direction when major feature decisions affect delivery.

---

## DevOps/Release Engineer

### Role Summary
DevOps and Release Engineers automate, standardize, and enable safe, repeatable deployments to production.

### Responsibilities
- Design and maintain CI/CD pipelines
- Automate testing, building, and deployment processes
- Provision and manage test and production environments
- Document and practice rollback procedures
- Monitor deployment health and post-release metrics
- Partner with security on compliance and scanning

### Goals
- Enable frequent, low-risk deployments
- Reduce manual effort in release processes
- Maintain high system availability and reliability

### Typical Communication
- Sprint planning with Developers and Project Managers for infrastructure dependencies
- Release planning and deployment scheduling
- Incident response and post-mortems with Developers and Project Managers

### Interactions
DevOps/Release Engineers partner with Developers to maintain build and deployment pipelines, and with QA/Test Engineers to provision test environments and automate quality checks. They coordinate release schedules and readiness with Project Managers and Product Managers, and share deployment health and incidents with the delivery team.

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors represent business stakeholders, provide strategic context, and remove organizational blockers.

### Responsibilities
- Define business objectives and success metrics
- Approve major budget and resource decisions
- Escalate and remove organizational roadblocks
- Provide strategic guidance on competing priorities
- Review milestone progress and outcomes

### Goals
- Ensure the project delivers on business objectives
- Maximize ROI and strategic impact
- Maintain executive alignment and support

### Typical Communication
- Monthly milestone reviews and status updates with Project Managers
- Escalated risk discussions with Product Leads and Project Managers
- Strategic decision meetings with Product Leads and Product Managers

### Interactions
Sponsors provide business context and resource decisions to Product Leads and Product Managers, and receive milestone, risk, and outcome updates from Project Managers. They remove organizational blockers for the delivery team and align executive stakeholders on priority trade-offs.

---

## Scrum Master/Team Facilitator

### Role Summary
Scrum Masters and Team Facilitators facilitate ceremonies, remove process blockers, coach teams on continuous improvement, and maintain team health. This role is optional for teams using Agile.

### Responsibilities
- Facilitate ceremonies (standups, planning, retrospectives)
- Remove process blockers and impediments
- Coach the team on continuous improvement
- Maintain team health and psychological safety
- Track team velocity and capacity

### Goals
- Improve team velocity and predictability
- Reduce cycle time through process optimization
- Foster a culture of continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies with the delivery team
- Impediment removal discussions with Project Managers and relevant stakeholders
- Retrospective facilitation and follow-up with the team

### Interactions
Scrum Masters/Team Facilitators support Developers, Product Managers, and QA/Test Engineers through team ceremonies and impediment removal. They coordinate with Project Managers on delivery risks and capacity while keeping facilitation separate from the Project Manager's accountability for project schedules, risks, and status.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
