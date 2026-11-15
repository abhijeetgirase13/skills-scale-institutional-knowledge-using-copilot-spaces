# OctoAcme Project Management Docs

## Summary of Project Management Processes

OctoAcme runs cross-functional projects with a customer-first, iterative, data-informed approach and clear ownership: every project has a named Project Manager and Product Lead.

- **Initiation:** Validate the business need with a Project One-pager, identify stakeholders, set success metrics, and pass a go/no-go decision gate.
- **Planning:** Hold a kickoff, build a prioritized and estimated backlog with acceptance criteria, define the Definition of Done, and map releases, milestones, and dependencies.
- **Execution & Tracking:** Daily standups, weekly delivery syncs, and sprint demos; a project board (Backlog → Ready → In Progress → In Review → QA → Done); small, reviewed PRs with CI tests, linting, and security scans; track velocity, burndown, and success metrics; three-level blocker escalation.
- **Risk & Communication:** Maintain a Risk Register (impact, likelihood, owner, mitigation, status) reviewed weekly; regular stakeholder status updates from a single source of truth; clear escalation paths (Team → PM → Product Lead → Sponsor).
- **Release & Deployment:** Patch/minor/major releases with pre-release requirements, staging smoke tests, automated deployment, post-deploy verification, and a rollback/incident playbook.
- **Retrospective & Continuous Improvement:** Timeboxed retros after sprints, releases, and incidents, producing 2–3 owned action items tracked in the backlog.

### Roles

- **Project Manager:** Coordinates delivery, schedules, risks, dependencies, and communications.
- **Product Manager:** Defines outcomes and success metrics, and prioritizes the roadmap and backlog.
- **Developers:** Build features to meet acceptance criteria, write tests and docs, and review code.
- **QA/Testing:** Validates quality and acceptance criteria.
- **Stakeholders:** Provide inputs and approvals.

### Quality Assurance

Unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when needed. PRs require at least one approval before merging.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
