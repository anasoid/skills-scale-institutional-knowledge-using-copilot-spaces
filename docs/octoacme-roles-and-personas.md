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

## UX/Design Lead

### Role Summary
UX/Design Leads shape the user experience, validate assumptions with users, and ensure product decisions stay focused on usability, accessibility, and customer value.

### Responsibilities
- Lead user research, design exploration, and accessibility reviews
- Translate product goals into user flows, wireframes, and interaction decisions
- Partner with Product Managers on problem framing and acceptance criteria
- Collaborate with Developers and QA/Testing to validate that the delivered experience matches design intent

### Goals
- Deliver intuitive, inclusive, and usable experiences
- Reduce rework caused by unclear requirements or design gaps
- Align product decisions with user needs and business outcomes

### Typical Communication
- Discovery and design review sessions
- Product and engineering feedback loops
- UX validation and usability updates

### Interaction with Existing Roles
- Works closely with Product Managers to define user problems and success criteria
- Provides design direction and prototypes for Developers to implement
- Helps QA/Testing verify that the experience meets accessibility and usability expectations
- Keeps Project Managers informed on design risks, dependencies, and timeline impacts

---

## Technical Lead / Architect

### Role Summary
Technical Leads or Architects guide the technical direction, reduce architectural risk, and ensure the solution remains maintainable, scalable, and aligned with long-term goals.

### Responsibilities
- Define technical standards, patterns, and non-functional requirements
- Review architecture, dependencies, integration points, and technical trade-offs
- Partner with Developers on implementation quality and delivery feasibility
- Advise the Project Manager on risks, sequencing, and cross-team dependencies

### Goals
- Maintain a resilient and scalable technical foundation
- Reduce delivery risk through sound design decisions
- Support clear trade-offs between speed, quality, and maintainability

### Typical Communication
- Architecture reviews
- Dependency and risk planning discussions
- Technical design documents and implementation guidance

### Interaction with Existing Roles
- Works with Product Managers to align technical trade-offs with product priorities
- Provides technical leadership and decision support to Developers during implementation
- Coordinates with Project Managers on delivery sequencing, dependencies, and risks
- Supports QA/Testing by clarifying technical assumptions and quality expectations

---

## QA/Test Lead

### Role Summary
QA/Test Leads ensure quality is built into delivery and that accepted outcomes match stakeholder expectations and business needs.

### Responsibilities
- Define test strategy, test coverage, and release readiness criteria
- Coordinate test planning, execution, and defect triage
- Partner with Developers on testability and defect resolution
- Work with Product Managers and Stakeholders on acceptance validation

### Goals
- Catch defects early and reduce release risk
- Improve confidence in quality and reliability
- Align testing to business and user outcomes

### Typical Communication
- Test plans and quality reviews
- Defect triage and release readiness updates
- Acceptance validation with stakeholders

### Interaction with Existing Roles
- Collaborates with Developers to ensure features are testable and bugs are resolved quickly
- Shares quality risks and readiness status with Project Managers and Product Managers
- Helps validate whether implementation meets acceptance criteria for Stakeholders
- Provides risk-based feedback on release confidence and deployment readiness

---

## Security/Privacy Lead

### Role Summary
Security/Privacy Leads protect the organization and users by identifying risks, defining controls, and ensuring compliance requirements are considered early in the lifecycle.

### Responsibilities
- Identify security and privacy requirements and risk areas
- Review technical designs for compliance, data protection, and threat exposure
- Support mitigation planning and security review checkpoints
- Coordinate with Developers, QA/Testing, and the Project Manager on pre-release controls

### Goals
- Reduce risk of security and privacy incidents
- Ensure compliance requirements are integrated into delivery
- Improve trust and operational resilience

### Typical Communication
- Security and privacy review sessions
- Risk assessments and mitigation tracking
- Release readiness and escalation discussions

### Interaction with Existing Roles
- Advises Product Managers and Developers on requirements, constraints, and risk trade-offs
- Reviews implementation decisions with Technical Leads or Architects to reduce exposures
- Works with Project Managers to build security and compliance into milestone planning
- Partners with QA/Testing to validate controls and release readiness prior to deployment

---

## Data/Analytics Lead

### Role Summary
Data/Analytics Leads ensure teams can measure progress, validate outcomes, and use evidence to improve decisions across the project lifecycle.

### Responsibilities
- Define success metrics, instrumentation, and data collection needs
- Validate data quality and reporting readiness
- Partner with Product Managers to interpret outcomes and business impact
- Work with Developers and QA/Testing to ensure tracking is implemented and validated

### Goals
- Improve visibility into product and operational performance
- Ensure decisions are informed by evidence
- Support continuous improvement and measurable accountability

### Typical Communication
- Metric definition and review cycles
- Reporting dashboards and milestone updates
- Outcome-focused planning and retrospectives

### Interaction with Existing Roles
- Helps Product Managers define measurable outcomes and align them to business goals
- Works with Developers to confirm instrumentation and event tracking are in place
- Provides QA/Testing with reporting inputs and validation criteria for release confidence
- Shares insights with Project Managers to support status reporting and prioritization decisions

---

## Operations/SRE or Release Lead

### Role Summary
Operations/SRE or Release Leads help ensure systems remain reliable, deployment-ready, and recoverable when changes are released to users.

### Responsibilities
- Coordinate deployment windows, rollback readiness, and release timing
- Monitor service health and operational readiness
- Partner with Developers and QA/Testing on smoke tests and release criteria
- Communicate release status, risks, and incident escalations to the Project Manager and stakeholders

### Goals
- Reduce operational risk during and after release
- Improve reliability and recovery readiness
- Support smooth delivery with clear ownership and escalation

### Typical Communication
- Release plans and readiness checklists
- Monitoring and incident coordination
- Production verification and stakeholder updates

### Interaction with Existing Roles
- Works with Developers to ensure production readiness and rollback planning are in place
- Coordinates with Project Managers on release windows, dependencies, and communication timing
- Provides QA/Testing with deployment validation criteria and support for smoke tests
- Keeps Product Managers and Stakeholders informed on operational impact and any issues affecting launch confidence

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- On smaller teams, multiple personas may be combined, but accountability should remain explicit and visible in project planning, execution, and reporting.
- These roles are meant to clarify ownership without replacing the core responsibilities of Developers, Product Managers, and Project Managers.


