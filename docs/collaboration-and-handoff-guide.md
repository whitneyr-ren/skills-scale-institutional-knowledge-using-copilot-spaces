# OctoAcme Collaboration & Handoff Guide

## Purpose
This guide clarifies collaboration patterns and handoff points between roles to reduce confusion, improve accountability, and ensure smooth workflows. It addresses the ownership gaps identified in issue #4.

---

## Cross-Role Collaboration Patterns

### Product Manager ↔ UX Designer

**When:** Feature planning, design reviews, user research  
**Collaboration Pattern:**
- PdM shares user needs, business goals, and success metrics
- UX Designer conducts research and creates design concepts
- Joint review sessions to align on solution approach
- UX Designer validates designs through user testing
- PdM provides feedback on business viability

**Key Handoffs:**
- PdM → UX: Problem statement, user stories, success criteria
- UX → PdM: Research findings, design mockups, usability test results

**Artifacts:**
- User research reports
- Design specifications with acceptance criteria
- Usability test feedback

---

### UX Designer ↔ Developers

**When:** Design handoff, implementation, design refinement  
**Collaboration Pattern:**
- UX Designer provides detailed design specs and assets
- Developers ask clarifying questions on feasibility
- Regular check-ins during implementation
- UX Designer reviews implemented features
- Joint problem-solving on design/technical trade-offs

**Key Handoffs:**
- UX → Developers: Design mockups, specifications, assets, accessibility requirements
- Developers → UX: Implementation for review, technical constraints

**Artifacts:**
- Design handoff documentation (Figma, Sketch, etc.)
- Component specifications
- Accessibility checklist

**Common Pitfalls:**
- Unclear design specifications → Schedule design review before dev starts
- Late design changes → Involve UX early in technical planning
- Design not matching implementation → Regular check-ins during development

---

### Product Manager ↔ Data Analyst

**When:** Planning metrics, A/B testing, performance reviews  
**Collaboration Pattern:**
- PdM defines business questions and success metrics
- Data Analyst designs measurement approach
- Joint definition of KPIs and targets
- Regular metric reviews and insights sharing
- Data-informed roadmap prioritization

**Key Handoffs:**
- PdM → Data: Success metrics, experiment hypotheses, business questions
- Data → PdM: Dashboards, insights, experiment results, recommendations

**Artifacts:**
- KPI definitions and targets
- Experiment plans and results
- Metric dashboards
- Data insights presentations

---

### Developers ↔ QA/Testing

**When:** Feature development, testing, bug resolution  
**Collaboration Pattern:**
- Developers share acceptance criteria and implementation approach
- QA creates test plans based on requirements
- Developers write unit tests; QA conducts integration/E2E testing
- QA reports bugs with clear reproduction steps
- Joint triage on priority and severity
- Developers fix bugs; QA verifies fixes

**Key Handoffs:**
- Developers → QA: Completed features, test environments, acceptance criteria
- QA → Developers: Bug reports, test results, edge cases

**Artifacts:**
- Test plans and test cases
- Bug reports with reproduction steps
- Test results and coverage reports

**Common Pitfalls:**
- Unclear acceptance criteria → Review criteria together during planning
- Late testing → Involve QA in planning and enable parallel testing
- Repeated bugs → Improve automated test coverage

---

### Project Manager ↔ Scrum Master/Delivery Lead

**When:** Planning, execution, dependency management  
**Collaboration Pattern:**
- PM owns overall project timeline and external dependencies
- Scrum Master owns sprint execution and team health
- Joint planning on capacity and commitments
- Scrum Master escalates team blockers to PM
- PM provides context on strategic dependencies
- Coordinated facilitation of ceremonies

**Key Handoffs:**
- PM → Scrum Master: Project priorities, external dependencies, resource constraints
- Scrum Master → PM: Team velocity, blockers, process improvements

**Artifacts:**
- Project timeline and milestones
- Sprint plans and velocity tracking
- Blocker and dependency logs

**Division of Responsibility:**
- **PM:** External stakeholder management, cross-team dependencies, budget, timeline
- **Scrum Master:** Team facilitation, agile coaching, removing team-level blockers

---

### Product Manager ↔ Stakeholders

**When:** Planning, approvals, status updates, launch  
**Collaboration Pattern:**
- PdM shares product vision and roadmap
- Stakeholders provide business context and approvals
- Regular status updates at appropriate cadence
- Stakeholder feedback incorporated into prioritization
- Go/no-go decisions at key milestones

**Key Handoffs by Stakeholder Type:**

**Business Sponsor:**
- PdM → Sponsor: Business case, ROI projections, milestone updates
- Sponsor → PdM: Strategic direction, budget approvals, escalation support

**Support Team:**
- PdM → Support: Release notes, feature documentation, training materials
- Support → PdM: Customer pain points, support volume trends, feature requests

**Sales Team:**
- PdM → Sales: Feature roadmap, competitive positioning, demo assets
- Sales → PdM: Customer feedback, market requirements, win/loss insights

**Artifacts:**
- Stakeholder communication plans
- Status reports and milestone reviews
- Decision logs
- Release announcements

---

## Critical Handoff Points in Project Lifecycle

