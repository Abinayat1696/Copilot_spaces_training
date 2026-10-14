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

## Delivery Leads

### Role Summary
Delivery Leads coordinate day-to-day execution across teams and keep the project moving toward milestones. They focus on operational clarity, cross-team alignment, and removal of execution blockers.

### Responsibilities
- Maintain sprint or iteration plans and delivery cadence
- Remove blockers that slow teams down or create handoff friction
- Track dependencies, risks, and decision points across disciplines
- Coordinate with engineering, QA, and project leadership on scope and sequencing
- Support status reporting and milestone readiness reviews

### How they interact with existing roles
- Works with Product Managers on priority trade-offs and sequencing
- Aligns with Project Managers on schedules, risks, and stakeholder updates
- Coordinates Developers and QA on scope, readiness, and acceptance flow
- Escalates unresolved cross-team issues to the Project Manager or sponsor when needed

### Typical Communication
- Delivery standups and cross-functional planning
- Dependency tracking and milestone check-ins
- Escalation summaries for leadership and stakeholders

---

## Release Engineers

### Role Summary
Release Engineers own the systems and practices that safely deliver software to production. They focus on release automation, deployment readiness, and rollback confidence.

### Responsibilities
- Manage CI/CD pipelines, deployment automation, and release approvals
- Prepare release checklists and deployment windows
- Coordinate rollback planning and incident response for release issues
- Maintain deployment documentation and release notes
- Validate production readiness with QA and engineering teams

### How they interact with existing roles
- Works with Developers to ensure release readiness and deployment safety
- Partners with QA on smoke tests, validation criteria, and production sign-off
- Coordinates with Project Managers on release timing and stakeholder communications
- Collaborates with Site Reliability Engineers on operational readiness and rollback decisions

### Typical Communication
- Release readiness reviews
- Deployment and rollback update threads
- Post-release verification summaries

---

## Site Reliability Engineers (SREs)

### Role Summary
Site Reliability Engineers protect production health and reliability. They design for operational resilience and help teams maintain stable service performance throughout the lifecycle.

### Responsibilities
- Define and monitor reliability goals, alerting, and service health metrics
- Support incident response, recovery procedures, and post-incident reviews
- Help teams design systems that are observable, resilient, and operable
- Maintain runbooks, capacity planning safeguards, and service ownership practices

### How they interact with existing roles
- Partners with Developers to improve service reliability and operability
- Advises Project Managers and Product Managers on technical trade-offs involving uptime, latency, and incident risk
- Works with QA and Release Engineers to validate production readiness and deployment safety
- Helps drive root-cause analysis after incidents and release issues

### Typical Communication
- Operational reviews and incident updates
- Reliability dashboard reviews and alert follow-ups
- Release and deployment readiness discussions

---

## UX Researchers / Designers

### Role Summary
UX Researchers and Designers ensure solutions are useful, accessible, and aligned with customer needs. They translate user feedback into product decisions and experience improvements.

### Responsibilities
- Conduct user research and validate assumptions with real customer feedback
- Define user flows, information architecture, and interaction patterns
- Translate user insights into design decisions and acceptance criteria
- Collaborate on accessibility, usability, and experience quality

### How they interact with existing roles
- Informs Product Managers on customer pain points and priority decisions
- Provides design artifacts and interaction guidance to Developers
- Works with QA to validate usability, accessibility, and acceptance standards
- Helps Project Managers understand user-impact risks and design-related dependencies

### Typical Communication
- Research synthesis and design review sessions
- Product and feature planning discussions
- Acceptance criteria refinement with engineering and QA

---

## Data Analysts / Data Product Owners

### Role Summary
Data Analysts and Data Product Owners track whether the project is delivering the intended outcome. They connect product decisions to measures, reporting, and evidence.

### Responsibilities
- Define and track success metrics and key product signals
- Instrument events, dashboards, and reporting for product decisions
- Assess feature impact using usage, retention, conversion, and adoption data
- Support product prioritization with evidence and trend analysis

### How they interact with existing roles
- Works with Product Managers to define measurable outcomes and benchmarks
- Provides developers and QA with data assumptions and validation criteria
- Helps Project Managers assess progress against milestones and risks
- Brings evidence into stakeholder updates and retrospective discussions

### Typical Communication
- Metric reviews and adoption analyses
- Product prioritization and roadmap check-ins
- Release-impact reporting and post-launch learning reviews

---

## Security Reviewers / Security Owners

### Role Summary
Security Reviewers and Security Owners ensure projects meet security, privacy, and compliance expectations. They help teams identify and reduce risk before rollout.

### Responsibilities
- Review system design, architecture, and data handling for potential risk
- Support threat modeling, secure coding practices, and compliance checks
- Validate security requirements before release and major changes
- Coordinate incident response and escalation for security-related issues

### How they interact with existing roles
- Reviews work with Developers throughout design and implementation
- Advises Project Managers and Product Managers on risk, timelines, and risk-reduction plans
- Collaborates with Release Engineers and SREs on secure deployment and incident readiness
- Supports QA with security validation and release gating where needed

### Typical Communication
- Security review meetings and design checkpoints
- Risk and mitigation discussions during planning and release review
- Incident escalation and remediation updates

---

## QA Leads

### Role Summary
QA Leads define and coordinate testing strategy so teams can release with confidence. They maintain the quality bar across unit, integration, and end-to-end validation.

### Responsibilities
- Define quality gates, test plans, and acceptance criteria alignment
- Coordinate test execution across unit, integration, and system-level validation
- Track defects, regressions, and release quality outcomes
- Support readiness decisions for handoff, launch, and post-release monitoring

### How they interact with existing roles
- Works with Developers to review testability, coverage, and defect ownership
- Collaborates with Release Engineers and SREs on smoke testing and deployment validation
- Provides progress and risk signals to Project Managers and Product Managers
- Helps Product Managers confirm that user-facing outcomes meet acceptance criteria

### Typical Communication
- QA readiness reviews and regression status updates
- Release validation summaries
- Defect triage and risk discussions with delivery leads

---

## Business Stakeholder Proxies

### Role Summary
Business Stakeholder Proxies represent key stakeholder interests when the primary stakeholders are unavailable or decisions need to be made quickly. They help maintain momentum and avoid delays in approvals or feedback loops.

### Responsibilities
- Provide domain context and decision-making input for product and delivery choices
- Support prioritization conversations and approval processes
- Coordinate stakeholder communication and escalation paths
- Help align technical decisions with business needs and constraints

### How they interact with existing roles
- Works with Product Managers to maintain business alignment and priority clarity
- Supports Project Managers with approval paths and stakeholder input
- Collaborates with Developers and QA on feature trade-offs and release confidence
- Bridges communication between delivery teams and leadership when decisions are needed quickly

### Typical Communication
- Stakeholder check-ins and priority reviews
- Approval and escalation discussions
- Milestone and release readiness updates

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These expanded roles help clarify accountability across delivery, quality, reliability, security, research, and stakeholder alignment.

