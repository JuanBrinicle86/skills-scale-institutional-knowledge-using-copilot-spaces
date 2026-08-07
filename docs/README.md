# OctoAcme Project Management Docs

This README is an index of OctoAcme project management process documents stored in the docs/ folder and provides a short summary of our project management approach. Use this README as the single point of entry to find the Project One-pager, planning and execution guidance, release checklists, risk templates, and persona descriptions.

OctoAcme runs projects through a clear, stage-based lifecycle from Initiation to Planning, Execution, Release, and Retrospective. Initiation uses a concise Project One‑pager to capture the problem statement, goals, success metrics, stakeholders, and a high-level timeline. The decision gate before planning confirms success metrics and stakeholder alignment. Planning turns approved initiatives into shippable backlog items with acceptance criteria, estimates, a Definition of Done, and a release/milestone map — including an explicit risk register and dependency tracking.

Day‑to‑day execution is board-driven (Backlog → Ready → In Progress → In Review → QA → Done) and supported by a disciplined Pull Request workflow that favors small PRs, includes issue links and acceptance criteria, and requires CI checks and approvals before merging. Team rhythm includes daily standups for progress and blockers, weekly delivery syncs for progress and flagged risks, sprint demos/reviews, and regular PM–PdM alignment. The project also defines escalation paths for blockers and incident communication templates to coordinate cross-team responses.

Quality assurance is integrated across the lifecycle: unit and integration tests for new logic, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when necessary. Releases follow pre‑release checks (CI/security scans, release notes, rollback plans), a deployment checklist (staging smoke tests and post‑deploy verifications), and post‑release retrospectives that convert learnings into tracked action items.

## Links to process documents

- [Project Management Overview](docs/octoacme-project-management-overview.md)  
- [Project Initiation Guide](docs/octoacme-project-initiation.md)  
- [Project Planning](docs/octoacme-project-planning.md)  
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)  
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)  
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)  
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)  
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use
- Add this README to docs/ as `README.md`. Keep links updated if filenames or locations change.
- Use the Project One-pager and release templates as living artifacts inside the project repo.
- When you update process docs, create an issue using the "Add Content to Project Management Process Docs" template and link it to the change for traceability.

## Acceptance Criteria
- [x] Content aligns with existing process docs  
- [x] Update improves clarity or closes a documented gap  
- [ ] Proposed content has been reviewed with stakeholders (if needed)
