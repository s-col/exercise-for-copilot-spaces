# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This folder contains standardized guidance for running cross-functional projects from initiation through release and continuous improvement.

## Overview

OctoAcme uses a structured but flexible approach centered on customer value, iterative delivery, clear ownership, data-informed decisions, and psychological safety. The process combines lightweight planning artifacts, transparent communication, risk management, and quality checks so teams can deliver incrementally while maintaining alignment.

## Core Project Management Processes

OctoAcme follows five connected lifecycle phases:

1. **Initiation** — Validate the business need, define measurable success criteria, identify stakeholders, estimate resource needs, and make a go/no-go decision.
2. **Planning** — Turn an approved initiative into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, milestones, dependencies, and an initial test approach.
3. **Execution and tracking** — Deliver work in small increments using a project board, regular standups, weekly delivery syncs, demos, pull requests, and ongoing risk tracking. Blockers are escalated from the team to the Project Manager, Product Lead, and sponsor as needed.
4. **Release and deployment** — Confirm acceptance criteria, passing CI and security scans, release notes, smoke tests, and rollback or mitigation plans before deploying. Post-deployment verification and stakeholder announcements complete the release process.
5. **Retrospective and improvement** — After each sprint, release, milestone, or incident, capture what went well, what could improve, and a small number of owned action items. Review those actions in the weekly PM sync and measure their impact.

### Roles and Personas

- **Project Managers (PMs)** coordinate schedules, risks, dependencies, meetings, documentation, and stakeholder communication.
- **Product Managers (PdMs)** define outcomes, prioritize the backlog, validate solutions, and measure customer and business impact.
- **Developers** implement features, maintain tests and documentation, participate in reviews, and identify technical risks.
- **QA/Testing** validates quality and acceptance criteria, with manual QA used when needed.
- **Stakeholders** provide input, approvals, and business context.

### Communication and Quality Practices

Communication uses agreed cadences: team standups, weekly PM/PdM and delivery syncs, sprint or milestone demos, monthly stakeholder updates, and ad-hoc escalation for urgent issues. A single source of truth such as the project README or release document should contain status, while the risk register records impact, likelihood, owners, mitigations, and status. Quality is built into the workflow through unit tests, integration tests where applicable, end-to-end smoke tests for critical flows, linting, CI, security scanning, code review, and a required approval before merging. Teams also track velocity, burndown, success metrics, errors, latency, and usage to support data-informed decisions.

## Quick Links to Process Docs

- [Project Management Overview](./octoacme-project-management-overview.md) — Core principles, roles, artifacts, lifecycle, and communication cadence
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate an idea, align stakeholders, and approve work for planning
- [Project Planning](./octoacme-project-planning.md) — Define scope, backlog, estimates, dependencies, milestones, and the Definition of Done
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day workflows, quality standards, metrics, and blocker escalation
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk registers, stakeholder updates, incident communication, and escalation paths
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checks, and rollback procedures
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure, action tracking, and improvement practices
- [Personas & Roles](./octoacme-roles-and-personas.md) — Responsibilities, goals, and communication patterns for common roles

## Quick Navigation by Project Phase

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then review [Personas & Roles](./octoacme-roles-and-personas.md).
- **Starting a project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md), then move to [Project Planning](./octoacme-project-planning.md).
- **Planning delivery?** Use the [Project Planning](./octoacme-project-planning.md) guide and [Risk Management & Communication](./octoacme-risks-and-communication.md).
- **Executing work?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and keep the risk register current.
- **Preparing to ship?** Complete the [Release & Deployment Guide](./octoacme-release-and-deployment.md).
- **Wrapping up or learning from an incident?** Run a [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) session and track the resulting actions.

## Maintaining These Docs

Keep process improvements aligned with the existing guidance and record proposed updates through the repository's process-document issue template. Store project-specific artifacts in the project repository and add process-specific context to `.copilot/` when it should be available to Copilot Spaces.
