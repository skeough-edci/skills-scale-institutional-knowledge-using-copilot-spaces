# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises, including delivery, quality, release, security, and stakeholder roles.

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

### Interactions with Existing Roles
- **Developers**: Collaborate with peers through reviews and pairing.
- **Product Managers**: Clarify requirements and acceptance criteria.
- **Project Managers**: Share estimates, status, and risks.
- **Other roles**: Work with QA, DevOps, Security, and UX on quality, delivery, and design.

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

### Interactions with Existing Roles
- **Developers**: Review technical trade-offs with engineers.
- **Product Managers**: Collaborate with fellow Product Managers on roadmap alignment.
- **Project Managers**: Align scope and priorities with delivery plans.
- **Other roles**: Report to the Product Lead; work with UX, QA, and Support on design, acceptance, and feedback.

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

### Interactions with Existing Roles
- **Developers**: Track developer status, risks, and blockers.
- **Product Managers**: Align schedules with product priorities.
- **Project Managers**: Coordinate with other Project Managers on dependencies.
- **Other roles**: Escalate to the Product Lead (Level 2) and Sponsors (Level 3); coordinate with QA, Release Manager, and Security.

---

## QA / Test Engineer

### Role Summary
QA / Test Engineers validate quality and acceptance criteria. They own test plans, smoke tests, and QA sign-off.

### Responsibilities
- Create and maintain test plans and smoke tests
- Validate work against acceptance criteria
- Report and verify defects
- Provide QA sign-off for releases

### Goals
- Catch defects before release
- Make acceptance criteria testable and verifiable

### Typical Communication
- Defect reports and test status updates
- QA sign-off in release readiness reviews

### Interactions with Existing Roles
- **Developers**: Reports defects, advises on testability, and verifies fixes.
- **Product Managers**: Clarifies and validates acceptance criteria.
- **Project Managers**: Reports test status and release readiness.
- **Other roles**: Works with Release Manager on sign-off and Support on customer-reported issues.

---

## Product Lead

### Role Summary
The Product Lead is the named owner in the overview and the Level 2 escalation point. They approve one-pagers at the initiation decision gate.

### Responsibilities
- Approve one-pagers at the initiation decision gate
- Resolve priority conflicts
- Serve as escalation point above the Project Manager (Level 2)
- Align product direction with Sponsors

### Goals
- Keep priorities clear and conflicts resolved quickly
- Ensure work aligns with business strategy

### Typical Communication
- Decision gate reviews
- Escalation discussions and priority decisions
- Updates to Sponsors

### Interactions with Existing Roles
- **Developers**: Sets priorities that shape developer work.
- **Product Managers**: Guides and aligns Product Managers on priorities and roadmap.
- **Project Managers**: Receives Level 1 escalations from Project Managers and resolves them.
- **Other roles**: Escalates business-impacting issues to Sponsors (Level 3).

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide funding, strategic direction, and final escalation (Level 3) for business-impacting issues.

### Responsibilities
- Provide funding and strategic direction
- Approve go/no-go decisions
- Act as final escalation for business-impacting issues (Level 3)
- Review monthly stakeholder updates

### Goals
- Ensure investment delivers business value
- Make timely go/no-go decisions

### Typical Communication
- Monthly stakeholder updates
- Go/no-go decision meetings
- Escalation briefings

### Interactions with Existing Roles
- **Developers**: Rarely interacts directly; engages via the Product Lead and PM.
- **Product Managers**: Receives roadmap and outcome information mainly through the Product Lead.
- **Project Managers**: Receives monthly updates and escalations from the PM.
- **Other roles**: Interacts mainly with the Product Lead.

---

## Release Manager

### Role Summary
Release Managers coordinate release readiness, deployment windows, release notes, rollback plans, and post-deploy verification.

### Responsibilities
- Coordinate release readiness and deployment windows
- Prepare and publish release notes
- Maintain rollback plans
- Ensure post-deploy verification is completed

### Goals
- Deliver predictable, low-risk releases
- Enable fast recovery when releases fail

