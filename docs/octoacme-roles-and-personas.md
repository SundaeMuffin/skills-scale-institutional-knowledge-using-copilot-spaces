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

## Release Manager

### Role Summary
Release Managers own the end-to-end release process, from coordinating deployment logistics and approval gates to managing rollback plans. They act as the critical bridge between development completion and production delivery, ensuring releases are predictable, low-risk, and well-communicated.

### Responsibilities
- Coordinate release planning, scheduling, and deployment logistics with PM and Developers
- Own release communications, versioning, and go/no-go decisions
- Manage rollback plans and incident response protocols for releases
- Maintain the release calendar and track dependencies across teams
- Ensure release readiness criteria are met before deployment

### Goals
- Deliver stable, on-schedule releases with minimal disruption to end users
- Reduce release risk through consistent processes and clear rollback plans
- Maintain clear audit trails for all release events and approvals

### Typical Communication
- Release readiness reviews prior to each deployment
- Release notes and deployment summaries distributed to stakeholders
- Coordination with QA Lead for final sign-off and with PM for timing decisions
- Post-release retrospective notes on incidents or delays

### Interactions with Existing Roles
- Works closely with **Project Managers** to align release dates with project milestones and stakeholder expectations.
- Collaborates with **Developers** to validate deployment steps, environment configuration, and rollback procedures.
- Coordinates with the **QA Lead** to confirm quality gates and acceptance criteria are satisfied before release.
- Keeps **Product Managers** and **Stakeholders/Reviewers** informed of release status and any scope changes.

---

## QA Lead

### Role Summary
QA Leads define and own the quality strategy for a project. They ensure that software meets acceptance criteria and quality standards before it reaches end users, coordinating both manual and automated test efforts across the delivery team.

### Responsibilities
- Define and maintain the test strategy, quality gates, and definition of done
- Design and execute test plans covering functional, regression, and edge-case scenarios
- Coordinate manual and automated testing efforts across the team
- Triage defects, prioritize bug fixes with PM and Developers, and track resolution
- Review acceptance criteria with Product Managers to ensure testability

### Goals
- Prevent defects from reaching production through proactive quality processes
- Improve test coverage and reduce regression risk over time
- Create shared quality standards the entire team can work toward

### Typical Communication
- Test plans and quality gate reports shared with PM and Release Manager before each release
- Bug triage sessions with Developers and PM during execution sprints
- Retrospective contributions on defect trends and process improvements
- Daily standups participation during active testing phases

### Interactions with Existing Roles
- Partners with **Developers** on testability, test automation, and rapid defect resolution.
- Aligns with **Product Managers** to validate that acceptance criteria are clear, complete, and testable.
- Provides final quality sign-off to the **Release Manager** before deployments proceed.
- Escalates high-risk defects to **Project Managers** for visibility in risk registers and stakeholder updates.

---

## Support Engineer

### Role Summary
Support Engineers are the team's connection to real-world usage after a release. They triage post-release issues, manage customer-facing communications during incidents, and synthesize patterns from user feedback into actionable insights for the backlog.

### Responsibilities
- Triage, investigate, and resolve post-release issues and customer-reported bugs
- Coordinate with Developers and PM on hotfix prioritization and incident response
- Communicate status updates to affected users and internal stakeholders during incidents
- Document recurring issues, workarounds, and resolution steps in a knowledge base
- Surface patterns from support requests to inform backlog prioritization and product improvements

### Goals
- Minimize customer impact from post-release issues through rapid triage and resolution
- Reduce repeat incidents by closing the loop between support findings and engineering improvements
- Build a knowledge base that accelerates resolution of recurring problems

### Typical Communication
- Incident reports and post-mortems shared with PM, Release Manager, and Developers
- Regular summaries of support trends communicated to Product Managers for backlog input
- Customer-facing status updates during active incidents
- Participation in retrospectives to contribute real-world feedback on released features

### Interactions with Existing Roles
- Collaborates with **Developers** to investigate root causes and deliver hotfixes for critical issues.
- Works with **Project Managers** to escalate incidents that require resource prioritization or stakeholder notification.
- Feeds user-observed patterns to **Product Managers** to inform roadmap and backlog decisions.
- Coordinates with the **Release Manager** on emergency release processes for critical hotfixes.

---

## UX Designer

### Role Summary
UX Designers advocate for the end user throughout the project lifecycle. They translate user needs and business goals into clear, accessible designs, ensuring that what gets built is intuitive, consistent, and meets usability standards before and after development.

### Responsibilities
- Conduct user research, usability testing, and translate findings into design requirements
- Create wireframes, prototypes, and design specifications for features
- Define and maintain design standards, accessibility guidelines, and component patterns
- Collaborate on acceptance criteria to ensure usability is a measurable outcome
- Review implemented features for design fidelity and flag deviations before release

### Goals
- Deliver experiences that are intuitive, accessible, and aligned with user needs
- Reduce rework by ensuring design intent is clearly communicated before development begins
- Advocate for accessibility and inclusive design as a baseline, not an afterthought

### Typical Communication
- Design reviews and prototype walkthroughs with Developers and Product Managers
- Usability test results shared with PM and PdM to inform prioritization
- Design specs and annotation updates kept in sync with the backlog
- Retrospective input on design-development handoff friction and usability outcomes

### Interactions with Existing Roles
- Partners closely with **Product Managers** to align design decisions with product vision, user research, and success metrics.
- Works with **Developers** to clarify design intent, review implementations, and identify feasible solutions early.
- Contributes usability acceptance criteria alongside **QA Leads** to ensure design quality is verifiable.
- Keeps **Stakeholders/Reviewers** informed of design direction at key gates to capture early feedback.

---

## Stakeholder/Reviewer

### Role Summary
Stakeholders and Reviewers are business or technical advisors who provide input, review deliverables at key gates, and ensure the project remains aligned with organizational goals. Their involvement drives accountability and surfaces strategic concerns before they become delivery risks.

### Responsibilities
- Review and approve project outputs at defined checkpoints (e.g., charter sign-off, release go/no-go)
- Provide domain expertise, business context, and strategic direction to the team
- Raise concerns, dependencies, or constraints that may affect scope, timeline, or quality
- Participate in retrospectives to share observations on team effectiveness and outcomes
- Represent the interests of the broader organization or a specific business function

### Goals
- Ensure projects deliver outcomes that align with business strategy and stakeholder needs
- Surface risks and misalignments early to avoid costly late-stage rework
- Foster a productive feedback loop between the delivery team and the wider organization

### Typical Communication
- Checkpoint reviews and go/no-go decision meetings at major project milestones
- Monthly or per-milestone briefings from Project and Product Managers
- Ad-hoc feedback provided via documented review comments or decision logs
- Retrospective participation to share strategic observations and validate outcomes

### Interactions with Existing Roles
- Engages with **Project Managers** through status updates, escalations, and milestone approvals.
- Provides direction and feedback to **Product Managers** on roadmap priorities and business alignment.
- May review designs or prototypes produced by **UX Designers** at key decision gates.
- Participates in release go/no-go decisions alongside the **Release Manager** and **Project Manager**.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

