# OctoAcme Role Responsibility Matrix (RACI)

## Purpose
This document provides a clear view of who is Responsible, Accountable, Consulted, and Informed (RACI) for key activities across the project lifecycle at OctoAcme.

## RACI Definitions
- **R - Responsible**: Does the work to complete the task
- **A - Accountable**: Ultimately answerable for the task's completion and has decision-making authority (only one A per task)
- **C - Consulted**: Provides input and expertise (two-way communication)
- **I - Informed**: Kept up-to-date on progress (one-way communication)

---

## Project Initiation Phase

| Activity | PM | PdM | PO | Dev | QA Lead | Release Mgr | UX | BA |
|----------|----|----|----|----|---------|-------------|----|----|
| Define project charter | C | A | C | I | I | I | C | C |
| Define success metrics | C | A | R | I | I | I | C | C |
| Stakeholder identification | R | C | I | I | I | I | I | C |
| Initial risk assessment | A | C | I | C | C | I | I | C |
| Project kickoff meeting | A | R | R | I | I | I | I | I |

## Planning Phase

| Activity | PM | PdM | PO | Dev | QA Lead | Release Mgr | UX | BA |
|----------|----|----|----|----|---------|-------------|----|----|
| Create project timeline | A | C | C | C | C | C | I | I |
| Backlog creation & prioritization | I | C | A | C | C | I | C | C |
| Requirements elicitation | C | C | C | I | I | I | C | A |
| User story creation | I | C | A | C | C | I | C | C |
| Technical design | C | I | C | A | C | I | C | I |
| Test planning | C | I | C | C | A | I | I | C |
| Release planning | C | C | C | C | C | A | I | I |
| Resource allocation | A | C | I | C | I | I | I | I |
| Sprint planning | C | C | R | R | R | I | C | C |

## Execution Phase

| Activity | PM | PdM | PO | Dev | QA Lead | Release Mgr | UX | BA |
|----------|----|----|----|----|---------|-------------|----|----|
| Feature development | I | I | C | A | C | I | C | C |
| Code reviews | I | I | I | A | C | I | I | I |
| Unit testing | I | I | I | A | C | I | I | I |
| UX design creation | C | C | C | C | I | I | A | C |
| Test case development | I | I | C | C | A | I | I | C |
| Test execution | I | I | I | C | A | I | I | I |
| Defect triage | C | C | C | R | A | I | C | C |
| Requirements clarification | I | C | R | C | C | I | C | A |
| Daily standups | R | I | R | R | R | I | R | R |
| Sprint demos | R | R | R | R | R | I | R | R |
| Progress tracking | A | I | I | C | C | I | I | I |
| Risk monitoring | A | C | I | C | C | C | I | C |

## Release & Deployment Phase

| Activity | PM | PdM | PO | Dev | QA Lead | Release Mgr | UX | BA |
|----------|----|----|----|----|---------|-------------|----|----|
| Release planning | C | C | C | C | C | A | I | I |
| Pre-release testing | I | I | C | C | A | C | I | I |
| Deployment execution | I | I | I | C | C | A | I | I |
| Release notes creation | C | C | C | C | C | A | I | C |
| Deployment verification | C | I | C | C | R | A | C | I |
| Rollback decision | C | C | I | C | C | A | I | I |
| Stakeholder communication | A | C | I | I | I | R | I | I |
| Production monitoring | I | I | I | R | C | A | I | I |

## Post-Release & Retrospective

| Activity | PM | PdM | PO | Dev | QA Lead | Release Mgr | UX | BA |
|----------|----|----|----|----|---------|-------------|----|----|
| Retrospective facilitation | A | R | R | R | R | R | R | R |
| Lessons learned documentation | R | C | C | C | C | C | C | C |
| Process improvement actions | A | C | C | C | C | C | C | C |
| Metrics review | R | A | C | C | C | C | I | C |
| Documentation updates | R | C | C | C | C | C | C | C |

## Cross-Cutting Activities

| Activity | PM | PdM | PO | Dev | QA Lead | Release Mgr | UX | BA |
|----------|----|----|----|----|---------|-------------|----|----|
| Stakeholder communication | A | R | C | I | I | C | I | C |
| Change management | A | C | C | C | C | C | I | C |
| Quality assurance | C | C | C | R | A | C | C | C |
| Documentation maintenance | R | C | C | R | R | R | R | R |
| Escalation handling | A | C | I | C | C | I | I | C |
| Team coordination | A | C | R | R | R | R | R | R |

---

## Role Abbreviations
- **PM**: Project Manager
- **PdM**: Product Manager
- **PO**: Product Owner
- **Dev**: Developer
- **QA Lead**: QA Lead
- **Release Mgr**: Release Manager
- **UX**: UX Designer
- **BA**: Business Analyst

## Notes
- This matrix represents typical responsibilities. Actual assignments may vary based on team size, project complexity, and organizational structure.
- For smaller teams, one person may hold multiple roles and thus have combined responsibilities.
- When in doubt about ownership, the Project Manager is responsible for clarifying and documenting role assignments.
- Review and update this matrix during retrospectives to ensure it reflects current team practices.

---

*Last updated: February 2026*
