# OctoAcme Project Management Docs

Welcome! This README provides an overview of OctoAcme's project management processes and quick links to all docs in this folder.

## Overview of Project Management at OctoAcme

OctoAcme employs a structured, customer-focused project management methodology that emphasizes iterative delivery and clear ownership. The approach is built on five core principles: prioritizing customer value and usability, delivering work in small testable increments, establishing clear ownership through named Project Managers and Product Leads, making data-informed decisions based on measured impact, and fostering psychological safety to encourage feedback and learning. The organizational structure defines four key roles—Project Managers who coordinate delivery and manage risk, Product Managers who define outcomes and prioritize the backlog, Developers who implement features and collaborate on design, and QA/Testing specialists who validate quality—working together across a standardized lifecycle that progresses through initiation, planning, execution, release, and retrospective phases. Projects begin with a lightweight Project One-pager that establishes business need and success metrics, followed by structured planning that produces prioritized backlogs, release timelines, and clearly defined acceptance criteria before the delivery team begins work.

Execution at OctoAcme follows a disciplined rhythm that combines daily coordination with robust quality practices. The team operates through daily 15-minute standups focused on progress and blockers, weekly delivery syncs, and end-of-sprint demos, while managing work through a project board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests are kept small (≤400 lines when possible) and require at least one approval plus passing CI/linting before merge. Quality assurance is comprehensive, incorporating unit tests for new logic, integration and end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when needed. Progress is tracked through velocity and burndown metrics, with success measured against metrics established in the Project One-pager. Blockers are escalated through a three-level system: team-level triage in standups, PM escalation to Product Leads and dependent teams, and sponsor-level escalation for business-impacting issues.

Risk management is woven throughout the project lifecycle, with a Risk Register maintained to track identified risks by ID, description, impact, likelihood, owner, and mitigation plan. Risks are identified during planning and ongoing execution, assessed for impact and likelihood, actively mitigated through documented actions and contingency plans, and reviewed at weekly syncs. Communication is structured through multiple channels: weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates, supplemented by ad-hoc escalations as needed. A consistent communication template ensures stakeholders receive progress updates, next steps, and visibility into risks and blockers, with special protocols for incident communication that include triage summaries, actions being taken, and expected timelines. Additionally, clear escalation paths guide when and how issues move from team-level to PM to Product Lead to Sponsor, ensuring appropriate visibility and decision-making authority.

OctoAcme emphasizes learning and improvement through structured retrospectives held after each sprint, release, or important milestone. Retrospectives follow a consistent structure examining what went well, what could improve, and generating 2–3 prioritized action items with clear owners and due dates. Release management is standardized with pre-release requirements including passed acceptance criteria, CI and security scans, drafted release notes, documented rollback plans, and prepared smoke tests. Deployment follows a checklist including staging verification, post-deploy verification, and stakeholder announcements, with a clear rollback and incident playbook to address deployment failures or critical issues. This combination of regular learning cycles, clear release gates, and incident response capabilities creates an environment where teams continuously refine their processes and maintain high delivery velocity while minimizing production risk.

## 📑 Docs Index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risks and Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

_Stored in [`docs/`](./)_
