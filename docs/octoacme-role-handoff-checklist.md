# OctoAcme — Role Handoff Checklist Template

## Purpose
Provide a reusable checklist to ensure clean, accountable handoffs between roles during planning, execution, and release phases.

Copy and fill in this template for each major handoff or phase transition in a project.

---

## Handoff Details

- **Handoff from:** `[Role]`
- **Handoff to:** `[Role]`
- **Project / Feature:** `[Name]`
- **Date:** `[YYYY-MM-DD]`
- **Phase transition:** `[ ] Planning → Execution` `[ ] Execution → Release` `[ ] Release → Post-Release`

---

## Planning → Execution Handoff

### Product Manager → Development Team
- [ ] Problem statement and user stories are defined and accepted
- [ ] Acceptance criteria are documented for each story in scope
- [ ] Success metrics are defined and data collection requirements are shared with Data Analyst
- [ ] Prioritized backlog is finalized for the sprint or milestone
- [ ] Open questions or dependencies are documented and assigned

### UX/UI Designer → Developers
- [ ] Final design files are shared with developer-ready annotations
- [ ] Component specifications and interaction states are documented
- [ ] Edge cases and error states are included in designs
- [ ] Design has been reviewed and approved by Product Manager
- [ ] Handoff meeting or walkthrough completed with lead developer

### Data Analyst → Developers
- [ ] Instrumentation and event tracking requirements are documented
- [ ] Metric definitions and KPIs are agreed upon with Product Manager
- [ ] Data schema or event contract reviewed with Tech Lead

### Security Engineer → Development Team
- [ ] Threat model or security review completed for new features
- [ ] Secure coding requirements communicated to Tech Lead and Developers
- [ ] Compliance requirements documented and tracked in project plan

---

## Execution → Release Handoff

### Developers → QA
- [ ] Feature branch is in a stable, testable state
- [ ] Unit and integration tests are passing in CI
- [ ] Known limitations or deferred items are documented in the ticket
- [ ] Test environment is configured and accessible
- [ ] Acceptance criteria have been reviewed and are unchanged

### QA → Release Manager
- [ ] All acceptance criteria tested and verified
- [ ] Regression test suite completed with results documented
- [ ] Open defects triaged with severity ratings and go/no-go recommendation
- [ ] Performance or load testing completed (if applicable)
- [ ] UX acceptance validated with UX/UI Designer (if applicable)

### Security Engineer → Release Manager
- [ ] Security review sign-off completed or formal risk acceptance documented
- [ ] Vulnerability scan results reviewed and critical/high items resolved
- [ ] Compliance checkpoints cleared or exceptions approved

### DevOps / SRE → Release Manager
- [ ] Deployment runbook updated for this release
- [ ] Rollback procedure tested and documented
- [ ] Observability coverage verified (logs, metrics, alerts in place)
- [ ] Deployment window confirmed and change request approved (if required)
- [ ] Staging deployment completed and smoke tests passed

---

## Release → Post-Release Handoff

### Release Manager → Customer Support / Success
- [ ] Release notes and change summary shared before go-live
- [ ] Known issues and workarounds documented
- [ ] Customer communication drafted and approved
- [ ] Support team briefed on new features, impacts, and FAQs

### Release Manager → DevOps / SRE
- [ ] Post-deploy verification steps confirmed
- [ ] On-call team notified of release and any elevated monitoring needs
- [ ] Rollback criteria defined and on-call team aware

### Data Analyst → Product Manager
- [ ] Post-release metrics baseline documented
- [ ] Dashboard or reporting views ready for post-launch analysis
- [ ] Follow-up analysis schedule agreed (e.g., review after 1 week / 1 sprint)

### Project Manager → All Stakeholders
- [ ] Release announcement sent to relevant stakeholder groups
- [ ] Project status updated to reflect release completion
- [ ] Retrospective scheduled within one sprint of release

---

## Handoff Sign-Off

| Role | Name | Sign-Off | Date |
|---|---|---|---|
| Handing off | | `[ ] Confirmed` | |
| Receiving | | `[ ] Confirmed` | |
| Project Manager | | `[ ] Confirmed` | |

---

## Notes / Open Items

> Record any open items, dependencies, or exceptions here. Assign an owner and target resolution date for each.

- [ ] Item: `[description]` — Owner: `[role/name]` — Due: `[date]`
