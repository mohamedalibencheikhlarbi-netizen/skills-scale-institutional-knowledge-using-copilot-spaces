# OctoAcme Project Management Docs

This README gathers OctoAcme's core project management process documents and provides a summary of the processes and links to the full docs in the `docs/` folder.

## OctoAcme Project Management Overview

OctoAcme follows a structured, iterative project lifecycle that prioritizes customer value, clear ownership, and data-driven decision-making. The process is organized across five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. During initiation, teams validate business needs and create a lightweight one-pager that confirms success metrics, stakeholder alignment, and resource requirements. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a defined Definition of Done. This deliberate gating ensures teams move forward only when objectives are clear and stakeholders are aligned, reducing rework and scope creep.

Execution and tracking are managed through a combination of structured ceremonies and continuous workflows. Teams operate on a regular cadence of daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations using GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests follow a lightweight protocol with clear size limits (≤400 lines when possible), automated CI checks, and at least one approval before merging. Quality is embedded throughout execution via unit tests, integration tests, end-to-end smoke tests, and security scanning. A tiered blocker escalation system—from team-level triage to sponsor-level intervention—ensures risks don't derail delivery.

Communication and risk management are central to OctoAcme's approach. The organization defines three primary roles: **Product Managers** (who define outcomes and prioritize the roadmap), **Project Managers** (who coordinate delivery and manage schedules/risks), and **Developers** (who implement features and collaborate on design). A weekly PM-to-PdM sync, twice-weekly standups, and monthly stakeholder updates create transparency across all levels. Risk registers are maintained with impact, likelihood, owner, and mitigation plans, reviewed weekly during syncs. Escalation paths are clearly defined—from team level to PM to Product Lead to Sponsor—ensuring critical issues surface quickly.

Finally, OctoAcme closes the loop through structured retrospectives and continuous improvement. After each sprint, release, or milestone, teams conduct 45–75 minute retrospectives to capture what went well, what could improve, and assign 2–3 actionable items with owners and due dates. These improvements feed back into future backlogs and processes, creating a culture of learning and iterative refinement. Release deployments are controlled through pre-release checklists, staging validation, smoke tests, and documented rollback plans, ensuring production stability. This end-to-end approach—from initiation through retrospective—establishes repeatable, transparent, and scalable project execution across OctoAcme's teams.

## Quick Summary of OctoAcme Processes

- **Project Initiation:** Validate and authorize work with a one-pager, stakeholder alignment, and a lightweight decision gate to move into planning.
- **Project Planning:** Break approved initiatives into prioritized backlog items, estimate scope, define Definition of Done, and create a release/milestone plan.
- **Execution & Tracking:** Use a project board to track work (Backlog → Ready → In Progress → In Review → QA → Done), run small PRs, CI checks, and regular team rhythms (standups, weekly sync, demos).
- **Risk & Communication:** Maintain a risk register, assess and mitigate risks, and use defined escalation paths for blockers and incidents.
- **Release & Deployment:** Follow pre-release checks, automated pipelines, smoke tests, and rollback/playbook procedures for production deploys.
- **Retrospective & Continuous Improvement:** Run regular retrospectives, capture action items with owners and due dates, and track improvements.

## Links to Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts
- [Project Initiation Guide](octoacme-project-initiation.md) — Define and validate work with a one-pager and stakeholder alignment
- [Project Planning](octoacme-project-planning.md) — Turn approved initiatives into actionable plans and prioritized backlogs
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day execution, track progress, and escalate blockers
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize releases and reduce production risk
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive iterative improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Definitions of core roles and responsibilities

## How to Use

Start here when:
- **Onboarding** new Project Managers, Product Managers, or delivery team members
- **Setting up** a new project and need guidance on process phases
- **Looking up** a specific workflow or role responsibility
- **Contributing** to process improvements or new documentation

Keep this README updated when process docs change. Use it as the single entry point to OctoAcme's project management knowledge base.
