# OctoAcme Project Management Processes

Welcome to the OctoAcme Project Management documentation. This folder contains comprehensive guides for running projects using the OctoAcme methodology.

## Overview

OctoAcme's project management approach is built on principles of **iterative delivery**, **clear ownership**, **data-informed decisions**, and **psychological safety**. We believe in delivering customer value through well-defined processes, transparent communication, and continuous improvement. Each project is stewarded by a core leadership team consisting of a Project Manager (PM) who coordinates delivery and risk, a Product Manager (PdM) who defines outcomes and measures success, developers who implement and validate quality, and QA/Testing specialists who ensure acceptance criteria are met.

## Project Lifecycle

OctoAcme projects follow a structured lifecycle from initiation through closure:

1. **Initiation** – Validate business need and align stakeholders
2. **Planning** – Create detailed delivery plan and backlog
3. **Execution** – Build, test, and iterate with regular demos
4. **Release** – Deploy to production with proper controls
5. **Retrospective** – Capture learnings and drive improvements

## Core Project Management Processes

### [Project Management Overview](./octoacme-project-management-overview.md)
A concise introduction to OctoAcme's approach, roles, key artifacts, and lifecycle. Start here to understand the foundational framework.

### [Project Initiation](./octoacme-project-initiation.md)
Define initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Use this guide when starting a new project or feature proposal.

### [Project Planning](./octoacme-project-planning.md)
Turn an approved initiative into an actionable plan and backlog for delivery. Learn how to break work into shippable increments with clear acceptance criteria.

### [Execution & Tracking](./octoacme-execution-and-tracking.md)
Guidance for managing day-to-day execution and tracking progress toward project milestones. Includes team rhythm, workflow standards, quality practices, and blocker escalation.

### [Risk Management & Communication](./octoacme-risks-and-communication.md)
How to identify, manage, and communicate risks and dependencies. Covers risk registers, lifecycle, stakeholder communication, and escalation paths.

### [Release & Deployment](./octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production to reduce risk and improve observability. Includes release types, checklists, and rollback procedures.

### [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements. Learn how to run effective retrospectives and track continuous improvements.

### [Roles & Personas](./octoacme-roles-and-personas.md)
Defines typical roles and responsibilities used in OctoAcme project work, including Developers, Product Managers, and Project Managers.

---

## Project Management Process Summary

### Communication & Coordination Cadence
OctoAcme emphasizes regular, structured communication to maintain alignment and transparency:

- **Daily Standups** (15 minutes) – Focus on progress, blockers, and dependencies
- **Weekly PM/PdM Sync** – Alignment between Project Manager and Product Manager
- **Twice-Weekly Team Standups** – Delivery team coordination (or as agreed)
- **Monthly Stakeholder Updates** – Status reports to sponsors and stakeholders
- **Ad-hoc Escalations** – Risk and blocker escalation as needed

### Central Workspace & Tools
- **GitHub Projects** – Organizes work through columns: Backlog, Ready, In Progress, In Review, QA, Done
- **Risk Register** – Maintained and updated weekly to track issues through three escalation levels:
  - Level 1: Team-level triage in daily standup
  - Level 2: PM escalates to Product Lead and dependent teams
  - Level 3: Sponsor-level escalation for business-impacting issues
- **Project Documentation** – Centralized in the project repository with key artifacts: Project One-pager, Roadmap, Release Plan, Backlog items with acceptance criteria

### Quality Assurance & Testing
Quality is embedded throughout execution via a multi-layered approach:

- **Unit Tests** – For all new logic
- **Integration Tests** – Where applicable to validate component interactions
- **End-to-End Smoke Tests** – For critical flows before release
- **Security Scanning** – Automated in CI pipelines
- **Pull Request Workflow** – Keep PRs small (≤400 lines when possible), require automated test and linting verification, and need at least one approval before merging
- **Metrics & Monitoring** – Track velocity and burndown, monitor success metrics from the Project One-pager, and maintain dashboards for key signals (errors, latency, usage)

### Release Management
Releases are standardized with clear requirements and verification steps:

- **Pre-Release Requirements** – All acceptance criteria met, passing CI/security scans, rollback plans documented, smoke tests prepared
- **Release Types** – Patch (hotfixes), Minor (incremental features), Major (significant functionality or breaking changes)
- **Post-Deployment** – Verification and stakeholder announcement
- **Incident Response** – Includes rollback procedures and blameless retrospectives

### Continuous Improvement
OctoAcme emphasizes learning and iterative process refinement:

- **Retrospectives** – Held after each sprint, release, or significant milestone
- **Action Items** – Prioritized with assigned owners and due dates
- **Impact Measurement** – Track and measure the impact of improvements over time
- **Learning Culture** – Systematic refinement of processes and team capabilities

---

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Project Initiation](./octoacme-project-initiation.md) guide
3. **Planning your delivery?** Review [Project Planning](./octoacme-project-planning.md)
4. **Managing execution?** Consult [Execution & Tracking](./octoacme-execution-and-tracking.md)
5. **Need to release?** See [Release & Deployment](./octoacme-release-and-deployment.md)

For questions about roles and responsibilities, refer to [Roles & Personas](./octoacme-roles-and-personas.md).
