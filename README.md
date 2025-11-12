# OctoAcme Project Management Process Docs Index

This folder centralizes OctoAcme's program and project management guidance so teams can find, follow, and contribute to consistent processes. The README below provides a short overview of our approach, links to the process documents in this folder, and guidance for how to use and contribute to them.

## Project Management Processes — Overview

OctoAcme uses a lightweight, iterative lifecycle focused on delivering measurable customer value while ensuring clear ownership, transparent decisions, and actionable traceability. Projects begin with a validated Project One-pager to define goals, stakeholders, success metrics, and a high-level timeline (Initiation). Once approved, the Planning stage breaks work into prioritized, shippable backlog items with clear acceptance criteria, estimates, and a Definition of Done. Teams then execute in short increments with demos, frequent syncs, and disciplined release and QA practices—capturing learnings in retrospectives and tracking improvements after project close.

Workflows emphasize practical conventions for repeatability: program boards (Backlog → Ready → In Progress → In Review → QA → Done), standardized backlog templates, and disciplined pull request practices (small PRs, linked issues, acceptance criteria, CI and security checks, approvals required before merge). Releases are tested, reviewed, and classified (patch/minor/major), with pre-release and rollback plans and incident response playbooks.

Core roles and personas (Product Manager, Project Manager, Developer, QA, Stakeholder) are clearly defined to reduce ambiguity. The PM and PdM align weekly to prioritize and monitor progress, while the delivery team holds regular standups and milestone demos. Stakeholder communication follows a structured cadence and uses templates for reporting progress, risks, and decisions.

Quality assurance and continuous improvement are built in—automated tests and CI pipelines, security scanning, manual QA, risk registers reviewed in cadence meetings, and regular retrospectives to convert learnings into actionable improvements. All artifacts and processes live in this repository to ensure transparency, reduce onboarding friction, and eliminate dependency on tacit knowledge.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to Use & Contribute

- Use this README as the starting point for program management knowledge.
- Propose improvements using the ".github/ISSUE_TEMPLATE/Add Content to Project Management Process Docs" template.
- Keep docs concise and actionable, update front-matter metadata, and cross-link related guidance for discoverability.
- Review process docs quarterly; track adoption and impact in stakeholder syncs.

## Acceptance Checklist for this README

- [ ] Summary aligns with the existing process documents in this folder
- [ ] Contains direct links to all docs in docs/
- [ ] Reviewed by at least one PM and one process owner
