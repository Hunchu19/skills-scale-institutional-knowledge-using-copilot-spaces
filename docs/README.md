# OctoAcme Project Management Docs

This README indexes all major project management process documents for the OctoAcme program and summarizes the project management methodology used by the team.

## OctoAcme Project Management Process Summary

OctoAcme follows a five-phase project lifecycle designed to deliver customer value through iterative, well-planned execution. The process begins with **Initiation**, where new project ideas are validated through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics. Once approved, projects move into **Planning**, where work is broken into shippable increments with clear acceptance criteria and a prioritized backlog. The **Execution** phase emphasizes daily delivery with regular standups, sprint-based iteration, and continuous risk monitoring. Upon completion, projects proceed to **Release**, which includes pre-deployment verification and smoke testing, followed by **Close & Retrospective** to capture learnings and drive continuous improvement. This phased approach ensures projects remain aligned with business objectives while maintaining flexibility to adapt based on evidence and feedback.

OctoAcme defines clear ownership through four core personas: **Project Managers (PMs)** who coordinate delivery, manage risks, and facilitate communication; **Product Managers (PdMs)** who define outcomes, prioritize work, and measure success; **Developers** who implement features and collaborate on design and quality; and **QA/Testing** who validate acceptance criteria. The organization emphasizes psychological safety and customer-first principles to encourage innovation and learning. Communication occurs through a structured cadence: daily standups (15 minutes) focus on progress and blockers; weekly syncs between PM and PdM align on strategy and risks; twice-weekly standups coordinate the delivery team; and monthly stakeholder updates provide visibility. Cross-team dependencies are explicitly tracked in the project board and escalated during weekly syncs, with three-level escalation paths for blockers (team triage → PM escalation → sponsor involvement).

Quality is built into every stage of OctoAcme projects through defined Definition of Done criteria and comprehensive testing practices. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require automated CI testing, linting, and at least one approval before merge. The team employs a multi-layered quality strategy: unit tests validate new logic, integration tests verify component interactions, end-to-end smoke tests confirm critical flows before release, and security scanning runs in CI. Manual QA is applied for feature acceptance when needed. Project boards use standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to provide transparent tracking and enable team synchronization. Velocity and burndown metrics are tracked to inform planning, and post-deployment verifications ensure production stability.

OctoAcme institutionalizes risk management through a formal Risk Register maintained throughout the project lifecycle. Each risk is documented with ID, description, impact/likelihood assessment, owner, and mitigation plan, then reviewed at weekly syncs to monitor status and escalate as needed. Critical production issues trigger an incident playbook with root cause analysis and rollback procedures. The organization also embeds continuous improvement through structured retrospectives held after each sprint, release, or milestone, using anonymous idea boards to encourage candor. Retrospectives prioritize 2–3 actionable improvements with clear owners and due dates, which are then tracked in the project backlog. This systematic approach to learning—measuring impact of action items and celebrating improvements—creates a culture of iterative refinement that strengthens processes over time.

## Process Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
