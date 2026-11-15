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

## Executive Sponsor

### Role Summary
The Executive Sponsor is the senior leader accountable for the project's business outcome. They fund and champion the project and are the final escalation point.

### Responsibilities
- Approve the Project One-pager and the go/no-go decision at the initiation gate
- Resolve Level 3 (business-impacting) escalations
- Remove organizational blockers and secure resources

### Goals
- Ensure the project delivers measurable business value
- Keep the project aligned with company strategy and priorities

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Ad-hoc escalation meetings

### Interactions with Other Roles
- Receives monthly stakeholder updates from the Project Manager
- Partners with the Product Lead on priority and scope trade-offs
- Final escalation point in Team → PM → Product Lead → Sponsor

---

## Product Lead

### Role Summary
The Product Lead is the senior product owner for an initiative. Product Managers report to the Product Lead and own day-to-day backlog and feature decisions. On smaller projects, one person may fill both roles.

### Responsibilities
- Review the Project One-pager and confirm success metrics
- Handle Level 2 escalations and cross-team priority conflicts
- Set product direction and outcome priorities for the initiative

### Goals
- Keep product outcomes aligned with the business strategy
- Resolve priority conflicts quickly

### Typical Communication
- Weekly alignment with the Project Manager
- Roadmap reviews with Product Managers and the Sponsor

### Interactions with Other Roles
- Guides Product Managers on roadmap and outcome priorities
- Receives escalations from the Project Manager and escalates to the Sponsor when needed

---

## QA / Test Engineer

### Role Summary
The QA / Test Engineer owns the quality strategy. They check that work meets its acceptance criteria and the Definition of Done.

### Responsibilities
- Draft the initial test plan / QA approach during planning
- Maintain integration and end-to-end smoke tests for critical flows
- Run manual QA for feature acceptance and own the "QA" column on the project board
- Give quality sign-off before a release and run post-deploy verification

### Goals
- Catch defects before they reach production
- Keep automated test coverage reliable and fast

### Typical Communication
- Daily standups and sprint planning
- Test plans, bug reports, and release sign-off notes

### Interactions with Other Roles
- Works with Developers on testability and automated tests in CI
- Confirms acceptance criteria with Product Managers
- Reports quality risks to the Project Manager for the Risk Register
- Gives quality sign-off to the Release Manager before production deploys

---

## Tech Lead / Engineering Lead

### Role Summary
The Tech Lead is the senior engineer accountable for technical direction, architecture, and engineering standards.

### Responsibilities
- Lead technical design and estimation, and identify technical risks and dependencies
- Define branching, PR, and CI conventions (PR size, review and approval policy)
- Mentor Developers and decide technical trade-offs

### Goals
- Maintain a sound, scalable architecture
- Keep engineering practices consistent across the team

### Typical Communication
- Technical design docs and code reviews
- Weekly alignment with Product and Project Managers

### Interactions with Other Roles
- Reviews Developer PRs and unblocks technical issues
- Advises the Product Manager and Project Manager on feasibility, estimates, and risks
- Works with the Release Manager on deployment readiness and rollback decisions

---

## Release Manager / DevOps Engineer

### Role Summary
The Release Manager coordinates releases and owns the deployment pipeline and the health of each environment.

### Responsibilities
- Schedule deployment windows and confirm that pre-release requirements are met
- Run staging and production deployments through the automated pipeline
- Own the rollback plan, carry out rollbacks, and coordinate on-call during incidents
- Publish release notes

### Goals
- Make releases safe, repeatable, and fast to recover from
- Keep deployment pipelines reliable and observable

### Typical Communication
- Release schedules, release notes, and deployment announcements
- Incident updates during deployment issues

### Interactions with Other Roles
- Gets quality sign-off from QA before production deploys
- Notifies the Project Manager, Support, and stakeholders about releases and incidents
- Engages Security on-call as described in the security incident runbook

---

## Security Champion

### Role Summary
The Security Champion is a security advocate embedded in the team who keeps delivery aligned with security standards.

### Responsibilities
- Triage findings from CI security scans and advise on secure design
- Act as the team's first contact under the security incident runbook

### Goals
- Prevent security vulnerabilities from reaching production
- Build security awareness across the team

### Typical Communication
- Security review comments on PRs and design docs
- Security risk updates in weekly syncs

### Interactions with Other Roles
- Works with Developers and the Tech Lead on security fixes
- Adds security risks to the Risk Register with the Project Manager
- Coordinates with Security on-call and the Release Manager during security incidents

---

## Customer Support / Success Liaison

### Role Summary
The Customer Support / Success Liaison represents customers and support teams in delivery and release communications.

### Responsibilities
- Prepare support teams for releases and known issues
- Feed customer feedback and incident trends back into the backlog

### Goals
- Reduce how much releases disrupt customers
- Bring real customer needs into product decisions

### Typical Communication
- Release readiness briefings for support teams
- Customer feedback summaries

### Interactions with Other Roles
- Receives release announcements from the Release Manager and Project Manager
- Shares customer insights with Product Managers

---

## UX / Product Designer (optional)

### Role Summary
The UX / Product Designer makes sure solutions are usable and customer-centered, in line with OctoAcme's customer-first principle.

### Responsibilities
- Conduct user research and usability testing
- Deliver designs before sprint planning

### Goals
- Deliver intuitive, accessible experiences

### Typical Communication
- Design reviews, prototypes, and usability findings

### Interactions with Other Roles
- Works with Product Managers on defining the problem
- Works with Developers and QA on implementation and acceptance

---

## Stakeholders

### Role Summary
Stakeholders are the groups affected by or contributing to the project, such as engineering, sales, and support.

### Responsibilities
- Provide inputs and approvals
- Attend demos and reviews

### Goals
- Stay informed and make sure the project meets their group's needs

### Typical Communication
- Regular status updates (weekly or milestone-based) and demos

### Interactions with Other Roles
- Receive updates from the Project Manager through the single source of truth (project README or release doc)
- Give feedback to Product Managers and the Product Lead

---

## Decision Ownership (RACI Summary)

| Decision / Activity | Responsible | Accountable | Consulted | Informed |
|---|---|---|---|---|
| Initiation go/no-go | Project Manager | Sponsor | Product Lead, Tech Lead | Stakeholders |
| Backlog prioritization | Product Manager | Product Lead | Tech Lead, Project Manager | Team |
| Release approval | Release Manager | Project Manager | QA, Tech Lead | Support, Stakeholders |
| Rollback decision | Release Manager | Tech Lead | QA, Security Champion | Project Manager, Support |
| Escalations | Project Manager | Product Lead / Sponsor | Team | Stakeholders |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

