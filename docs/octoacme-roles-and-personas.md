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

## Scrum Master / Iteration Lead

### Role Summary
The Scrum Master / Iteration Lead facilitates agile ceremonies, removes impediments, and coaches the team on process. They protect team focus and champion continuous improvement across sprints.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Identify and remove blockers that impede team progress
- Shield the team from unplanned interruptions during a sprint
- Track and communicate team velocity and capacity
- Champion process improvements and adherence to agreed ways of working

### Goals
- Keep the team focused, unblocked, and delivering consistently
- Reduce ceremony overhead while preserving alignment
- Foster a culture of continuous improvement and psychological safety

### Typical Communication
- Daily standups and sprint ceremonies
- Blocker escalation to PM or Product Lead as needed
- Retrospective action items and follow-ups
- Sprint metrics and health reports

### Interaction Points
- Works closely with **Project Managers** to align on schedule, risks, and escalations
- Partners with **Product Managers** to ensure backlog readiness and sprint goal clarity
- Supports **Developers** by clearing technical and organizational impediments
- Coordinates with **QA Engineer / Test Lead** to ensure testing fits within sprint cadence

---

## Technical Lead / Architect

### Role Summary
The Technical Lead / Architect guides the technical direction of the project, ensures sound design decisions, and mentors the development team. They bridge product requirements and engineering implementation.

### Responsibilities
- Define and communicate technical architecture and design standards
- Review proposals and PRs for feasibility, scalability, and security
- Identify technical risks and propose mitigation strategies
- Mentor developers and provide guidance on complex implementations
- Collaborate with Product Managers to assess technical trade-offs

### Goals
- Deliver solutions that are maintainable, scalable, and secure
- Reduce technical debt and unplanned rework
- Ensure the team has the technical clarity needed to execute effectively

### Typical Communication
- Technical design documents and architecture decision records (ADRs)
- Code and PR reviews
- Technical risk items in the Risk Register
- Engineering syncs and design sessions

### Interaction Points
- Partners with **Developers** on design, implementation, and code quality
- Aligns with **Product Managers** on feasibility and scope trade-offs
- Informs **Project Managers** of technical risks and dependencies
- Coordinates with **QA Engineer / Test Lead** on testability and quality standards
- Consults with **Release Manager** on deployment architecture and rollback strategies

---

## QA Engineer / Test Lead

### Role Summary
The QA Engineer / Test Lead owns the quality validation strategy for the project. They verify that acceptance criteria are met, define the testing approach, and coordinate manual and automated testing activities.

### Responsibilities
- Define and maintain the test plan and testing strategy
- Write and execute test cases covering functional, regression, and edge-case scenarios
- Verify that acceptance criteria are met before features move to release
- Coordinate manual QA for feature acceptance and exploratory testing
- Identify and document defects, track them to resolution

### Goals
- Ensure that released features meet quality and acceptance standards
- Reduce defect escape rate to production
- Shift quality left by integrating testing early in the development cycle

### Typical Communication
- QA status updates in sprint reviews and standups
- Defect reports and test summary reports
- Test plan documentation in the project repo
- Coordination with developers during feature handoff

### Interaction Points
- Works with **Developers** to clarify acceptance criteria and verify fixes
- Aligns with **Product Managers** on acceptance criteria and edge cases
- Partners with **Scrum Master / Iteration Lead** to fit testing activities into sprint capacity
- Coordinates with **Release Manager** to verify smoke tests before production deployment
- Reports quality metrics to **Project Managers**

---

## Release Manager

### Role Summary
The Release Manager coordinates the planning and execution of production releases. They manage release windows, oversee deployment procedures, and ensure rollback plans are in place for every release.

### Responsibilities
- Schedule and communicate release windows with stakeholders and on-call teams
- Verify that all pre-release requirements are met before deployment proceeds
- Coordinate deployment execution across engineering and operations teams
- Manage the rollback process if a release causes a critical production issue
- Maintain release notes and post-release announcements

### Goals
- Deliver reliable, low-risk releases to production
- Minimize deployment downtime and customer impact
- Ensure every release has a tested rollback plan

### Typical Communication
- Release schedule and deployment window notifications
- Pre-release checklist status and go/no-go decisions
- Incident notifications and rollback decisions during releases
- Post-release summaries and announcements to stakeholders

### Interaction Points
- Coordinates with **Project Managers** on release timelines and milestone commitments
- Works with **QA Engineer / Test Lead** to verify smoke tests and release readiness
- Partners with **Developers** and **Technical Lead / Architect** on deployment procedures and rollback strategies
- Notifies **Sponsor / Executive Stakeholder** of release status and any production incidents
- Aligns with **Product Managers** on release notes and customer communication

---

## Sponsor / Executive Stakeholder

### Role Summary
The Sponsor / Executive Stakeholder provides business authorization, strategic direction, and executive-level support for the project. They approve scope changes, resolve high-level escalations, and ensure the project aligns with organizational priorities.

### Responsibilities
- Approve project initiation, scope changes, and major investment decisions
- Provide business context and strategic priorities to the delivery team
- Resolve escalations that cannot be addressed at the PM or Product Lead level
- Ensure appropriate resources (budget, headcount, tools) are available
- Review and sign off on project completion and key milestones

### Goals
- Ensure the project delivers measurable business value
- Minimize organizational risk from project decisions
- Maintain alignment between project outcomes and strategic objectives

### Typical Communication
- Monthly or milestone-based stakeholder updates from the PM
- Decision gate reviews at initiation and major phase transitions
- Escalation notifications for business-impacting risks or blockers
- Final approval communications for scope or timeline changes

### Interaction Points
- Receives status updates and escalations from **Project Managers**
- Aligns on product vision and priorities with **Product Managers**
- Serves as the final decision authority for go/no-go at project initiation and key milestones
- Engaged by **Release Manager** for major release communications and production incidents
- Referenced in the Escalation Path: Team-level → PM → Product Lead → Sponsor

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

