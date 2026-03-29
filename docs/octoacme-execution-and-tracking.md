# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Cross-Functional Role Responsibilities During Execution

Clear ownership across all roles during key execution ceremonies reduces confusion and keeps delivery on track.

### Daily Standup
| Role | Responsibility |
|---|---|
| **Project Manager** | Facilitates the standup; captures blockers and updates the project board |
| **Developers** | Report progress, flag blockers, and note dependencies |
| **Product Manager** | Available for quick clarifications on scope or priorities |
| **Release Manager** | Flags deployment risks or environment issues affecting current work |
| **Business Analyst** | Clarifies requirements questions raised by Developers |

### Sprint Demo / Review
| Role | Responsibility |
|---|---|
| **Project Manager** | Coordinates demo logistics and prepares the agenda |
| **Developers** | Demo completed work against acceptance criteria |
| **Product Manager** | Reviews and accepts or rejects work; captures feedback |
| **Business Analyst** | Validates that delivered features meet documented requirements |
| **Support Lead** | Reviews new features for support documentation needs and potential customer impact |
| **UX Researcher** | Shares any usability findings relevant to features being reviewed |

### Sprint Retrospective
| Role | Responsibility |
|---|---|
| **Project Manager** | Facilitates and documents action items |
| **All team members** | Contribute "what went well," improvements, and actionable items |
| **Support Lead** | Brings in customer feedback themes from the sprint |
| **UX Researcher** | Surfaces usability insights observed during the sprint |

---

## Support Lead & UX Researcher Feedback Loops

Integrating customer and user insights throughout execution—not just at launch—improves quality and reduces rework.

### Support Lead Feedback Loop
- **Input**: Support Lead gathers customer-reported bugs, friction points, and feature requests on an ongoing basis.
- **Triage**: Weekly bug triage meeting between Support Lead, Product Manager, and Dev lead prioritizes issues for the current or next sprint.
- **Tracking**: High-priority customer issues are added to the project board with a `customer-reported` label and tracked to resolution.
- **Closure**: Support Lead communicates resolutions back to affected customers and updates support documentation.

### UX Researcher Feedback Loop
- **Input**: UX Researcher conducts usability studies and interviews aligned to features in active development or recently released.
- **Synthesis**: Findings are synthesized into an insights report shared with the Product Manager and relevant Developers before the next sprint planning session.
- **Prioritization**: Product Manager incorporates high-impact usability improvements into the backlog with appropriate priority.
- **Validation**: UX Researcher validates that implemented improvements meet the intended usability goal before the sprint closes.

---

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Support Lead included in sprint reviews for customer feedback
- [ ] UX Researcher insights reviewed at sprint planning
- [ ] Cross-functional role responsibilities communicated to all team members
