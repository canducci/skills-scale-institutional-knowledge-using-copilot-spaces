# OctoAcme Project Management Docs

Welcome to OctoAcme's project management documentation. This README provides an overview of our processes and serves as your starting point for navigating the detailed guides in this folder.

---

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The process spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase is supported by documented guidance and mandatory artifacts—such as Project One-pagers, Risk Registers, and Release Notes—that ensure consistency across projects. The organization prioritizes a customer-first mindset, data-informed decision-making, and psychological safety, creating an environment where feedback and continuous improvement are encouraged at every stage.

Roles and communication are central to OctoAcme's execution model. Three core leadership roles drive each project: the **Project Manager (PM)** coordinates schedules, risks, and communications; the **Product Manager (PdM)** defines outcomes and prioritizes the backlog; and **Developers** implement features while collaborating on design and testability. This clear ownership structure is reinforced by a consistent communication cadence—including daily standups, weekly PM-PdM syncs, and monthly stakeholder updates—ensuring alignment across engineering, product, and business stakeholders. Risk escalation follows a three-level path (team → PM → Product Lead → Sponsor), enabling rapid issue resolution without unnecessary delays.

Quality and execution practices ensure reliable, timely delivery. The team uses a project board workflow with defined columns (Backlog, Ready, In Progress, In Review, QA, Done) to maintain visibility. Pull requests are kept small (≤ 400 lines when possible) and require at least one approval, with all code passing automated tests and linting before review. Quality assurance encompasses unit tests, integration tests, end-to-end smoke tests, and security scanning in CI, supplemented by manual QA for feature acceptance. OctoAcme also maintains a Risk Register throughout execution, monitors velocity and burndown metrics, and conducts retrospectives after each sprint or release to capture learnings and drive continuous improvement.

Release and deployment follow a controlled, observable process designed to minimize production risk. Before releasing, the team verifies that all acceptance criteria are met, CI and security scans pass, release notes are drafted, and a rollback plan is documented. Deployments proceed through a standard checklist—staging validation, production deployment (preferably automated), post-deploy verification, and stakeholder announcement—with a documented incident and rollback playbook in place. This disciplined approach, combined with OctoAcme's emphasis on transparency and blameless retrospectives, enables the organization to iterate rapidly while maintaining confidence in production quality.

---

## Project Lifecycle at a Glance

| Phase | Key Activities | Primary Artifact(s) |
|---|---|---|
| **1. Initiation** | Validate business need, align stakeholders, decide go/no-go | Project One-pager, Stakeholder list |
| **2. Planning** | Break work into increments, estimate scope, create release plan | Prioritized backlog, Milestone map, Risk Register |
| **3. Execution** | Implement features, run standups, track progress, manage risks | Project board, PRs, Status updates |
| **4. Release** | Validate acceptance criteria, deploy, verify, announce | Release notes, Deployment checklist, Rollback plan |
| **5. Close & Retrospective** | Capture learnings, drive improvements, close out project | Retrospective notes, Action items |

---

## Key Roles

| Role | Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risk management, and stakeholder communications. Runs standups and weekly syncs. |
| **Product Manager (PdM)** | Defines desired outcomes, owns and prioritizes the backlog, and measures success against agreed metrics. |
| **Developers** | Implement features and fixes to meet acceptance criteria, write tests, participate in code reviews, and identify technical risks. |
| **QA / Testing** | Validates quality and acceptance criteria through unit, integration, end-to-end, and manual testing. |
| **Stakeholders** | Provide inputs, approve scope and priorities, and receive regular status updates throughout the project. |

For detailed persona descriptions, see [Roles and Personas](./octoacme-roles-and-personas.md).

---

## Quick Links

| Document | Description |
|---|---|
| [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's principles, roles, and key artifacts |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Steps to validate and authorize a new project, including the One-pager template |
| [Project Planning](./octoacme-project-planning.md) | How to build an actionable backlog, define DoD, and create a release plan |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day workflows, PR process, quality practices, and progress metrics |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk Register format, escalation paths, and stakeholder communication templates |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | How to run retrospectives and track improvement action items |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Detailed descriptions of each role and their responsibilities |

---

## Getting Started

### New team members
1. Read the [Project Management Overview](./octoacme-project-management-overview.md) to understand OctoAcme's principles and roles.
2. Review [Roles and Personas](./octoacme-roles-and-personas.md) to find your role and understand what's expected.
3. Browse the phase guides (Initiation → Planning → Execution → Release → Retrospective) to get familiar with the full lifecycle.
4. Ask your PM or PdM which phase the current project is in, and jump to that guide first.

### Project leads starting a new project
1. Start with the [Project Initiation Guide](./octoacme-project-initiation.md) to create a Project One-pager and stakeholder list.
2. Move to [Project Planning](./octoacme-project-planning.md) to run the kickoff, build the backlog, and set milestones.
3. Use [Risk Management & Communication](./octoacme-risks-and-communication.md) to establish a Risk Register and communication cadence from day one.
4. Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) during delivery to keep the team aligned and maintain quality standards.
5. Follow the [Release & Deployment Guide](./octoacme-release-and-deployment.md) when preparing to ship.
6. Close out with a [Retrospective](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings for the next cycle.

### Using these docs with Copilot Spaces
These documents are indexed in OctoAcme's Copilot Space, allowing you to ask questions about processes, templates, and best practices directly in your editor. For example:
- *"What does the Project One-pager template look like?"*
- *"What are the pre-release requirements before deploying to production?"*
- *"Who is responsible for managing the Risk Register?"*

Copilot will use the content in this `docs/` folder to provide accurate, context-aware answers grounded in OctoAcme's own processes.