### Typical Communication
- Release readiness checklists
- Release notes and announcements
- Deployment window coordination

### Interactions with Existing Roles
- **Developers**: Coordinates deployment timing and fixes needed for release.
- **Product Managers**: Confirms release scope and communicates what is shipping.
- **Project Managers**: Shares release status and readiness with the PM.
- **Other roles**: Works with QA on sign-off, DevOps on deployments, and on-call/Support on announcements and post-deploy issues.

---

## DevOps / Platform Engineer

### Role Summary
DevOps / Platform Engineers maintain CI/CD pipelines, security scanning, environments, and observability.

### Responsibilities
- Maintain CI/CD pipelines
- Maintain security scanning in pipelines
- Manage environments
- Provide observability and monitoring

### Goals
- Fast, reliable, automated delivery
- Visible system health

### Typical Communication
- Pipeline and environment status updates
- Incident and outage coordination

### Interactions with Existing Roles
- **Developers**: Supports Developers with pipelines, environments, and tooling.
- **Product Managers**: Informs Product Managers of platform constraints as needed.
- **Project Managers**: Reports platform risks and outages to the PM.
- **Other roles**: Supports the Release Manager on deployments and the Security Champion on scanning.

---

## Security Champion / Security On-call

### Role Summary
Security Champions review security scans, advise on risks, and lead the security incident runbook.

### Responsibilities
- Review security scan results
- Advise on security risks and mitigations
- Lead the security incident runbook
- Promote secure development practices

### Goals
- Reduce security risk
- Respond quickly and effectively to security incidents

### Typical Communication
- Security findings and advisories
- Incident channels and post-incident reviews

### Interactions with Existing Roles
- **Developers**: Advises on remediation of findings and secure design.
- **Product Managers**: Informs Product Managers of security risks affecting scope.
- **Project Managers**: Works with the PM during incidents on status and communications.
- **Other roles**: Works with DevOps on scanning and environment hardening.

---

## Support / Customer Success

### Role Summary
Support / Customer Success is the voice of the customer after release.

### Responsibilities
- Receive release announcements and prepare customers
- Report customer issues
- Feed customer feedback to Product Managers and QA

### Goals
- Resolve customer issues quickly
- Surface customer needs to product teams

### Typical Communication
- Release announcements
- Customer issue reports and feedback summaries

### Interactions with Existing Roles
- **Developers**: Escalates customer-reported defects through the agreed channels.
- **Product Managers**: Provides customer feedback to inform priorities.
- **Project Managers**: Flags customer-impacting issues to the PM.
- **Other roles**: Feeds QA with reproducible issues; coordinates with the Release Manager on announcements.

---

## UX / Design

### Role Summary
UX / Design provides designs and usability validation and informs acceptance criteria.

### Responsibilities
- Provide designs and prototypes
- Validate usability
- Inform acceptance criteria

### Goals
- Deliver usable, consistent experiences
- Reduce rework through early validation

### Typical Communication
- Design reviews and handoffs
- Usability findings

### Interactions with Existing Roles
- **Developers**: Hands off designs and answers implementation questions.
- **Product Managers**: Collaborates on user needs and acceptance criteria.
- **Project Managers**: Shares design timelines and dependencies.
- **Other roles**: Works with QA on validating designed behavior.

---

## Scrum Master / Delivery Facilitator (optional)

### Role Summary
Scrum Masters / Delivery Facilitators facilitate team ceremonies and remove blockers. This role is optional.

### Responsibilities
- Facilitate standups, sprint planning, and retrospectives
- Remove blockers
- Promote team process improvement

### Goals
- Keep the delivery team unblocked and flowing
- Improve team practices continuously

### Typical Communication
- Standups, sprint planning, and retrospectives
- Blocker tracking

### Interactions with Existing Roles
- **Developers**: Helps the delivery team stay unblocked and focused.
- **Product Managers**: Helps Product Managers prepare backlog for planning.
- **Project Managers**: Works with the PM to share progress and escalate blockers.
- **Other roles**: Supports the whole delivery team.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