### 1. Initiation → Planning
**Who:** Product Manager, Project Manager, Stakeholders  
**Handoff:** Approved project charter, initial requirements  
**Checklist:**
- [ ] Business case and success metrics defined
- [ ] Stakeholder alignment achieved
- [ ] Resource availability confirmed
- [ ] Go/no-go decision documented

---

### 2. Planning → Execution
**Who:** Project Manager, Product Manager, Scrum Master, Developers, UX, QA  
**Handoff:** Prioritized backlog, sprint plan, designs  
**Checklist:**
- [ ] Backlog items have clear acceptance criteria
- [ ] Designs are complete and reviewed
- [ ] Test strategy defined
- [ ] Definition of Done agreed upon
- [ ] Dependencies identified and communicated

---

### 3. Design → Development
**Who:** UX Designer, Developers  
**Handoff:** Design specifications, assets, prototypes  
**Checklist:**
- [ ] Design mockups finalized and approved
- [ ] Component specifications documented
- [ ] Assets exported and organized
- [ ] Accessibility requirements specified
- [ ] Responsive behavior defined
- [ ] Edge cases and error states designed

---

### 4. Development → QA
**Who:** Developers, QA/Testing  
**Handoff:** Completed features in test environment  
**Checklist:**
- [ ] All acceptance criteria met
- [ ] Unit tests written and passing
- [ ] Test environment available and stable
- [ ] Test data prepared (if needed)
- [ ] Known limitations documented

---

### 5. QA → Release
**Who:** QA, Project Manager, Product Manager, Developers  
**Handoff:** Validated release candidate  
**Checklist:**
- [ ] All critical and high-priority bugs resolved
- [ ] Smoke tests passed
- [ ] Regression testing completed
- [ ] Release notes prepared
- [ ] Rollback plan documented
- [ ] Support team briefed

---

### 6. Release → Post-Launch
**Who:** Product Manager, Data Analyst, Support, Developers  
**Handoff:** Live feature with monitoring  
**Checklist:**
- [ ] Success metrics being tracked
- [ ] Monitoring and alerts configured
- [ ] Support documentation published
- [ ] Stakeholders notified
- [ ] Post-launch review scheduled

---

## Ownership Matrix

Use this matrix to clarify "Who owns what" at each stage:

| Activity | Owner | Collaborators | Informed |
|----------|-------|---------------|----------|
| Define product vision | Product Manager | UX Designer, Data Analyst | Stakeholders, PM |
| User research | UX Designer | Product Manager | Developers, PM |
| Create roadmap | Product Manager | Project Manager | Stakeholders, Team |
| Design features | UX Designer | Product Manager, Developers | QA, PM |
| Define success metrics | Product Manager | Data Analyst | PM, Stakeholders |
| Create project plan | Project Manager | Product Manager, Scrum Master | Team, Stakeholders |
| Develop features | Developers | UX Designer, QA | PM, PdM |
| Facilitate sprints | Scrum Master | Project Manager | Team |
| Test features | QA/Testing | Developers | PM, PdM |
| Analyze metrics | Data Analyst | Product Manager | PM, Stakeholders |
| Manage risks | Project Manager | All roles | Stakeholders |
| Make go/no-go decisions | Business Sponsor | Product Manager, PM | Team |
| Support customers | Support Team | All roles | — |

---

## Escalation Paths

### For Team-Level Issues
**Primary:** Scrum Master → Project Manager → Product Manager

### For Technical Blockers
**Primary:** Developer → Tech Lead → Project Manager

### For Product Decisions
**Primary:** Any role → Product Manager → Business Sponsor (if needed)

### For Quality Issues
**Primary:** QA → Developers → Project Manager (for timeline impact)

### For Strategic Changes
**Primary:** Product Manager → Business Sponsor → Stakeholders

---

## Tips for Effective Collaboration

1. **Over-communicate handoffs:** Don't assume the next person knows the work is ready
2. **Use consistent artifacts:** Standard templates reduce confusion
3. **Document decisions:** Keep a decision log for future reference
4. **Regular syncs:** Don't wait for formal ceremonies to collaborate
5. **Feedback loops:** Build in reviews at each handoff point
6. **Shared visibility:** Use project boards to show status across roles
7. **Celebrate handoffs:** Acknowledge when work moves smoothly between roles

---

## Common Collaboration Anti-Patterns

❌ **Throwing work over the wall:** No communication during handoff  
✅ **Better:** Schedule handoff meeting, provide context, answer questions

❌ **Unclear ownership:** Multiple people think they own the same work  
✅ **Better:** Use the ownership matrix, clarify in kickoff

❌ **Last-minute surprises:** Blockers not communicated until deadline  
✅ **Better:** Daily standup updates, proactive escalation

❌ **Skipping reviews:** Assuming work is correct without validation  
✅ **Better:** Build review points into workflow

---

## Continuous Improvement

This guide should evolve based on team experience:
- Capture handoff issues in retrospectives
- Update this guide with learnings
- Add role-specific collaboration patterns as needed
- Share successes to reinforce good practices

---

## Reference
Based on personas and responsibilities defined in [Roles & Personas](./octoacme-roles-and-personas.md) and process improvements identified in issue #4.
