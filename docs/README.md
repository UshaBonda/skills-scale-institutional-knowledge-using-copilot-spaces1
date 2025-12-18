# OctoAcme Project Management Documentation

## Overview

This folder contains authoritative, living documentation for standardized project management at OctoAcme.  It centralizes best practices, processes, and artifacts to streamline onboarding, codify institutional knowledge, and enable repeatable, high-quality project execution.

---

## Key Project Management Processes

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation** — Frame business need, stakeholders, and success metrics in a Project One-pager.  Stakeholder and sponsor alignment is required before planning. 
2. **Planning** — Break work into shippable increments with clear acceptance criteria, surface dependencies and risks, document a release plan, and establish backlog priorities.  Planning involves collaborative kickoff, backlog creation, and resource/risk mapping.
3. **Execution** — Use GitHub Projects with workflow columns (Backlog, Ready, In Progress, In Review, QA, Done). Teams hold daily standups, weekly delivery syncs, and ensure all PRs are small (≤400 lines) with linked issues, review, and automated CI/CD checks.  Proactive risk tracking and regular status updates are key.
4. **Release** — Move features through pre-release (acceptance, CI/security, review), run smoke tests, and deploy with rollback plans documented. Communication of deployment and incident practices is standardized.
5. **Close & Retrospective** — Hold regular retrospectives (after sprints/milestones/incidents) capturing learnings, continuous improvements, and tracking follow-up action items.

### Roles & Communication

- **Project Managers** drive delivery, risk management, and cross-team communications. 
- **Product Managers** own vision, outcomes, and backlog priorities.
- **Developers** build, test, and identify technical risks.
- QA/Testing roles validate feature acceptance; stakeholders provide feedback/approvals.
- Cadence: weekly PM/product sync, bi-weekly team standups, monthly stakeholder updates.  Escalation paths are documented for blockers from team → PM → Product Lead → Sponsor.

### Quality & Risk Practices

Quality is embedded with automated tests (unit, integration, end-to-end), manual QA on acceptance, and security scanning.  Risks are tracked in a register (ID, description, impact, owner) and reviewed weekly. Each phase comes with a concise checklist and clear documentation artifact to ensure reliability and accountability at every step. 

---

## Document List
- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) — High-level intro and principles
- [octoacme-project-initiation.md](./octoacme-project-initiation.md) — Authorizing new projects
- [octoacme-project-planning.md](./octoacme-project-planning.md) — Turning ideas into actionable delivery
- [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) — Day-to-day workflows
- [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) — Managing risks and communication
- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment. md) — Shipping features to production
- [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) — Retrospectives and improvement
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) — Roles used in projects

---

## Contributing

Use the [Process Doc Update](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose improvements. Review action items and proposals for alignment with team and stakeholder feedback before merging.

---

**This README is maintained as the single source of truth for project management processes in the docs/ folder.**

---

_Last updated: December 18, 2025_
