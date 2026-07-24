# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a **structured project management approach** focused on customer value, iterative delivery, clear ownership, and data-informed decisions. This documentation hub provides comprehensive guidance for running projects from initiation through closure.

OctoAcme's methodology emphasizes:
- **Phased delivery** across five key lifecycle stages (Initiation, Planning, Execution, Release, and Close & Retrospective)
- **Multi-disciplinary collaboration** with clearly defined roles: Project Managers, Product Managers, Developers, and QA teams
- **Transparent communication** through regular standups, syncs, and stakeholder updates using standardized templates
- **Quality assurance practices** combining automated CI/CD checks, small pull requests, and comprehensive testing before production deployment
- **Continuous improvement** through retrospectives that capture learnings and drive actionable improvements each cycle

This approach reduces risk, accelerates delivery, and maintains psychological safety across cross-functional teams.

## Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to enable rapid feedback
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## Documentation Index

### Getting Started

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, core roles, key artifacts, and project lifecycle
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of Developers, Product Managers, Project Managers, and their responsibilities

### Project Phases

- **[Project Initiation](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, and authorize work with a lightweight Project One-pager
- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies, risks, and create a prioritized backlog with acceptance criteria
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm (standups and syncs), quality standards, and blocker escalation
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardized release process, pre-flight checklists, deployment procedures, and rollback playbooks
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, run effective retros, and convert insights into actionable improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk identification and monitoring, escalation paths, and stakeholder communication templates

## Key Artifacts

Throughout the project lifecycle, maintain these artifacts:

- **Project Charter / One-pager** — Problem statement, goals, success metrics, timeline, stakeholders, and risks
- **Prioritized Backlog** — Work items with acceptance criteria, estimates, and owners
- **Risk Register** — Tracked risks with impact, likelihood, mitigation, and status
- **Definition of Done** — Team-agreed quality and completeness standards
- **Release Notes & Deployment Checklist** — Pre-release verification and deployment steps
- **Retrospective Notes & Action Items** — Learnings and improvements with owners and timelines

## How to Use These Docs

1. **Start with the Overview** — Read the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level understanding of OctoAcme's principles and lifecycle
2. **Review your role** — Check [Roles & Personas](./octoacme-roles-and-personas.md) to understand responsibilities for your position
3. **Navigate by phase** — Follow the appropriate phase guide (Initiation → Planning → Execution → Release → Retrospective) as your project progresses
4. **Use checklists and templates** — Each document includes practical checklists and templates; adapt them to your team's needs
5. **Keep artifacts updated** — Maintain project charters, risk registers, and status updates in your project repository (ideally in `docs/` or `.copilot/` folders)
6. **Escalate risks early** — Use the three-level escalation path outlined in [Risk Management & Communication](./octoacme-risks-and-communication.md) to flag issues proactively

## Communication Cadence

- **Daily standups** (15 min) — Progress, blockers, dependencies
- **Twice-weekly delivery team syncs** — Sprint planning, backlog refinement, technical alignment
- **Weekly PM/PdM sync** — Risk review, status, decisions needed
- **Monthly stakeholder updates** — High-level progress, milestones, and announcements
- **Ad-hoc escalations** — Immediate notification for critical risks or decisions

## Quick Reference: Definition of Done

Before closing any work item, ensure:
- [ ] Acceptance criteria are met and verified
- [ ] Code is reviewed and approved
- [ ] Tests are written and passing (unit, integration, smoke)
- [ ] Security scanning has run and passed
- [ ] Documentation is updated
- [ ] Related team members are notified

---

**For questions or suggestions on improving these processes**, open an issue with the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.