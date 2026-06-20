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

## Engineering Manager

### Role Summary
Engineering Managers ensure the team has the capacity, focus, and support needed to deliver reliably. They bridge technical execution and organizational priorities.

### Responsibilities
- Own staffing, capacity planning, and team health
- Provide technical delivery oversight and execution coaching
- Act as escalation support for blockers and impediments
- Align team goals with product and organizational objectives

### Goals
- Sustain predictable delivery and healthy team dynamics
- Reduce unplanned churn from capacity and priority shifts
- Support career growth and technical excellence across the team

### Typical Communication
- Weekly 1:1s with direct reports and PM
- Capacity and risk updates to leadership
- Escalation calls when delivery is at risk

### Collaboration & Handoffs
- **Project Manager:** aligns on timeline, resourcing, and risk escalation paths
- **Product Manager:** negotiates scope trade-offs when capacity is constrained
- **Developers:** provides execution support, removes blockers, reviews workload
- **QA:** sets quality goals and supports prioritization of defect resolution
- **Tech Lead / Architect:** co-owns technical health and architectural decisions

---

## Tech Lead / Architect

### Role Summary
Tech Leads and Architects guide the technical direction of projects, ensuring solutions are scalable, maintainable, and meet non-functional requirements.

### Responsibilities
- Define and maintain architectural patterns and design standards
- Review technical designs and ensure quality and consistency
- Identify and manage technical risks and dependencies
- Guide developers on implementation approach and best practices

### Goals
- Deliver technically sound, scalable solutions
- Minimize technical debt and architecture drift
- Maintain high code quality and non-functional reliability

### Typical Communication
- Architecture decision records (ADRs) and design docs
- PR reviews and technical feedback
- Pairing sessions and design discussions with developers

### Collaboration & Handoffs
- **Developers:** provides design/code guidance, reviews PRs, unblocks technical questions
- **Product Manager:** validates technical feasibility and surfaces trade-offs early
- **Project Manager:** communicates technical dependencies and risk to project timeline
- **Security Engineer:** co-owns security architecture and threat model reviews
- **DevOps / SRE:** collaborates on deployment architecture and reliability patterns

---

## UX/UI Designer

### Role Summary
UX/UI Designers ensure that product experiences are usable, consistent, and aligned with user needs. They produce design artifacts that guide implementation and acceptance validation.

### Responsibilities
- Define user flows, interaction patterns, and visual design
- Facilitate usability testing and incorporate feedback
- Produce design specs and assets for developer handoff
- Maintain a consistent design system and component library

### Goals
- Deliver intuitive, accessible, and high-quality user experiences
- Reduce rework caused by late-stage UX changes
- Ensure developer implementations match design intent

### Typical Communication
- Design reviews and critique sessions
- Annotated mockups and prototypes shared via design tools
- Handoff notes in tickets or linked design files

### Collaboration & Handoffs
- **Product Manager:** aligns on problem framing, user research, and acceptance criteria for UX
- **Developers:** provides implementation-ready specs; reviews built UI for fidelity
- **QA:** supplies UX acceptance criteria and validates visual/interaction correctness
- **Project Manager:** flags design blockers or scope changes affecting timeline

---

## DevOps / SRE

### Role Summary
DevOps and SRE engineers maintain the reliability, security, and efficiency of build, deploy, and operating infrastructure. They enable the team to ship quickly and safely.

### Responsibilities
- Design and operate CI/CD pipelines and deployment automation
- Define and enforce observability standards (logging, metrics, alerting)
- Maintain rollback procedures and incident readiness runbooks
- Optimize infrastructure reliability, performance, and cost

### Goals
- Achieve high deployment frequency with low change failure rate
- Minimize mean time to recovery (MTTR) for incidents
- Enable self-service deployment capabilities for the delivery team

### Typical Communication
- Deployment and release readiness sign-offs
- On-call handoffs and incident postmortems
- Infrastructure change proposals and runbook updates

### Collaboration & Handoffs
- **Developers:** partners on pipeline configuration, build requirements, and deployment scripts
- **Project Manager:** confirms release readiness; communicates deployment windows and risks
- **Product Manager:** aligns on reliability expectations, SLAs, and operational constraints
- **Tech Lead / Architect:** collaborates on deployment architecture and infrastructure design
- **Release Manager:** coordinates deployment execution and go/no-go criteria

---

## Security Engineer / Compliance Lead

