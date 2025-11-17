# OctoAcme Project Management Processes

## Purpose

This documentation provides centralized, accessible guidance for project management at OctoAcme. The process docs collected here are based on proven OctoAcme practices and serve as a reference for:

- **Onboarding new team members** to understand how projects are run
- **Repeatable delivery** through consistent practices and shared understanding
- **Continuous improvement** by capturing learnings and refining our approach

Whether you're a new team member, stakeholder, or contributor, these guides help you quickly understand our high-level approach and where to find detailed guidance for each phase of project delivery.

---

## OctoAcme Project Lifecycle

Our project management approach follows five key phases, each with defined roles, activities, and deliverables:

### 1. **Initiation**

**Purpose:** Validate and authorize work, align stakeholders, and create a lightweight plan.

**Key Activities:**
- Confirm business need and define measurable outcomes
- Identify stakeholders and champions
- Create a Project One-pager (problem, goal, success metrics)
- Establish initial timeline and resource needs
- Make go/no-go decision for planning

**Key Roles:**
- **Project Manager (PM):** Coordinates delivery activities, schedules, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes work, and measures success
- **Stakeholders:** Provide inputs, approvals, and business context (Business Sponsors, Support, Sales)
- **UX Designer:** Provide initial design concepts if applicable
- **Data Analyst:** Help define measurable success criteria and baseline metrics

📄 **Detailed Guide:** [Project Initiation](./octoacme-project-initiation.md)

---

### 2. **Planning**

**Purpose:** Turn an approved initiative into an actionable plan and backlog for delivery.

**Key Activities:**
- Conduct project kickoff with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Estimate scope and define Definition of Done
- Identify dependencies, risks, and integration points
- Create release plan and milestone map

**Key Roles:**
- **Project Manager (PM):** Manages timelines, dependencies, and risk register
- **Product Manager (PdM):** Prioritizes backlog and defines acceptance criteria
- **Developers:** Assist in estimating work and identifying technical risks
- **QA/Testing:** Draft initial test plans and quality approach
- **UX Designer:** Provide design specifications and validate acceptance criteria for UX features
- **Data Analyst:** Help define measurable success metrics and KPIs
- **Scrum Master/Delivery Lead:** Facilitate sprint planning and ensure backlog is ready

📄 **Detailed Guides:** 
- [Project Planning](./octoacme-project-planning.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)

---

### 3. **Execution & Tracking**

**Purpose:** Manage day-to-day execution and track progress toward project milestones.

**Key Activities:**
- Daily standups focused on progress, blockers, and dependencies
- Weekly delivery syncs and demos
- Use project boards to track work (Backlog → Ready → In Progress → Review → QA → Done)
- Pull Request workflow with automated tests and code reviews
- Monitor velocity, burndown, and success metrics

**Key Roles:**
- **Developers:** Implement features, write tests, participate in code reviews
- **Project Manager (PM):** Tracks progress, manages risks, coordinates cross-team dependencies
- **QA/Testing:** Validates quality and acceptance criteria
- **Product Manager (PdM):** Reviews progress against success metrics
- **UX Designer:** Validate implemented designs match specifications
- **Data Analyst:** Monitor and report on success metrics and KPIs
- **Scrum Master/Delivery Lead:** Facilitate standups, remove blockers, track velocity

📄 **Detailed Guide:** [Execution & Tracking](./octoacme-execution-and-tracking.md)

---

### 4. **Release & Deployment**

**Purpose:** Standardize releases to production to reduce risk and improve observability.

**Key Activities:**
- Ensure all acceptance criteria met and PRs merged
- Run CI, security scans, and smoke tests
- Draft release notes and rollback plan
- Deploy to staging, then production
- Post-deployment verification and stakeholder announcement

**Key Roles:**
- **Developers:** Support deployment and post-release verification
- **Project Manager (PM):** Coordinates release timeline and communications
- **QA/Testing:** Runs smoke tests and validates deployment
- **Product Manager (PdM):** Reviews release impact and metrics
- **Data Analyst:** Set up monitoring for success metrics and prepare post-launch dashboards
- **Support Team (Stakeholder):** Prepared with release notes and support documentation

📄 **Detailed Guide:** [Release & Deployment](./octoacme-release-and-deployment.md)

---

### 5. **Retrospective & Continuous Improvement**

**Purpose:** Capture learnings and convert them into actionable improvements.

**Key Activities:**
- Conduct retrospectives after sprints, releases, or important milestones
- Identify what went well and what could be improved
- Define 2–3 prioritized action items with owners and due dates
- Track improvement actions in backlog and review in weekly syncs
- Measure impact of improvements and celebrate wins

**Key Roles:**
- **All Team Members:** Contribute feedback and implement improvements
- **Project Manager (PM):** Facilitates retrospectives and tracks action items
- **Product Manager (PdM):** Measures impact and incorporates learnings into roadmap
- **Scrum Master/Delivery Lead:** Leads retrospective facilitation and coaches on continuous improvement

📄 **Detailed Guide:** [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

## Core Principles

Our approach is built on these guiding principles:

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named PM and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

---

## Key Roles at OctoAcme

Understanding roles and responsibilities helps teams collaborate effectively:

- **Project Manager (PM):** Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, and measures success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validate quality and acceptance criteria
- **UX Designer:** Designs user experiences, conducts research, ensures usability and accessibility
- **Data Analyst:** Measures success metrics, provides insights, informs data-driven decisions
- **Scrum Master/Delivery Lead:** Facilitates agile practices, removes blockers, coaches teams
- **Stakeholders:** Provide inputs, approvals, and business context (includes Business Sponsors, Support, Sales, and End Users)

📄 **Detailed Guide:** [Roles & Personas](./octoacme-roles-and-personas.md)

---

## How to Use These Process Docs

### For New Team Members
- Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach
- Review the [Roles & Personas](./octoacme-roles-and-personas.md) guide to understand responsibilities
- Use phase-specific guides as you engage in each lifecycle stage

### For Active Projects
- Keep your Project Charter updated in the project repository
- Reference phase-specific checklists to ensure completeness
- Add project-specific process docs to `.copilot/` to provide context for Copilot Spaces

### For Process Improvements
- Use retrospectives to identify improvement opportunities
- Update these process docs as practices evolve
- Share learnings with the broader team to scale institutional knowledge

---

## Additional Resources

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level principles, scope, and artifacts
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks
- [Role Onboarding Checklist](./role-onboarding-checklist.md) — Structured onboarding guide for all roles
- [Collaboration & Handoff Guide](./collaboration-and-handoff-guide.md) — Clear ownership and collaboration patterns between roles

---

## Questions or Feedback?

These process docs are living documents. If you have suggestions for improvements or questions about how to apply these practices, please reach out to your Project Manager or contribute updates through a pull request.
