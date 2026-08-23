# OctoAcme Project Management Documentation

## Overview

This folder contains the complete OctoAcme project management methodology—a lightweight, iterative approach to delivering customer value across cross-functional teams. Our processes emphasize clear ownership, data-informed decisions, psychological safety, and continuous improvement.

### Key Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## How OctoAcme Runs Projects: The Process Summary

OctoAcme follows a structured five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Retrospective**. The initiation phase begins with stakeholder validation and a lightweight Project One-pager that captures the business problem, success metrics, and initial timeline. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs and clear acceptance criteria. Throughout execution, teams maintain daily standups and a structured Kanban board with columns spanning from Backlog through Done. The process emphasizes iterative delivery of small, testable increments rather than big-bang releases, with regular demos and reviews at sprint or milestone endpoints. Each release undergoes rigorous pre-deployment checks including acceptance criteria validation, passing CI/security scans, and smoke testing before production deployment. This disciplined approach is supported by comprehensive risk management, escalation protocols, and retrospectives that convert learnings into actionable improvements.

OctoAcme defines three core delivery roles: **Project Managers** coordinate timelines, risks, and communications; **Product Managers** own the vision, prioritize the backlog, and measure outcomes; and **Developers** implement features, write tests, and collaborate on design. Each project has named champions in these roles to ensure clear ownership and accountability. Communication is structured around a predictable cadence: daily standups (15 minutes) focus on progress and blockers, weekly syncs between PM and Product Manager align priorities and escalate risks, twice-weekly standups keep the delivery team synchronized, and monthly stakeholder updates provide visibility. This rhythm ensures rapid problem-solving at the team level while giving leadership the information they need to make strategic decisions.

Quality is embedded throughout OctoAcme's execution cycle through a layered testing approach: unit tests validate individual logic, integration tests verify cross-component interactions, and end-to-end smoke tests confirm critical flows before release. All code changes go through a PR workflow with automated CI checks (linting, testing, security scanning) and require at least one team-level approval before merging. Risk management is formalized through a Risk Register that tracks identification, assessment, mitigation, and monitoring, with a clear escalation path from team-level triage → Product Lead → Sponsor for business-impacting issues. The organization also maintains structured incident playbooks that include rollback procedures, root cause analysis, and blameless retrospectives. This multi-layered approach to quality and risk mitigation reduces surprises, accelerates resolution when issues do arise, and builds organizational confidence in release velocity.

## Process Documents

### Getting Started
- [Project Management Overview](./octoacme-project-management-overview.md) — Quick introduction to roles, principles, and key artifacts
- [Roles and Personas](./octoacme-roles-and-personas.md) — Definitions of Developer, Product Manager, Project Manager, and other key roles

### Project Lifecycle
- [Project Initiation](./octoacme-project-initiation.md) — Validate business need, align stakeholders, decide go/no-go
- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments, manage dependencies
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Daily standups, quality standards, blocker escalation
- [Release & Deployment](./octoacme-release-and-deployment.md) — Standardized release procedures and rollback plans

### Cross-cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk registers, stakeholder updates, escalation paths
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements

## How to Use These Docs

1. **Start here** — Read this README for a high-level understanding of OctoAcme processes
2. **Learn the roles** — Review the Roles and Personas guide to understand who does what
3. **Follow the lifecycle** — Use the project lifecycle docs as you move through phases (Initiation → Planning → Execution → Release)
4. **Apply cross-cutting practices** — Use the risk management and retrospective docs throughout your project
5. **Keep it current** — Maintain the Project Charter in your project repo and update it as conditions change

## Contributing

To propose updates or new content to these process documents, file an issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template. This ensures proposed changes are reviewed for alignment with our methodology and benefit from stakeholder input.
