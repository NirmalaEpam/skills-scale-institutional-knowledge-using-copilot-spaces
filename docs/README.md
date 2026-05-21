# OctoAcme Project Management Docs

This `docs/` folder centralizes how OctoAcme manages cross-functional delivery from idea through release and continuous improvement. It is intended as a shared knowledge base for onboarding, day-to-day execution, and consistent project governance.

OctoAcme uses a lightweight but structured lifecycle that starts with project initiation and moves through planning, execution, release, and retrospective learning. During initiation, teams validate the business problem, align stakeholders, define measurable outcomes, and capture foundational artifacts such as a project one-pager, initial risks, communication plan, and high-level milestones. Planning then turns the approved initiative into shippable increments with prioritized backlog items, clear acceptance criteria, estimates, dependencies, and an agreed Definition of Done.

Delivery is supported by clearly defined personas and shared ownership. Project Managers coordinate schedules, risks, dependencies, and communication. Product Managers define problem statements, prioritize the roadmap and backlog, and track outcomes against success metrics. Developers design and implement features, collaborate on quality and testability, and surface technical risks. QA/testing contributors validate acceptance criteria and overall quality, while stakeholders provide direction and approvals at key decision points.

Communication and escalation are treated as core operating practices. Teams run regular standups, weekly delivery and PM/Product syncs, sprint or milestone demos, and recurring stakeholder updates. Progress, risks, and decisions are maintained in a single source of truth (for example, project README and release documents), and blockers follow a clear escalation path from team triage to PM/Product Lead and sponsor-level escalation when business impact is high.

Quality assurance and release readiness are embedded throughout execution. Teams favor small PRs linked to issues and acceptance criteria, require CI checks (including tests, linting, and security scanning) before merge, and verify quality with unit, integration, and end-to-end smoke tests as applicable. Before release, OctoAcme expects all acceptance criteria to be met, release notes and rollback plans to be prepared, and post-deploy verification to be completed. Retrospectives after sprints, releases, and incidents convert lessons learned into tracked improvement actions.

## Documents in this folder

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)
- [OctoAcme — Project Planning](./octoacme-project-planning.md)
- [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)
- [OctoAcme — Risk Management & Communication](./octoacme-risks-and-communication.md)
- [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](./octoacme-roles-and-personas.md)
