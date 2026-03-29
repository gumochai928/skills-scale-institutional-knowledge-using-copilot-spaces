# OctoAcme — Stakeholder Management Guide

## Purpose
A reference for Project Managers on managing stakeholder expectations, communications, and feedback loops throughout the project lifecycle. This guide provides practical templates and processes to keep stakeholders informed, engaged, and aligned.

---

## Stakeholder Identification & Mapping

Before creating a communication plan, identify and categorize all stakeholders.

### Stakeholder Categories

| Category | Description | Examples |
|---|---|---|
| **Sponsors** | Accountable for project outcomes; provide funding and strategic direction | Executive sponsors, business owners |
| **Key Decision Makers** | Must approve scope, budget, or architectural decisions | VP Engineering, Product Director |
| **Active Contributors** | Directly participate in delivery | Developers, PMs, BAs, UX Researchers, Security |
| **Informed Parties** | Receive updates but are not actively involved in delivery | Department heads, legal, finance |
| **External Stakeholders** | Outside the organization but affected by the project | Customers, partners, auditors |

### Stakeholder Register Template

Maintain a stakeholder register updated at the start of each phase:

| Name | Role | Category | Communication Frequency | Preferred Channel | Key Interests / Concerns |
|---|---|---|---|---|---|
| | | | | | |

---

## Stakeholder Onboarding Checklist

Use this checklist when onboarding a new stakeholder to an active project.

### Before the Onboarding Meeting
- [ ] Prepare a project summary (one-pager or slide deck): scope, timeline, current status, key risks
- [ ] Grant access to relevant project documentation (wiki, project board, shared drive)
- [ ] Share the stakeholder register and communication plan so the new stakeholder understands the engagement model
- [ ] Identify the primary point of contact for the stakeholder's questions

### During the Onboarding Meeting
- [ ] Walk through project scope, goals, and success metrics
- [ ] Review the current project status and upcoming milestones
- [ ] Clarify the stakeholder's role and expected inputs (decisions, approvals, reviews)
- [ ] Review communication cadence (standups, status reports, steering committees)
- [ ] Establish escalation path and preferred communication channel
- [ ] Confirm any specific concerns or priorities the stakeholder brings

### After the Onboarding Meeting
- [ ] Send a meeting summary with key decisions and action items
- [ ] Add the stakeholder to appropriate mailing lists and communication channels
- [ ] Schedule the first recurring status touch-point
- [ ] Update the stakeholder register with notes from the onboarding discussion
- [ ] Follow up within one week to confirm the stakeholder has access to all needed materials

---

## Communication Cadence

| Meeting / Report | Frequency | Audience | Owner |
|---|---|---|---|
| Daily Standup | Daily | Core team | Project Manager |
| Weekly Delivery Sync | Weekly | Core team + PM lead | Project Manager |
| Stakeholder Status Report | Monthly (or bi-weekly for high-visibility projects) | All stakeholders | Project Manager |
| Steering Committee / Executive Briefing | Monthly or milestone-driven | Sponsors, Key Decision Makers | Project Manager + PM |
| Sprint Demo / Review | End of each sprint | All stakeholders (invited) | Project Manager |
| Ad-hoc Escalation | As needed | Relevant stakeholders | Project Manager |

---

## Monthly Status Report Template

Use this template to produce consistent, clear monthly status updates.

---

**Project Name:**
**Reporting Period:** [Month YYYY]
**Report Date:**
**Prepared by:** [Project Manager Name]

### Overall Status

| Dimension | Status | Summary |
|---|---|---|
| **Schedule** | 🟢 On Track / 🟡 At Risk / 🔴 Off Track | Brief note |
| **Scope** | 🟢 Stable / 🟡 Change Pending / 🔴 Significant Change | Brief note |
| **Budget** | 🟢 On Budget / 🟡 At Risk / 🔴 Over Budget | Brief note |
| **Quality** | 🟢 Acceptable / 🟡 Concerns / 🔴 Critical Issues | Brief note |
| **Risks** | 🟢 Managed / 🟡 Elevated / 🔴 Critical Risk Active | Brief note |

### Accomplishments This Period
- [Key deliverable or milestone completed]
- [Another significant achievement]

### Planned Activities Next Period
- [Upcoming deliverable or milestone]
- [Planned decisions or reviews needing stakeholder input]

### Key Risks & Issues

| Risk / Issue | Impact | Likelihood / Status | Mitigation / Resolution |
|---|---|---|---|
| | | | |

### Decisions Needed
List any decisions that require stakeholder input before the next reporting period:

| Decision | Context | Owner | Due Date |
|---|---|---|---|
| | | | |

### Metrics Snapshot

| Metric | Target | Actual | Trend |
|---|---|---|---|
| Velocity | | | |
| Open Bugs (P0/P1) | | | |
| Test Coverage | | | |
| [Custom metric] | | | |

---

## Escalation Decision Tree

Use this decision tree when determining whether and how to escalate an issue to stakeholders.

```
Is the issue impacting delivery (timeline, scope, or quality)?
├── NO → Monitor; document in risk register; no stakeholder escalation needed
└── YES → Continue ↓

Can the team resolve it within the current sprint without stakeholder input?
├── YES → Team-level triage; update risk register; note in next status report
└── NO → Continue ↓

Does resolution require a decision or resource outside the team's authority?
├── NO → Escalate to PM lead / Engineering lead for guidance
└── YES → Continue ↓

Is the impact limited to a single workstream or team?
├── YES → Escalate to relevant business owner or workstream sponsor
└── NO (cross-team or enterprise impact) → Escalate to Project Sponsor ↓

Does the issue involve regulatory, legal, data privacy, or security implications?
├── YES → Immediately loop in Information Security Manager and/or Legal
└── NO → Proceed with sponsor escalation
```

### Escalation Communication Guidelines
1. **Be specific**: State the issue, impact, decision needed, and recommended options.
2. **Be timely**: Escalate early—avoid waiting until the last moment.
3. **Document the escalation**: Log it in the risk register and note the outcome.
4. **Follow up**: Confirm the decision in writing (email or meeting notes).

### Escalation Template

> **Subject**: [ESCALATION] [Project Name] — [Brief Issue Description]
>
> **Issue**: [Clear description of the problem]
>
> **Impact**: [What will happen if not resolved, and by when]
>
> **Options Considered**:
> 1. [Option A] — pros/cons
> 2. [Option B] — pros/cons
>
> **Recommended Action**: [What you recommend and why]
>
> **Decision Needed By**: [Date]
>
> **Contact**: [Project Manager name and contact details]

---

## Managing Stakeholder Feedback

### Feedback Collection Points
- Sprint reviews and demos (encourage stakeholders to attend)
- Monthly status report response (provide a feedback mechanism such as a reply-to or form)
- Quarterly stakeholder surveys for long-running projects
- Ad-hoc feedback captured in a shared log

### Feedback Triage Process
1. **Log all feedback** in the project tracker or stakeholder feedback log.
2. **Classify by type**: scope request, quality concern, process suggestion, or informational.
3. **Assess impact**: Does this affect current scope, timeline, or quality?
4. **Route appropriately**:
   - Scope changes → Product Manager for backlog prioritization
   - Quality concerns → Tech lead and Dev team for triage
   - Process suggestions → Retrospective backlog for team discussion
   - Informational → Acknowledge and file

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
