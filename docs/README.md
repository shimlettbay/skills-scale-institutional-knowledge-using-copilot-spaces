# OctoAcme Project Management Docs

This folder contains the core project management guidance for OctoAcme. These documents provide a shared understanding of how the team validates new work, plans delivery, executes across functions, releases features safely, and continuously improves how work gets done.

## Project management processes summary

OctoAcme starts each initiative by validating the business need, measurable outcomes, stakeholders, and initial risks. The team captures the problem statement, success metrics, a high-level timeline, resource needs, and early dependencies in a project one-pager before moving forward. Once stakeholders align and the decision gate is reached, the initiative enters planning: the team prioritizes backlog items, defines acceptance criteria and a Definition of Done, estimates work, identifies dependencies and risks, and prepares a milestone plan.

During execution, work is tracked on a project board using clear stages such as Backlog, Ready, In Progress, In Review, QA, and Done. The Project Manager coordinates delivery, timelines, risks, and updates; the Product Manager owns the product outcome and backlog priorities; developers build and test; QA validates quality and acceptance; and stakeholders provide input and approvals. Teams use regular standups, weekly PM and product syncs, and milestone reviews to surface blockers, manage dependencies, and keep decisions visible.

Quality is built into each phase of the lifecycle. New logic should include unit and integration testing where appropriate, smoke tests should validate critical user flows, and CI should run automated checks including tests, linting, and security scanning before merges and releases. Release readiness requires acceptance criteria to be met, release notes and rollback plans to be prepared, and smoke testing to be completed in staging before production deployment. After sprints, releases, milestones, or incidents, the team runs retrospectives to capture what worked, what needs improvement, and which actions should be carried into the backlog.

## Document index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to use these docs

Use the overview and lifecycle documents to understand the standard OctoAcme process, then move into the more detailed guides for planning, execution, risk management, and release practices. This set is designed to give new contributors a practical framework for delivering work with clear ownership, measurable outcomes, and consistent communication.
