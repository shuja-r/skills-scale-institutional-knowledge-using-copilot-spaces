# OctoAcme Project Management Processes

This folder centralizes OctoAcme's project management processes and provides a single entry point to the team's lifecycle, roles, workflows, communication cadence, and quality practices. The processes are designed to enable predictable delivery of customer value through small, testable increments and a shared Definition of Done. Projects progress through a clear lifecycle — Initiation, Planning, Execution, Release, and Close & Retrospective — with named owners and measurable success criteria captured in a lightweight Project One-pager.

Roles and responsibilities are defined to ensure clear ownership and accountability. Project Managers coordinate schedules, manage risks and cross-team communication; Product Managers own outcomes, prioritize the backlog, and define acceptance criteria; Developers design, implement, and maintain code with test coverage; and QA validates acceptance criteria and runs both automated and manual checks where required. These personas work together in a cross-functional delivery team to ensure alignment on scope, timeline, and quality.

Day-to-day work follows an established rhythm and lightweight workflows: daily standups for progress and blockers, weekly delivery syncs for status and cross-team dependencies, periodic demos/reviews for stakeholder feedback, and sprint planning to pull only items that meet the Definition of Done. Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done). The pull request workflow encourages small PRs, CI-based automated testing and linting, at least one reviewer approval (team-defined), and explicit acceptance criteria referenced in PR descriptions.

Quality assurance and release practices minimize risk and improve observability. Teams rely on unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and documented rollback plans for production deployments. Pre-release checks require passing CI/security scans, drafted release notes, and prepared smoke tests. Post-release, teams run retrospectives and convert action items into backlog issues to ensure continuous improvement.

Process documents in this folder:
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-release-and-deployment.md
- octoacme-risks-and-communication.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

How to propose updates
- Use the "Add Content to Project Management Process Docs" issue template at .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml to propose new content or updates.
- Track proposed changes as issues and attach PRs to the corresponding issue for review and approval.