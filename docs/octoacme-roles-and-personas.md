# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX Designer

### Role Summary
UX Designers shape the user experience by translating business requirements and user research into intuitive interfaces and interaction flows. They collaborate closely with Product Managers and Developers to ensure the product is both usable and desirable.

### Responsibilities
- Conduct user research and usability studies to validate design decisions
- Create wireframes, prototypes, and high-fidelity designs
- Define and maintain UX standards, patterns, and component guidelines
- Provide design feedback during feature acceptance and QA cycles
- Collaborate with Product Managers to prioritize experience improvements
- Ensure accessibility and inclusive design standards are met

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce user friction and support self-service adoption
- Bridge business intent and technical feasibility through human-centered design

### Typical Communication
- Design reviews and prototype walkthroughs with PdM and Developers
- Usability test reports shared with Product Managers and stakeholders
- Annotations and design specs linked from backlog items

### Interactions
| Lifecycle Phase | Collaboration |
|---|---|
| Initiation | Aligns with PdM on user needs and problem framing; contributes to one-pager UX considerations |
| Planning | Provides wireframes and prototypes to inform backlog sizing; reviews acceptance criteria for UX completeness |
| Execution | Participates in design reviews and demos; answers design questions from Developers |
| Release | Validates UI against design specs in staging; provides input for release notes and user-facing docs |
| Retrospective | Shares user feedback signals; proposes UX improvements for future iterations |

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between stakeholder intent and technical delivery. They elicit, document, and validate requirements to ensure the team builds the right solution for the right business need.

### Responsibilities
- Elicit and document business requirements through interviews, workshops, and process review
- Translate stakeholder needs into actionable user stories and acceptance criteria
- Identify and resolve ambiguities in requirements before development begins
- Validate delivered solutions against original business objectives
- Maintain a traceability matrix from requirements to delivery artifacts

### Goals
- Ensure requirements are clear, complete, and testable before development starts
- Reduce rework caused by misunderstood or missing requirements
- Strengthen communication between business stakeholders and technical teams

### Typical Communication
- Requirements workshops and walkthrough sessions with stakeholders and PdM
- Written user stories and acceptance criteria in the backlog
- Change request documentation and impact assessments

### Interactions
| Lifecycle Phase | Collaboration |
|---|---|
| Initiation | Supports PdM and PM in defining scope and documenting stakeholder needs for the one-pager |
| Planning | Refines epics into user stories with clear acceptance criteria; works with Developers to size and validate feasibility |
| Execution | Clarifies requirements on demand; reviews in-progress work for requirements alignment |
| Release | Validates release against original business requirements; participates in UAT coordination |
| Retrospective | Reviews requirement quality and traceability; identifies process improvements for elicitation |

---

## DevOps Engineer

### Role Summary
DevOps Engineers own the infrastructure, build pipelines, and deployment automation that enable reliable, repeatable delivery. They serve as the connective tissue between Development and Operations, ensuring code can move safely from development to production.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and automation tooling
- Manage infrastructure as code (IaC), environments, and cloud configuration
- Monitor system health, performance, and security posture; respond to alerts
- Support incident response, root cause analysis, and post-incident reviews
- Enforce deployment gates such as security scans, performance checks, and approvals
- Collaborate with Developers on build, test, and deployment best practices

### Goals
- Maximize deployment frequency while minimizing lead time and change failure rate
- Maintain high availability and observability for all production systems
- Reduce manual toil through automation and self-service tooling

### Typical Communication
- Infrastructure and pipeline documentation in the repo (`.github/`, IaC directories)
- Runbooks and incident response playbooks in `docs/`
- Deployment status and incident updates in team channels and status reports

### Interactions
| Lifecycle Phase | Collaboration |
|---|---|
| Initiation | Advises on infrastructure feasibility, environment needs, and tooling costs |
| Planning | Defines deployment architecture and environment strategy; contributes to the risk register for infra risks |
| Execution | Maintains CI pipelines; unblocks build and environment issues; reviews PRs touching infra code |
| Release | Executes or oversees production deployments; runs smoke tests; holds rollback authority |
| Retrospective | Reviews deployment metrics and incident data; drives reliability improvements |

---

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile ceremonies, protect team focus, and continuously improve the team's ways of working. They are servant leaders who remove blockers and help the team operate at a sustainable, predictable pace.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and remove impediments that slow delivery
- Coach the team and stakeholders on Agile values, principles, and practices
- Track sprint health metrics (velocity, burndown, blocker trends) and share transparently
- Shield the team from unplanned interruptions and scope creep
- Collaborate with PM and PdM to maintain a healthy, prioritized backlog

### Goals
- Enable the team to deliver consistently and predictably sprint over sprint
- Foster a culture of continuous improvement and psychological safety
- Improve cross-functional alignment and reduce process friction

### Typical Communication
- Sprint reports and burndown charts shared with PM and stakeholders
- Impediment logs and escalation notes
- Retrospective action items documented and tracked

### Interactions
| Lifecycle Phase | Collaboration |
|---|---|
| Initiation | Advises on team capacity and delivery model for the project one-pager |
| Planning | Co-facilitates kickoff; ensures backlog is well-groomed and sprint capacity is set |
| Execution | Runs daily standups and sprint ceremonies; escalates blockers to PM; tracks velocity |
| Release | Coordinates release readiness within the sprint; surfaces risks to PM and PdM |
| Retrospective | Leads retrospective sessions; owns action item follow-through |

---

## Customer Success / Support

### Role Summary
Customer Success and Support professionals serve as the voice of the customer within the project team. They translate user feedback and support signals into actionable insights, review releases for customer impact, and ensure the team ships changes that help rather than harm users.

### Responsibilities
- Monitor support queues and aggregate user feedback; surface trends to PdM and PM
- Review upcoming releases for customer impact and communicate changes to users
- Maintain and improve customer-facing support documentation and FAQs
- Participate in release readiness reviews to assess support readiness
- Act as first escalation point for customer-reported incidents; engage engineering as needed
- Contribute customer context to retrospectives to inform prioritization

### Goals
- Maximize customer satisfaction and reduce support ticket volume through proactive communication
- Ensure every release is accompanied by clear user-facing documentation and support preparation
- Close the feedback loop between users and the development team

### Typical Communication
- Weekly feedback digest shared with PdM and PM
- Release communication drafts and customer-facing changelogs
- Incident reports and escalation tickets when user-impacting issues arise

### Interactions
| Lifecycle Phase | Collaboration |
|---|---|
| Initiation | Provides customer pain point data and user research to inform the problem statement |
| Planning | Reviews proposed features for support complexity; flags training or documentation needs |
| Execution | Collaborates with Developers on bug triage; drafts support content for upcoming features |
| Release | Signs off on support readiness; prepares customer communication; reviews release notes |
| Retrospective | Brings customer satisfaction data and support ticket trends to the retrospective |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See the [Role Clarity Checklist](octoacme-role-clarity-checklist.md) to confirm which personas are in-scope for a given project during Initiation.

