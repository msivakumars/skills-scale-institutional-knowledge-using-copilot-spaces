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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed)

To reduce handoff ambiguity and improve cross-functional coordination, add the following personas. For each persona we recommend a short Responsibilities list and an Interactions section describing collaborators and typical handoffs.

### Release Manager

Responsibilities:
- Coordinate release windows and ownership of the release lifecycle
- Maintain and enforce the release checklist and rollback plan
- Verify that release notes, stakeholder communications, and post-release verifications are prepared
- Liaise with CI/CD, Platform, and On-call teams for deployment readiness

Interactions:
- Works with Project Manager (scheduling and risk assessment)
- Works with Developers and QA (validation and readiness)
- Works with SRE/Platform (deployment orchestration and rollbacks)
- Works with Product Marketing / Launch Coordinator (announcement timing and assets)

Why this helps:
- Centralizes release ownership and avoids ad-hoc, uncoordinated deployments.

---

### Technical Program Manager (TPM)

Responsibilities:
- Manage cross-team technical dependencies and milestones
- Facilitate architectural decision tracking and technical risk mitigation
- Drive program-level planning for long-running initiatives

Interactions:
- Works with PM and PdM to align priorities and timelines
- Works with Tech Leads and Engineers to unblock dependencies
- Communicates status and trade-offs to Stakeholders

Why this helps:
- Ensures multi-team technical work is coordinated and visible.

---

### SRE / Platform Liaison

Responsibilities:
- Advocate for operational reliability in feature design and delivery
- Define SLO/SLA expectations and required SLIs
- Own runbook requirements, incident handoffs, and post-deploy monitoring
- Coordinate production validation and tagging of critical releases

Interactions:
- Works with Developers on observability and instrumentation
- Works with Release Manager on deployment safety and rollback criteria
- Works with PM on incident impact communication and prioritization
- Works with QA for production-like testing and load testing scenarios

Why this helps:
- Improves system reliability and reduces time-to-detect/resolve incidents.

---

### UX Researcher / Design Liaison

Responsibilities:
- Plan and conduct user research and usability validation
- Synthesize qualitative insights and translate into acceptance criteria
- Provide design guidance aligned with accessibility and usability standards

Interactions:
- Works with PdM to define research goals and success criteria
- Works with Developers to clarify implementation intent and edge cases
- Works with PM to schedule research windows and incorporate findings into backlog

Why this helps:
- Reduces rework by validating assumptions earlier and improving user outcomes.

---

### Data Analyst / Insights Partner

Responsibilities:
- Define metrics, instrumentation needs, and success criteria for features
- Build dashboards and analyze experiment results
- Provide actionable insights for prioritization and retrospective learning

Interactions:
- Works with PdM to define success metrics and experiment scopes
- Works with Developers to ensure proper instrumentation and data quality
- Works with PM for regular reporting and post-release analysis
- Shares findings with Stakeholders

Why this helps:
- Ties work to measurable outcomes and avoids launching un-instrumented features.

---

### Compliance / Privacy Lead

Responsibilities:
- Identify regulatory and privacy requirements that affect features
- Review designs and changes for compliance risk and documentation
- Maintain approvals, checklists, and evidence for audits where required

Interactions:
- Works with PM to capture compliance items in the Risk Register
- Works with Developers to implement privacy-by-design controls
- Engages Legal and Security teams for approvals and escalations
- Works with Stakeholders for compliance-related decisions

Why this helps:
- Reduces release delays from late compliance discoveries and prevents regulatory exposure.

---

### Product Marketing / Launch Coordinator

Responsibilities:
- Coordinate go-to-market plans and prepare customer-facing materials
- Align support, sales, and enablement for launches
- Capture messaging, migration notes, and training requirements

Interactions:
- Works with PdM on messaging and target outcomes
- Works with Release Manager and PM to align timing and readiness
- Works with Stakeholders to approve launch communications

Why this helps:
- Ensures smooth customer-facing launches and readiness across teams.

---

## How to add these personas into our process docs
- Add an "Additional Personas" section (this section) to docs/octoacme-roles-and-personas.md.
- Add cross references and links from role descriptions to relevant checklists (release, metrics, compliance).
- For each persona, include Responsibilities, Interactions, and a short "When to engage" note.
