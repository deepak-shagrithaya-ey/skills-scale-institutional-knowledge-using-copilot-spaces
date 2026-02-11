# OctoAcme Project Management Docs

Welcome! This folder contains comprehensive documentation on OctoAcme's project management framework, designed to help team members understand how we run projects, coordinate across roles, and deliver customer value iteratively.

## Quick Start
- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction.
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md).
- **Looking for execution guidance?** Jump to [Execution & Tracking](./octoacme-execution-and-tracking.md).

---

## Project Management Processes (Summary)

### Overview & Lifecycle
OctoAcme follows a structured, customer-first project lifecycle that emphasizes iterative delivery and clear ownership. The framework spans five core phases: **Initiation** (validating business need and stakeholder alignment through a lightweight Project One-pager), **Planning** (breaking work into shippable increments with prioritized backlogs and acceptance criteria), **Execution** (day-to-day delivery with daily standups and sprint reviews), **Release** (standardized deployment with pre-release checks and rollback plans), and **Retrospective** (capturing learnings and driving continuous improvement). This phased approach ensures that projects move through decision gates where success metrics are clear, stakeholders agree on priority, and team availability is confirmed before advancing to the next phase.

### Key Roles & Communication Cadence
OctoAcme operates with clearly defined personas: **Project Managers** coordinate schedules, risks, and communications to ensure on-time delivery; **Product Managers** define customer value, prioritize the backlog, and measure outcomes; **Developers** design and build features while maintaining quality through testing and code reviews; and **QA/Testing** validates acceptance criteria and feature quality. Communication is structured and regular, with daily standups (15 minutes focused on progress and blockers), weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates. Risk escalation follows a clear path: Level 1 (team-level triage in standups) → Level 2 (PM escalates to Product Lead and dependent teams) → Level 3 (sponsor-level for business-impacting issues).

### Quality Assurance & Execution Standards
Quality is embedded throughout execution via a disciplined pull request workflow requiring small PRs (≤400 lines when possible), automated CI testing and linting, and at least one approval before merge. The team maintains a risk register updated weekly, tracks velocity and burndown metrics, and conducts regular demos at sprint or milestone ends. All work flows through a standardized GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), with a Definition of Done that includes unit tests, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI.

### Risk Management & Release Excellence
Risk management is proactive and documented through a Risk Register that captures ID, description, impact, likelihood, owner, mitigation plan, and status—reviewed during weekly syncs. Deployment is carefully controlled with pre-release requirements including passing CI/security scans, drafted release notes, documented rollback plans, and smoke tests. Each release is announced via stakeholder communications and tracked via release notes that document changes, migration steps, and known issues. This comprehensive approach, combined with blameless retrospectives and documented action items with clear owners and due dates, creates a culture of continuous improvement and psychological safety where teams learn and iterate based on evidence.

---

## Process Documents

| Document | Purpose |
|----------|---------|
| [**Project Management Overview**](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence. Start here. |
| [**Project Initiation Guide**](./octoacme-project-initiation.md) | Steps to validate new projects, align stakeholders, and create the Project One-pager before moving to planning. |
| [**Project Planning**](./octoacme-project-planning.md) | How to break work into shippable increments, estimate scope, define acceptance criteria, and manage dependencies. |
| [**Execution & Tracking**](./octoacme-execution-and-tracking.md) | Day-to-day delivery guidance including team rhythm, PR workflows, quality standards, and blocker escalation. |
| [**Risk Management & Communication**](./octoacme-risks-and-communication.md) | Maintain and monitor the Risk Register, communicate with stakeholders, and follow escalation paths. |
| [**Release & Deployment Guide**](./octoacme-release-and-deployment.md) | Standardized release process, deployment checklist, rollback procedures, and release notes template. |
| [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives, capturing learnings, and turning action items into measurable improvements. |
| [**Roles & Personas**](./octoacme-roles-and-personas.md) | Detailed descriptions of Project Managers, Product Managers, Developers, and QA responsibilities and goals. |

---

## How to Use These Docs

1. **For New Team Members:** Start with the overview and your role-specific persona doc, then dive into phases as you join projects.
2. **For Project Kickoff:** Use the Initiation and Planning guides as checklists for setup.
3. **For Daily Work:** Reference Execution & Tracking, PR workflows, and the Definition of Done.
4. **For Risk & Issues:** Consult Risk Management & Communication and escalation paths.
5. **For Releases:** Follow the Release & Deployment guide's checklist.
6. **For Learning & Improvement:** Run retrospectives using the template and track improvements.

---

## Continuous Improvement

These docs are living artifacts. If you encounter gaps, unclear sections, or process improvements, please:
- **Create an issue** using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
- **Propose updates** via pull request with clear rationale
- **Share feedback** with your Project Manager or Product Lead

This ensures our processes stay accurate, current, and aligned with how we actually work.