# OctoAcme Project Management Docs

This folder brings together OctoAcme's project management guidance, from validating an initiative through delivery, release, and continuous improvement. Use these documents as a shared reference for planning and executing cross-functional projects.

## Process overview

OctoAcme projects move through initiation, planning, execution, release, and retrospective. Initiation clarifies the business need, measurable outcomes, stakeholders, initial timeline, and risks; once the goals, priorities, and team availability are aligned, the work moves into planning. The team then shapes the approved initiative into prioritized, estimated backlog items with acceptance criteria, owners, milestones, a Definition of Done, and identified dependencies.

During execution, teams track work on a project board, deliver small increments through reviewed pull requests, and validate progress through testing and demos. The Project Manager coordinates delivery, schedules, risks, and communications; the Product Manager defines outcomes, prioritizes work, and measures impact; developers build and test, QA validates acceptance, and stakeholders provide input and approvals. Standups, weekly delivery and PM–Product Manager syncs, milestone demos, and regular stakeholder updates help surface progress, decisions, risks, and blockers. Risks are reviewed regularly, with blockers escalated from the team through the PM and Product Lead to the sponsor as needed.

Quality is integrated throughout delivery: new logic receives unit tests, integration tests are added where applicable, critical flows receive end-to-end smoke tests, and CI runs tests, linting, and security scans before review. Releases require acceptance criteria to be met, passing CI and security scans, release notes, smoke tests, and a rollback or mitigation plan; teams verify staging and production after deployment. Retrospectives after sprints, releases, milestones, or incidents turn lessons into a few prioritized improvement actions with owners and due dates.

## Documents

- [Project Management Overview](octoacme-project-management-overview.md) — principles, lifecycle, roles, artifacts, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — validate and authorize work, align stakeholders, and prepare the one-pager and initial plan.
- [Project Planning](octoacme-project-planning.md) — create the delivery backlog, estimates, Definition of Done, milestones, and risk and dependency plan.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — manage team rhythm, project-board workflow, pull requests, quality checks, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — maintain the risk register, communicate status, and follow escalation paths.
- [Release & Deployment](octoacme-release-and-deployment.md) — prepare releases, deploy and verify changes, and respond to deployment failures.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — capture learnings and track improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and communication patterns for developers, Product Managers, and Project Managers.
