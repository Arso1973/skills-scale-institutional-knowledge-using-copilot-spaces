# OctoAcme Project Management Docs

This repository contains OctoAcme's project management process documentation. Use this README as an index and quick reference to understand how OctoAcme plans, executes, and delivers projects.

## Project Management Processes Overview

OctoAcme follows a structured project lifecycle rooted in customer-first principles, iterative delivery, clear ownership, data-informed decisions, and psychological safety. Here's how our processes work:

### Project Initiation & Planning Phase

OctoAcme begins every project with a validation phase to confirm business need and align stakeholders before committing resources. During initiation, cross-functional teams develop a lightweight **Project One-pager** that captures the problem statement, SMART goals, success metrics, identified stakeholders, and initial risk assessment. Once the business case is approved and stakeholder alignment is confirmed, the project moves into detailed planning. The planning phase breaks work into shippable increments with prioritized backlogs, clear acceptance criteria, Definition of Done standards, and comprehensive risk/dependency mapping. This gated approach ensures that only well-defined, resourced initiatives proceed to execution.

### Execution, Delivery & Quality Assurance

During execution, teams operate with a clear cadence of daily standups (15 min), weekly delivery syncs, and regular demos at sprint milestones. Work flows through a **project board** with standardized columns (Backlog → Ready → In Progress → In Review → QA → Done), and pull requests are kept small (≤400 lines) with automated CI/CD checks, linting, security scanning, and mandatory code review approval before merging. Quality is embedded throughout the process with unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and manual QA for feature acceptance. The team maintains a risk register with ongoing monitoring, escalation protocols (team-level → PM → Product Lead → Sponsor), and weekly updates on blockers and dependencies.

### Release, Communication & Continuous Improvement

OctoAcme standardizes release management with clear classification (patch, minor, major), pre-release requirements including passing CI/security scans and documented rollback plans, and staged deployment from staging to production with post-deploy verification. **Stakeholder communication** happens through weekly status templates, monthly updates, and ad-hoc incident notifications when needed. After each sprint, release, or milestone, teams conduct retrospectives to capture learnings and drive continuous improvement. Action items from retrospectives are tracked in the backlog with clear owners and timelines, reinforcing a culture of measurement and iterative enhancement.

### Roles, Accountability & Psychological Safety

OctoAcme defines clear roles and accountability:
- **Product Managers** own the vision and prioritization
- **Project Managers** coordinate delivery and manage risks/communications
- **Developers** implement features and maintain quality standards
- **QA/Testing** validates acceptance criteria and quality gates

Each project has named PM and Product Lead ownership, with stakeholders clearly identified and integrated into the communication cadence. The organization emphasizes psychological safety in feedback and learning, ensuring that all team members understand their responsibilities and feel empowered to contribute to project success.

---

## Documentation Index

Navigate to the detailed process documents below for comprehensive guidance on each phase of project delivery:

### Core Reference
- [**Project Management Overview**](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, principles, roles, and key artifacts

### Project Lifecycle
- [**Project Initiation**](octoacme-project-initiation.md) — Validate business need, align stakeholders, and create a Project One-pager
- [**Project Planning**](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog
- [**Execution and Tracking**](octoacme-execution-and-tracking.md) — Manage day-to-day execution, track progress, and maintain quality standards
- [**Release and Deployment**](octoacme-release-and-deployment.md) — Standardize release types, pre-release requirements, and deployment workflows

### Supporting Processes
- [**Risks and Communication**](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks; escalation paths and stakeholder updates
- [**Retrospective and Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements

### Team Reference
- [**Roles and Personas**](octoacme-roles-and-personas.md) — Detailed role definitions, responsibilities, and communication styles

---

## How to Use These Docs

- **New team members**: Start with [Project Management Overview](octoacme-project-management-overview.md) for context, then reference specific docs as needed.
- **Project Managers**: Use [Project Initiation](octoacme-project-initiation.md) → [Project Planning](octoacme-project-planning.md) → [Execution and Tracking](octoacme-execution-and-tracking.md) as your workflow.
- **Product Managers**: Focus on [Project Initiation](octoacme-project-initiation.md), [Project Planning](octoacme-project-planning.md), and [Risks and Communication](octoacme-risks-and-communication.md).
- **Developers**: Reference [Execution and Tracking](octoacme-execution-and-tracking.md) for standards, [Release and Deployment](octoacme-release-and-deployment.md) for release processes, and [Roles and Personas](octoacme-roles-and-personas.md) for responsibilities.

Keep the Project Charter updated in your project repo. Add process-specific docs into `.copilot/` or `.github/` if you want Copilot Spaces to use them as context.

---

## Contributing to Process Docs

Found a gap in our processes? Want to suggest an improvement? Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates. All improvements help us scale institutional knowledge and support team success.
