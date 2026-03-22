# OctoAcme — Role Clarity Checklist

## Purpose
Use this checklist during project **Initiation** and **Kickoff** to confirm which personas are engaged, assign ownership for key responsibilities, and document escalation paths before execution begins.

Reference the full persona definitions in [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).

---

## 1. Confirm In-Scope Personas

Check each role that is actively assigned for this project:

| Persona | In Scope? | Assigned To | Notes |
|---|---|---|---|
| Product Manager (PdM) | ☐ Yes / ☐ No | | |
| Project Manager (PM) | ☐ Yes / ☐ No | | |
| Developer(s) | ☐ Yes / ☐ No | | |
| UX Designer | ☐ Yes / ☐ No | | |
| Business Analyst | ☐ Yes / ☐ No | | |
| DevOps Engineer | ☐ Yes / ☐ No | | |
| Scrum Master | ☐ Yes / ☐ No | | |
| Customer Success / Support | ☐ Yes / ☐ No | | |
| QA / Testing | ☐ Yes / ☐ No | | |
| Other: ____________ | ☐ Yes / ☐ No | | |

---

## 2. Define Ownership for Key Responsibilities

Assign a single **DRI (Directly Responsible Individual)** for each area. Leave blank if not applicable.

| Responsibility Area | DRI (Role / Name) | Notes |
|---|---|---|
| Risk management & risk register | | |
| Release planning & deployment approval | | |
| QA / acceptance testing sign-off | | |
| User research & UX validation | | |
| Stakeholder communications | | |
| Incident response lead | | |
| Backlog prioritization | | |
| Requirements documentation | | |
| CI/CD pipeline & environment health | | |
| Customer / support readiness | | |
| Retrospective facilitation | | |

---

## 3. Escalation Paths

Document how issues escalate when they cannot be resolved at the team level:

| Level | Trigger | Owner | Action |
|---|---|---|---|
| L1 — Team | Blocker identified in standup | Scrum Master / PM | Triage same day; resolve within sprint |
| L2 — Cross-team | Dependency blocked or risk materializes | PM | Escalate to dependent team lead; update risk register |
| L3 — Leadership | Business-impacting issue or scope change | PM + PdM | Notify Sponsor; schedule decision meeting within 24 h |
| L4 — Incident | Production impact detected | DevOps / On-call | Invoke incident playbook; notify Customer Success |

> **Customize** the table above for your project's team structure before kickoff.

---

## 4. Decision Owners

Record who has final say on common project decisions:

| Decision Type | Decision Owner | Consulted | Notes |
|---|---|---|---|
| Scope changes | PdM | PM, Sponsor | Requires updated one-pager for major changes |
| Release go/no-go | PM + PdM | DevOps, QA, CS | |
| Architecture / tech choices | Lead Developer | DevOps | |
| Budget / resource additions | PM | Sponsor | |
| UX design direction | PdM | UX Designer | |
| Incident response actions | DevOps / On-call | PM | |

---

## 5. Initiation & Kickoff Checklist

- [ ] All in-scope personas confirmed and assigned (Section 1)
- [ ] DRIs documented for all applicable responsibility areas (Section 2)
- [ ] Escalation paths reviewed and customized for this project (Section 3)
- [ ] Decision owners agreed and communicated to the team (Section 4)
- [ ] This checklist attached to the project repo under `docs/`
- [ ] Referenced in the Project One-pager (see [octoacme-project-initiation.md](octoacme-project-initiation.md))
- [ ] Shared with all stakeholders at or before kickoff meeting

---

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
