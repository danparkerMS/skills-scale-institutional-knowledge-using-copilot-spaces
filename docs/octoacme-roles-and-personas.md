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

## QA / Testing

### Role Summary
QA/Testing engineers validate quality, acceptance criteria, and functional correctness before release. They act as the last line of defense before software reaches production.

### Responsibilities
- Write and execute test plans, test cases, and exploratory tests
- Validate acceptance criteria defined by Product Manager and Business Analyst
- File and triage defects with clear reproduction steps
- Coordinate with Developers to resolve issues and re-test fixes
- Run end-to-end smoke tests prior to release

### Goals
- Ensure delivered software meets acceptance criteria and quality standards
- Catch regressions early and reduce post-release defects
- Maintain comprehensive test coverage across critical flows

### Typical Communication
- Sprint planning and backlog refinement sessions
- Defect reports and test summary emails
- Handoff notes during release readiness reviews

### Key Interactions
- **Project Manager:** Reports test status, flags blockers affecting release timelines
- **Product Manager / Business Analyst:** Clarifies acceptance criteria and edge cases
- **Developers:** Collaborates on defect triage and fix verification
- **Security Lead:** Coordinates security test results and vulnerability triage
- **Stakeholder Sponsor:** Contributes to release go/no-go decisions with quality data

---

## Business Analyst

### Role Summary
Business Analysts elicit requirements, refine user stories, and ensure proposed solutions meet business needs. They serve as the bridge between stakeholders and the delivery team.

### Responsibilities
- Facilitate requirements gathering sessions with stakeholders
- Document user stories, acceptance criteria, and business processes
- Ensure proposed solutions align with business goals and constraints
- Maintain a shared understanding of scope and priorities across the team
- Support UAT (User Acceptance Testing) by validating business requirements

### Goals
- Ensure clear, unambiguous requirements that reduce rework
- Reduce misalignment between business expectations and delivered solutions
- Improve handoff quality between discovery and delivery phases

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story write-ups and acceptance criteria documents
- Regular syncs with Product Manager and development team leads

### Key Interactions
- **Project Manager:** Provides scope inputs for planning and tracks open requirement items
- **Product Manager:** Collaborates on backlog refinement and priority decisions
- **Developers:** Clarifies requirements and reviews technical approaches for feasibility
- **QA / Testing:** Reviews test cases to confirm they reflect documented acceptance criteria
- **Stakeholder Sponsor:** Validates that requirements reflect strategic organizational priorities

---

## UX Designer

### Role Summary
UX Designers design user interfaces, create prototypes, and advocate for user-centered design practices throughout the project lifecycle.

### Responsibilities
- Create wireframes, prototypes, and user flows for planned features
- Conduct usability testing and synthesize feedback into design iterations
- Provide design standards, UI components, and assets for developers
- Champion accessibility and inclusive design across all deliverables
- Participate in product discovery and backlog refinement sessions

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce development rework by providing clear design specifications early
- Build a shared design language and component library for the product

### Typical Communication
- Design reviews and prototype walkthroughs with the team
- Usability test summaries and research insights
- Design handoff documentation (e.g., Figma annotations or design specs)

### Key Interactions
- **Project Manager:** Coordinates design milestone timelines and flags design dependencies
- **Product Manager:** Aligns design priorities with product vision and user research
- **Developers:** Provides detailed design specs and clarifies implementation questions
- **QA / Testing:** Reviews builds for visual and interaction regressions
- **Stakeholder Sponsor:** Presents design concepts for approval at key milestones

---

## Security Lead

### Role Summary
The Security Lead ensures security best practices are applied to all project deliverables, from requirements review through deployment and incident response.

### Responsibilities
- Review requirements and designs for security risks and compliance considerations
- Coordinate security testing and integrate scanning into the CI pipeline (see [Execution & Tracking](./octoacme-execution-and-tracking.md))
- Advise on vulnerability mitigation strategies and secure coding standards
- Own and maintain the security incident runbook and escalation paths (see [Risk Management & Communication](./octoacme-risks-and-communication.md))
- Lead security-focused retrospective actions after incidents or near-misses

### Goals
- Eliminate critical and high-severity vulnerabilities before release
- Build a security-first culture across the delivery team
- Ensure compliance with organizational security policies and standards

### Typical Communication
- Security review sign-offs at design and pre-release checkpoints
- Vulnerability triage and remediation status updates
- Incident briefings and post-incident blameless retrospective summaries

### Key Interactions
- **Project Manager:** Escalates unresolved security risks that may affect release timelines or project scope
- **Product Manager:** Flags security trade-offs that affect feature prioritization
- **Developers:** Reviews code for vulnerabilities and guides secure implementation patterns
- **QA / Testing:** Coordinates security test results, vulnerability triage, and retest verification
- **Stakeholder Sponsor:** Notifies of high-impact security incidents per escalation paths defined in [Risk Management & Communication](./octoacme-risks-and-communication.md)

---

## Stakeholder Sponsor

### Role Summary
The Stakeholder Sponsor provides executive or strategic oversight, approves major project decisions, and resolves escalated issues that are beyond the authority of the Project Manager or Product Manager.

### Responsibilities
- Review and approve project milestones, budgets, and phase gates
- Resolve escalated risks, resource constraints, and cross-organizational dependencies
- Confirm strategic alignment of the project with organizational priorities
- Approve key deliverables and serve as final decision-maker on scope or timeline changes
- Champion the project within the organization to secure necessary resources and support

### Goals
- Ensure the project delivers measurable business value aligned with organizational strategy
- Remove blockers that cannot be resolved at team level
- Provide visible executive sponsorship to build team confidence and stakeholder trust

### Typical Communication
- Monthly or milestone-based project briefings
- Escalation summaries from the Project Manager when sponsor decisions are required
- Approval confirmations for major deliverables and go/no-go decisions

### Key Interactions
- **Project Manager:** Primary point of contact for escalations and sponsor decisions; receives weekly status and risk updates
- **Product Manager:** Aligns on product strategy and approves significant scope or priority changes
- **Developers:** Engages at key demos and milestone reviews; not involved in day-to-day technical decisions
- **QA / Testing:** Reviews release quality summaries as part of go/no-go gate approvals
- **Security Lead:** Notified of high-impact security incidents and approves major security-related scope changes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

