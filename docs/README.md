# OctoAcme Project Management Docs

Welcome! This README provides a high-level overview of OctoAcme's project management processes and direct links to all related documentation in this folder.

## Project Management Processes Summary
OctoAcme's project management approach is lifecycle-driven and principle-led, moving work from Initiation to Planning, Execution, Release, and Retrospective. Ownership is explicit: a Project Manager coordinates delivery, risk, and communications; a Product Manager defines outcomes and prioritization; Developers implement with quality; QA validates acceptance and readiness; and stakeholders provide inputs and approvals. Key artifacts anchor each stage, including a Project One-pager/Charter, prioritized backlog with acceptance criteria and a clear Definition of Done, a release plan with milestones, a Risk Register, and retrospective notes that feed continuous improvement.

Workflows begin with Initiation to validate need, align stakeholders, and define success metrics and timelines, captured in the One-pager and an initial risk list. Planning turns intent into an executable path: kickoff with the team, build a prioritized and estimated backlog, define DoD, identify dependencies, and map a release plan. Execution is rhythm-based and visible: daily 15-minute standups focus on progress, blockers, and dependencies; weekly delivery syncs track milestones and risks; and each sprint culminates in a demo/review. Work flows across a project board (Backlog → Ready → In Progress → In Review → QA → Done), with escalation paths from team triage to PM/Product Lead to sponsor-level for high-impact issues.

Quality assurance is built into the engineering workflow. Small, reviewable pull requests link to issues and acceptance criteria; CI enforces automated tests and linting, with at least one approval required before merge per team policy. Testing layers include unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI, complemented by manual QA for feature acceptance when needed. Readiness to release requires passing CI/security, complete acceptance criteria, drafted release notes, a rollback plan, and prepared smoke tests. Deployment favors automated pipelines, staged rollouts, post-deploy verification, clear announcements, and a defined rollback/incident playbook.

Communication is structured and proactive. PM and PdM sync weekly; delivery teams hold frequent standups; stakeholders receive monthly (or milestone-based) updates, guided by reusable status and incident communication templates. A single source of truth (e.g., project README or release doc) consolidates status. Risks are continuously identified, assessed, mitigated, and monitored via a maintained Risk Register and reviewed in regular syncs. Retrospectives after sprints, releases, or incidents drive measurable improvements, with action items tracked in the backlog and revisited in PM syncs—reinforcing a culture of psychological safety, iterative delivery, and evidence-based decisions.

## Documentation Index
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
