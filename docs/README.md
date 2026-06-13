# OctoAcme Project Management Processes

This README provides a centralized index and overview of OctoAcme's project management processes. It serves as the single source of truth for understanding how OctoAcme runs projects and links to detailed guidance for each phase.

## Overview

OctoAcme follows a structured project lifecycle designed to validate ideas, plan execution, deliver iteratively, release safely, and continuously improve. The approach emphasizes clear ownership, data-informed decisions, and psychological safety. All cross-functional projects—whether delivering product features, services, or integrations—follow this framework.

### Key Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle Phases

### 1. **Initiation** — Validate & Authorize
Confirm business need and measurable outcomes, align stakeholders, and make a go/no-go decision.

**Key deliverables**: Project One-pager (Problem, Goal, Success Metrics), Stakeholder list, Initial timeline, Risk list, Resource needs

**Success criteria**: Success metrics are clear, stakeholders agree on priority, team availability confirmed

→ **Learn more**: [Project Initiation Guide](octoacme-project-initiation.md)

### 2. **Planning** — Create Actionable Plan
Turn an approved initiative into a prioritized backlog and roadmap with clear dependencies and responsibilities.

**Key activities**: Kickoff meeting, Prioritized backlog with acceptance criteria, Estimation (T-shirt sizing or story points), Definition of Done, Dependency mapping, Release plan and milestones

**Outcomes**: Backlog ready for sprint planning, Release timeline agreed, Initial test plan drafted

→ **Learn more**: [Project Planning](octoacme-project-planning.md)

### 3. **Execution & Tracking** — Build & Deliver
Manage day-to-day execution, track progress toward milestones, and maintain team rhythm through standups, syncs, and demos.

**Key workflows**: Project board (Backlog → Done), Small PRs (≤400 lines) with automated CI, Daily standups (15 min), Weekly delivery syncs, Quality assurance (unit, integration, E2E, security tests)

**Rhythm**: Daily standups, Weekly delivery sync, Demo/Review at sprint/milestone end

→ **Learn more**: [Execution & Tracking](octoacme-execution-and-tracking.md)

### 4. **Release & Deployment** — Ship Safely
Standardize release processes to reduce risk, improve observability, and enable fast rollback if needed.

**Release types**: Patch (hotfixes), Minor (incremental features), Major (significant/breaking changes)

**Pre-release checklist**: Acceptance criteria met, Passing CI and security scans, Release notes drafted, Rollback plan documented, Smoke tests prepared

→ **Learn more**: [Release & Deployment Guide](octoacme-release-and-deployment.md)

### 5. **Close & Retrospective** — Learn & Improve
Capture learnings after each sprint, release, or milestone and convert them into actionable improvements.

**Retrospective structure**: What went well, What could be improved, Action items (owner, due date)

**Follow-up**: Add action items to backlog, Review at weekly PM sync, Measure impact of improvements

→ **Learn more**: [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Cross-Cutting Concerns

### Risk Management & Communication
Maintain a Risk Register throughout the project lifecycle and follow stakeholder communication templates to ensure alignment.

**Risk escalation path**: Team-level → PM → Product Lead → Sponsor

**Communication cadence**: Weekly status (PM + PdM), Twice-weekly standups (delivery team), Monthly stakeholder updates, Ad-hoc escalations

→ **Learn more**: [Risk Management & Communication](octoacme-risks-and-communication.md)

### Roles & Personas
Each project has clear ownership and defined responsibilities across multiple personas.

- **Project Manager**: Coordinates delivery, schedules, risks, communications
- **Product Manager**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria

→ **Learn more**: [Roles & Personas](octoacme-roles-and-personas.md)

## Document Index

| Document | Purpose | Audience |
|----------|---------|----------|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme approach, roles, and key artifacts | Everyone (quick start) |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to validate ideas and authorize new projects | PMs, Product Leads, Sponsors |
| [Project Planning](octoacme-project-planning.md) | Turning an initiative into a prioritized backlog and roadmap | PMs, Developers, QA |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Daily rhythms, workflows, quality assurance, and progress tracking | Developers, QA, Delivery Team |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, deployment checklist, rollback playbook, release notes | Developers, DevOps, PMs |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, stakeholder communication templates | PMs, Product Leads, All (for escalations) |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and tracking action items | All team members |
| [Roles & Personas](octoacme-roles-and-personas.md) | Role summaries, responsibilities, and communication patterns | All (reference) |

## How to Use These Docs

- **Onboarding**: Start with [Project Management Overview](octoacme-project-management-overview.md) for a 5-minute orientation, then dive into phase-specific docs as needed
- **Project kickoff**: Use the Project One-pager template from [Project Initiation Guide](octoacme-project-initiation.md)
- **During execution**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and checklists regularly
- **Updates & improvements**: Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose edits or additions
- **Copilot Spaces**: Add these docs to your Copilot Space for context-specific guidance aligned with OctoAcme processes

## Contributing to Process Docs

To propose updates or additions to these process documents:

1. Open a new issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Describe the gap, clarification needed, or best practice to add
3. Provide suggested content (optional)
4. Get stakeholder review if needed
5. Update the relevant doc and this README if adding a new document

Keep these docs as the **single source of truth** for OctoAcme project management practices. Update them collaboratively as the team learns and evolves.
