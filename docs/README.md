# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This folder contains comprehensive documentation on our processes, roles, and best practices for managing projects at OctoAcme.

## Overview

OctoAcme follows a structured five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Retrospective**. The process begins with a lightweight Project One-pager that validates business need, identifies stakeholders, and confirms success metrics before moving forward. Once approved, the team transitions into detailed planning, breaking work into shippable increments with prioritized backlogs, clear acceptance criteria, and estimated timelines. Throughout execution, the team operates with a disciplined rhythm of daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations using GitHub Projects for visibility. Work is managed in small pull requests (≤400 lines) that require CI validation and at least one approval before merging. This approach enables the team to deliver incrementally, gather feedback quickly, and reduce risk through continuous testing and integration.

### Roles and Communication

OctoAcme defines three core delivery personas: **Project Managers** who coordinate schedules, manage risks, and facilitate communication; **Product Managers** who define outcomes, prioritize the backlog, and measure success; and **Developers** who implement features, collaborate on design, and contribute to planning and risk identification. Clear ownership is essential—each project has a named PM and Product Lead responsible for their respective domains. Communication happens through multiple channels: weekly syncs between PM and Product Lead, twice-weekly standups for delivery teams, monthly stakeholder updates, and regular demos at sprint or milestone completion. This multi-tiered communication structure ensures alignment across the organization while maintaining psychological safety and encouraging feedback at all levels.

### Quality, Risk Management, and Continuous Improvement

Quality is embedded throughout OctoAcme's execution model through unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI pipelines. Risk management operates on a three-level escalation path: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. A formal Risk Register captures risks with impact, likelihood, owner, and mitigation plans, reviewed weekly during syncs. After each sprint, release, or milestone, teams conduct blameless retrospectives (45–75 minutes) to capture what went well, identify improvements, and generate 2–3 prioritized action items. This culture of continuous improvement feeds validated changes back into living documentation, ensuring the process evolves with the team's experience while maintaining consistency and reducing single-person dependency risk across the organization.

## Documentation Structure

This folder contains the following process documents:

- **[octoacme-project-management-overview.md](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, key artifacts, roles, and lifecycle
- **[octoacme-project-initiation.md](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[octoacme-project-planning.md](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog
- **[octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)** — Manage day-to-day execution and track progress toward milestones
- **[octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
- **[octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production
- **[octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)** — Detailed definitions of typical roles and responsibilities in OctoAcme projects

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Reference these documents during project initiation, planning, and execution phases
- Use the checklists and templates provided as starting points for your project
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context for AI-assisted guidance
- Update and refine these documents as processes evolve based on team feedback and retrospectives

## Getting Started

If you're new to OctoAcme, start with [octoacme-project-management-overview.md](octoacme-project-management-overview.md) for a concise introduction. Then, based on your phase:

- **Initiating a project?** → [octoacme-project-initiation.md](octoacme-project-initiation.md)
- **Planning work?** → [octoacme-project-planning.md](octoacme-project-planning.md)
- **Executing and tracking?** → [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)
- **Managing risks?** → [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)
- **Releasing to production?** → [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)
- **Reflecting and improving?** → [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)

---

**Purpose of this Knowledge Base**: Centralize scattered project management knowledge, convert tacit team insights into searchable, versioned artifacts, and give all team members equal access to processes, decisions, and rationale.
