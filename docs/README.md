# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub!

## Summary of Project Management Processes

OctoAcme follows a structured, customer-first lifecycle that moves projects through five distinct phases: Initiation, Planning, Execution, Release, and Close & Retrospective. During **Initiation**, teams validate business need and align stakeholders around a lightweight Project One-pager that captures the problem statement, success metrics, and resource requirements. Once approved by the Product Lead and sponsor, the project moves into **Planning**, where work is broken into prioritized, estimated backlog items with clear acceptance criteria and a Definition of Done. This ensures scope is well-understood before execution begins.

Execution and delivery are coordinated through a disciplined team rhythm and clear ownership model. The core roles—Project Manager (PM), Product Manager (PdM), Developers, QA/Testing, and Stakeholders—meet in daily standups (15 min), weekly delivery syncs, and sprint planning sessions to track progress via a GitHub Projects board. Pull requests are kept small (≤400 lines when possible), require at least one approval, and must pass automated tests and security scans before merging. This iterative approach reduces risk and accelerates feedback loops. Quality is embedded throughout: unit tests, integration tests, end-to-end smoke tests, and security scanning all occur in CI before code reaches production.

Risk and communication are treated as ongoing activities. A Risk Register captures identified issues with impact, likelihood, mitigation plans, and owners; risks are reviewed weekly and escalated as needed. Stakeholders receive regular status updates using a consistent template. Incidents trigger a blameless retrospective. Finally, after each sprint or milestone, teams conduct retrospectives to capture learnings and convert them into prioritized action items. This continuous improvement culture, grounded in data and psychological safety, ensures OctoAcme projects deliver value consistently while building institutional knowledge.

## Project Management Docs

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, principles, roles, and lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — Initial steps to validate, authorize, and align stakeholders around new work
- [Project Planning](./octoacme-project-planning.md) — Breaking work into shippable increments with clear dependencies and timelines
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, quality practices, and blocker escalation
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identifying, managing, and communicating risks and stakeholder updates
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized release practices, deployment checklists, and rollback procedures
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and converting them into actionable improvements
- [Roles and Personas](./octoacme-roles-and-personas.md) — Detailed descriptions of key roles: Project Managers, Product Managers, Developers, and QA/Testing

## Getting Started

Use this README as your starting point for all OctoAcme process documentation. Whether you're starting a new project, onboarding to a team, or looking to improve a specific process, you'll find the relevant guidance above.

For any updates, improvements, or questions about these processes, please open a pull request or issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.