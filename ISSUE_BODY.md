## Which process document do you want to update?
<new document>

## Summary of New Content

Create a comprehensive README file for the OctoAcme Project Management Docs that serves as the central entry point for all process documentation. The README will include:

1. **Overview of OctoAcme Project Management Approach** - A brief summary of the core principles and lifecycle
2. **Complete Navigation Links** - Indexed links to all process documents in the docs/ folder:
   - octoacme-project-management-overview.md
   - octoacme-project-initiation.md
   - octoacme-project-planning.md
   - octoacme-execution-and-tracking.md
   - octoacme-risks-and-communication.md
   - octoacme-release-and-deployment.md
   - octoacme-retrospective-and-continuous-improvement.md
   - octoacme-roles-and-personas.md
3. **Quick Reference Guide** - Summarizing the project lifecycle phases and key roles
4. **How to Use These Docs** - Guidance for team members on documentation best practices

## Why is this update needed?

Team members need a single entry point to understand OctoAcme's project management processes. Currently, process documentation is scattered across multiple files with no clear navigation structure. A comprehensive README will:

- **Improve Onboarding** - Help new team members quickly understand our approach
- **Enhance Discoverability** - Provide a clear index to find relevant process docs
- **Centralize Knowledge** - Establish docs/ as the authoritative source for process guidance
- **Reduce Search Time** - Eliminate confusion about which document to consult
- **Support Copilot Spaces** - Enable grounding Copilot in structured, versioned documentation

## Suggested Content

### Proposed README.md Structure:

```markdown
# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme Project Management Documentation Hub. This directory contains comprehensive guides for managing projects from initiation through retrospectives.

## 📋 Quick Overview

OctoAcme follows a **customer-first, iterative delivery approach** with clear ownership and data-informed decision-making. Our project lifecycle comprises five key phases:

1. **Initiation** - Validate business need and align stakeholders
2. **Planning** - Break work into shippable increments and establish baselines
3. **Execution** - Build, test, review, and iterate daily
4. **Release** - Deploy features and verify quality
5. **Close & Retrospective** - Capture learnings and improve continuously

## 📚 Process Documentation

| Phase | Document | Purpose |
|-------|----------|---------|
| **Overview** | [Project Management Overview](./octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, roles, and key artifacts |
| **Initiation** | [Project Initiation Guide](./octoacme-project-initiation.md) | Steps to validate work and align stakeholders |
| **Planning** | [Project Planning](./octoacme-project-planning.md) | Creating actionable plans and prioritized backlogs |
| **Execution** | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery, testing, and progress tracking |
| **Cross-cutting** | [Risk Management & Communication](./octoacme-risks-and-communication.md) | Managing risks, dependencies, and stakeholder communication |
| **Release** | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardized release processes and rollback procedures |
| **Retrospectives** | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and driving improvements |
| **Reference** | [Roles and Personas](./octoacme-roles-and-personas.md) | Definitions of key roles and responsibilities |

## 👥 Core Roles

- **Project Manager (PM)** - Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)** - Defines outcomes, prioritizes backlog, and measures success
- **Developers** - Implement features and collaborate on design and quality
- **QA/Testing** - Validates quality and acceptance criteria
- **Stakeholders** - Provide inputs and approvals

## 🎯 Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## 🚀 How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
3. **Planning delivery?** Reference [Project Planning](./octoacme-project-planning.md)
4. **In execution?** Use [Execution & Tracking](./octoacme-execution-and-tracking.md)
5. **Preparing a release?** Review [Release & Deployment Guide](./octoacme-release-and-deployment.md)
6. **Improving processes?** Consult [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## 📝 Communication Cadence

- **Daily**: Team standups (15 min)
- **Weekly**: PM + PdM sync, delivery team standups, risk register review
- **Monthly**: Stakeholder updates
- **Per-sprint**: Sprint planning, demos, retrospectives
- **Ad-hoc**: Escalations and incident communications

## 🔄 Quick Links

- [Add Content to Project Management Process Docs](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

## Questions or Feedback?

If you'd like to suggest updates to these processes, please [open an issue](../../issues) using the "Add Content to Project Management Process Docs" template.
```

## Acceptance Criteria

- ✅ Content aligns with existing process docs
- ✅ Update improves clarity or closes a documented gap
- ✅ Proposed content has been reviewed with stakeholders (if needed)
