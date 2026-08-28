# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process documentation. This collection provides guidance for running projects at OctoAcme, from initial concept through delivery and continuous improvement.

## Overview

OctoAcme operates on a structured, iterative approach to project management that emphasizes **customer value**, **clear ownership**, **data-informed decisions**, and **psychological safety**. Our framework supports cross-functional project delivery of features, services, and integrations through a consistent five-phase lifecycle with lightweight but comprehensive governance.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Ship small, testable increments
- **Clear ownership**: Every project has named Project Manager (PM) and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Key Roles
- **Project Manager**: Coordinates delivery, schedules, risk, and communications
- **Product Manager**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provides inputs and approvals

## Project Lifecycle

OctoAcme projects flow through five distinct phases:

1. **Initiation** → Validate business need, align stakeholders, create Project One-pager
2. **Planning** → Break work into shippable increments, identify dependencies and risks
3. **Execution** → Build, test, review, iterate with daily standups and weekly syncs
4. **Release** → Deploy with standardized controls, verify, and announce
5. **Retrospective** → Capture learnings and feed improvements back into the process

---

## Documentation Map

### 📋 [Project Management Overview](./octoacme-project-management-overview.md)
**Start here** for a concise introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle. Best for new team members and stakeholders getting oriented.

### 🚀 [Project Initiation Guide](./octoacme-project-initiation.md)
Guidance for validating and authorizing new work. Covers:
- Initial stakeholder alignment
- Project One-pager template
- Go/no-go decision criteria
- Initiation checklist

### 📐 [Project Planning](./octoacme-project-planning.md)
Turning approved initiatives into actionable plans and backlogs. Covers:
- Backlog creation and prioritization
- Scope estimation and Definition of Done
- Sprint/iteration planning
- Risk and dependency management

### ⚙️ [Execution & Tracking](./octoacme-execution-and-tracking.md)
Day-to-day execution guidance and progress management. Covers:
- Team rhythm (daily standups, weekly syncs, demos)
- GitHub Projects board workflow and PR conventions
- Quality and testing practices
- Blocker escalation paths

### 🛡️ [Risk Management & Communication](./octoacme-risks-and-communication.md)
Managing risks and keeping stakeholders informed. Covers:
- Risk Register structure and lifecycle
- Stakeholder communication strategies
- Weekly status templates
- Incident communication and escalation paths

### 📦 [Release & Deployment Guide](./octoacme-release-and-deployment.md)
Standardizing how features reach production. Covers:
- Release types (patch, minor, major)
- Pre-release checklist and deployment steps
- Rollback and incident playbook
- Release notes template

### 🔍 [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capturing learnings and driving iterative improvement. Covers:
- Retrospective structure and facilitation
- Action item tracking and follow-up
- Continuous improvement culture
- Action item template

### 👥 [Roles & Personas](./octoacme-roles-and-personas.md)
Detailed descriptions of core project delivery roles and responsibilities. Includes:
- Developer responsibilities and goals
- Product Manager responsibilities and goals
- Project Manager responsibilities and goals
- How personas are used in exercises and scenarios

---

## Communication Cadence

- **Daily**: Team standups (15 min focus on progress, blockers, dependencies)
- **Twice-weekly**: Delivery team standups (or as agreed)
- **Weekly**: PM + Product Lead sync
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communication

---

## Quick Links & Common Workflows

### Starting a New Project
1. Read: [Project Management Overview](./octoacme-project-management-overview.md)
2. Create: [Project One-pager](./octoacme-project-initiation.md#project-one-pager-template)
3. Execute: [Initiation Checklist](./octoacme-project-initiation.md#initiation-checklist)
4. Move to: [Project Planning](./octoacme-project-planning.md)

### During Active Delivery
- Reference: [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily workflows
- Maintain: [Risk Register](./octoacme-risks-and-communication.md#risk-register) — review weekly
- Track: Progress via GitHub Projects and metrics from the Project One-pager
- Communicate: Use [Weekly Status Template](./octoacme-risks-and-communication.md#communication-templates)

### Preparing a Release
1. Review: [Pre-release requirements](./octoacme-release-and-deployment.md#pre-release-requirements)
2. Complete: [Deployment Checklist](./octoacme-release-and-deployment.md#deployment-checklist)
3. Prepare: [Release Notes](./octoacme-release-and-deployment.md#release-notes-template)
4. Have ready: [Rollback plan](./octoacme-release-and-deployment.md#rollback--incident-playbook)

### After a Project or Milestone
1. Schedule: [Retrospective](./octoacme-retrospective-and-continuous-improvement.md)
2. Capture: What went well, what could improve
3. Create: [Action items](./octoacme-retrospective-and-continuous-improvement.md#example-action-item-template) with owners and due dates
4. Track: Follow-up on improvements in weekly PM syncs

---

## Using These Docs

- **For projects**: Keep the Project One-pager and key artifacts updated in your project repository
- **For Copilot Spaces**: Add process-specific docs to `.copilot/` if you want Copilot to use them as context
- **For onboarding**: Share the [Project Management Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md) with new team members
- **For continuous improvement**: Treat these docs as living artifacts—update them as the team evolves and validates better approaches

---

## Support & Feedback

To request updates or add content to these process docs:
- Create an issue using the [**"Add Content to Project Management Process Docs"**](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
- Propose changes via pull request with a clear rationale for the update
- Share feedback in team retrospectives or syncs

---

*Last updated: 2026*  
*Maintained by: OctoAcme Project Management Community*
