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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test automation, and acceptance validation. They collaborate with developers and product to ensure features meet quality standards and user expectations.

### Responsibilities
- Define testing strategy (unit, integration, end-to-end) for each initiative
- Build and maintain automated test suites
- Perform manual QA and acceptance testing against criteria
- Identify and triage defects; track quality metrics
- Participate in release readiness reviews
- Coach team on quality best practices

### Goals
- Catch defects early and reduce production incidents
- Enable developer confidence in automated testing
- Maintain high test coverage and observability

### Interactions
- With **Developers**: code review feedback on testability, test design collaboration
- With **Product Managers**: acceptance criteria refinement, edge case discovery
- With **Release Manager**: smoke test execution, rollback validation
- With **Project Manager**: quality metrics reporting, risk escalation

### Typical Communication
- Sprint planning and backlog refinement
- QA sign-off on acceptance criteria
- Quality dashboards and defect reports
- Post-release health checks

---

## Product Lead

### Role Summary
Product Leads serve as the single point of strategic product oversight, bridging product vision with delivery execution. They own roadmap alignment, stakeholder synchronization, and outcome validation.

### Responsibilities
- Own product vision and multi-quarter roadmap
- Align prioritization across projects and initiatives
- Ensure projects deliver measurable business outcomes
- Facilitate strategic decisions and trade-offs
- Validate product-market fit through user feedback and metrics
- Communicate status and learnings to executive sponsors

### Goals
- Maximize cumulative customer and business impact
- Reduce context-switching and conflicting priorities
- Enable data-driven, long-term product strategy

### Interactions
- With **Product Managers**: prioritization guidance, roadmap alignment, success metric definition
- With **Project Managers**: milestone and risk escalation, timeline alignment
- With **Tech Lead**: technical feasibility assessment, architecture implications
- With **Sponsors**: strategic alignment, business outcome tracking

### Typical Communication
- Monthly roadmap reviews
- Quarterly business reviews
- Escalation of strategic trade-offs and dependencies

---

## Tech Lead / Architect

### Role Summary
Tech Leads and Architects provide technical direction, design authority, and risk assessment. They mentor developers, guide architectural decisions, and ensure systems remain scalable and maintainable.

### Responsibilities
- Own technical design and architectural decisions
- Conduct design reviews and architecture assessments
- Identify technical risks and propose mitigations
- Mentor developers and foster engineering best practices
- Ensure code quality, performance, and security standards
- Participate in planning to assess feasibility and dependencies

### Goals
- Enable fast, reliable feature delivery
- Maintain system scalability and reliability
- Reduce technical debt and unplanned rework

### Interactions
- With **Developers**: design guidance, code review, mentorship
- With **QA Lead**: testability assessment, test automation architecture
- With **Project Manager**: technical risk reporting, dependency mapping
- With **Release Manager**: deployment strategy, rollback feasibility

### Typical Communication
- Technical design reviews (async and sync)
- Architecture decision records (ADRs)
- Technical spike investigations
- Risk register updates

---

## Release Manager

### Role Summary
Release Managers coordinate deployment schedules, ensure production readiness, and own incident response and rollback procedures. They minimize deployment risk and maintain system reliability.

### Responsibilities
- Plan and coordinate release schedules and deployment windows
- Verify pre-release readiness (tests, security scans, rollback plans)
- Execute deployments and monitor post-deployment health
- Manage rollback and incident response procedures
- Document and communicate releases to support and stakeholders
- Track deployment metrics and process improvements

### Goals
- Deploy features safely with minimal customer impact
- Reduce time to recovery (MTTR) in case of incidents
- Enable predictable, low-stress release cadence

### Interactions
- With **Developers**: pre-release verification, deployment troubleshooting
- With **QA Lead**: smoke test execution, release sign-off
- With **Project Manager**: release timeline coordination, stakeholder communication
- With **Tech Lead**: architecture review, rollback validation
- With **On-call Engineer**: incident triage and response

### Typical Communication
- Release notes and deployment checklists
- Deployment window announcements
- Post-deployment verification reports
- Incident retrospectives

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors and Executive Stakeholders provide business context, strategic prioritization, and governance. They enable decisions and escalations, remove blockers, and measure business outcomes.

### Responsibilities
- Define business goals and success metrics for initiatives
- Provide final prioritization decisions across competing initiatives
- Approve resource allocation and budget
- Remove organizational blockers
- Validate business outcomes and ROI
- Serve as escalation point for critical decisions

### Goals
- Ensure initiatives align with business strategy
- Maximize return on product investment
- Enable rapid escalation and unblocking

### Interactions
- With **Product Lead**: strategic alignment, outcome validation, roadmap approval
- With **Project Manager**: status updates, exception escalation, resource approval
- With **Product Manager**: business case review, success metric definition

### Typical Communication
- Monthly or quarterly business reviews
- Executive status updates
- Escalation requests and decision logs
- Business outcome reports

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