### Role Summary
Security Engineers and Compliance Leads ensure that product and infrastructure changes meet security, privacy, and regulatory requirements throughout the project lifecycle.

### Responsibilities
- Conduct threat modeling and risk assessments for new features
- Define and enforce secure development controls and standards
- Manage compliance checkpoints and audit requirements
- Coordinate security incident response and remediation

### Goals
- Reduce security risk exposure throughout the delivery cycle
- Ensure regulatory and compliance obligations are met before release
- Build a security-aware engineering culture

### Typical Communication
- Security review sign-offs in release checklists
- Vulnerability and compliance reports to stakeholders
- Incident alerts and remediation tracking

### Collaboration & Handoffs
- **Tech Lead / Architect:** co-reviews security architecture, threat models, and design decisions
- **Developers:** provides secure coding guidance and reviews security-sensitive changes
- **Project Manager:** escalates security risks; feeds into risk register and release gates
- **Stakeholders:** delivers compliance status reporting and audit evidence
- **DevOps / SRE:** coordinates on infrastructure security controls and incident response

---

## Customer Support / Success Representative

### Role Summary
Customer Support and Success Representatives surface real-world user pain points, adoption blockers, and escalation trends back into the product and delivery process.

### Responsibilities
- Collect and synthesize user issues and escalation patterns
- Provide release impact feedback from user-facing perspective
- Identify adoption blockers and usability gaps in shipped features
- Coordinate with internal teams on customer-impacting incidents

### Goals
- Reduce recurring support volume through proactive product improvements
- Ensure customers are informed and enabled during and after releases
- Drive accountability for user experience quality post-launch

### Typical Communication
- Support trend summaries and escalation reports
- Release readiness input during pre-release reviews
- Post-release feedback shared with Product Manager and PM

### Collaboration & Handoffs
- **Product Manager:** provides prioritization input based on support volume and user feedback
- **Project Manager:** informs communication planning for customer-impacting changes
- **Developers:** supplies defect context and reproduction scenarios
- **QA:** contributes real-world reproduction steps and user-reported edge cases
- **Release Manager:** aligns on customer communication timing and content

---

## Data Analyst / BI Analyst

### Role Summary
Data Analysts and BI Analysts define, track, and interpret the metrics that determine whether projects and features are achieving their intended outcomes.

### Responsibilities
- Define success metrics and KPIs in collaboration with Product Manager
- Build and maintain reporting views, dashboards, and data pipelines
- Analyze feature impact and operational performance trends
- Surface data-driven insights to inform prioritization decisions

### Goals
- Enable data-informed decision-making across product and delivery
- Ensure instrumentation is in place before features ship
- Provide timely reporting on project and product health

### Typical Communication
- Metrics definitions shared early in planning
- Dashboard and report updates at sprint or milestone cadence
- Ad-hoc analysis requests for decisions or escalations

### Collaboration & Handoffs
- **Product Manager:** aligns on outcome metrics and interprets results to drive backlog decisions
- **Project Manager:** provides status metrics and progress indicators for reporting
- **Developers:** communicates instrumentation and data collection requirements pre-implementation
- **Tech Lead / Architect:** validates data model and analytics infrastructure design

---

## Release Manager

### Role Summary
Release Managers coordinate the end-to-end release process, ensuring all stakeholders are aligned, readiness criteria are met, and releases proceed safely and on schedule.

### Responsibilities
- Define and enforce go/no-go criteria for each release
- Coordinate release readiness across engineering, QA, DevOps, and support
- Maintain the release calendar and communicate schedules
- Own release communication and post-release verification steps

### Goals
- Deliver releases predictably with minimal disruption
- Ensure all release gates are validated before deployment
- Maintain clear accountability for release outcomes

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Release calendar updates shared with all stakeholders
- Post-release announcements and incident summaries if needed

### Collaboration & Handoffs
- **Project Manager:** aligns release schedule with project milestones and dependencies
- **DevOps / SRE:** confirms deployment execution, rollback readiness, and observability coverage
- **QA:** validates acceptance criteria and sign-off before release gate
- **Product Manager:** confirms feature completeness and stakeholder communication readiness
- **Customer Support / Success:** coordinates timing and content of customer-facing communications
- **Security Engineer:** confirms security review completion and any outstanding risk acceptance

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Cross-Functional Collaboration](./octoacme-cross-functional-collaboration.md) for the role interaction matrix.
- See [Role Handoff Checklist](./octoacme-role-handoff-checklist.md) for a reusable handoff template.

