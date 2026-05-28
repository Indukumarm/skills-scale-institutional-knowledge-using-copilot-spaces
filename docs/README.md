# OctoAcme Project Management Docs

Welcome! This directory provides all core process documentation for managing projects with the OctoAcme approach.

## Project Management Process Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The process is organized into five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**.

### Initiation
During initiation, teams validate business need and create a **Project One-pager** that documents the problem statement, success metrics, stakeholders, and initial timeline. This serves as the decision gate for whether to proceed with formal planning.

### Planning
Once approved, the planning phase breaks work into shippable increments, establishes a prioritized backlog with acceptance criteria, estimates scope, and maps dependencies and milestones. This structured foundation ensures teams have clear direction before development begins.

### Execution & Tracking
Execution is managed through a consistent team rhythm and GitHub Projects-based workflow. Daily standups (15 minutes) and weekly delivery syncs keep the team aligned on progress, blockers, and dependencies. Work is organized in columns: Backlog, Ready, In Progress, In Review, QA, and Done. Pull request workflows are disciplined—small PRs (≤400 lines when possible) with clear issue links and acceptance criteria, automated CI testing and linting, and at least one required approval before merging.

Quality assurance is built into the process with:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests before release
- Security scanning in CI pipelines
- Manual QA for feature acceptance when needed

Teams track velocity, burndown, and success metrics through dashboards, with a three-level blocker escalation path (team triage → PM/Product Lead → Sponsor) to unblock impediments quickly.

### Release & Deployment
Release and deployment are standardized with pre-release requirements (passing CI, security scans, drafted release notes, and rollback plans), a deployment checklist, post-deploy verification, and incident playbooks for rapid rollback if needed.

### Retrospective & Continuous Improvement
Each project concludes with a retrospective (45–75 minutes) to capture learnings and convert them into 2–3 prioritized action items, fostering a culture of continuous improvement and psychological safety.

## Core Roles & Responsibilities

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Quick Links to Detailed Docs

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and artifacts
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day execution and track progress toward milestones
- [Risks & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize how to release features to production
- [Retrospectives & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities for team members

---

**Getting Started:** New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction, then navigate to the specific process documents relevant to your current project phase.
