# OctoAcme — Cross-Functional Collaboration Checklist

## Purpose
A lightweight checklist to ensure the right roles are engaged at each project phase. Use this during planning and kickoff to reduce handoff gaps, unclear ownership, and role ambiguity.

---

## Role Engagement by Phase

### Initiation
- [ ] **Stakeholder Sponsor** has approved the project charter and confirmed strategic alignment
- [ ] **Project Manager** has been assigned and has scheduled the kickoff
- [ ] **Product Manager** has documented the problem statement and initial success metrics
- [ ] **Business Analyst** has identified key stakeholders for requirements gathering

### Planning
- [ ] **Business Analyst** has facilitated requirements sessions and documented user stories with acceptance criteria
- [ ] **UX Designer** has been briefed on user needs and has begun discovery or wireframing
- [ ] **Security Lead** has reviewed initial requirements for security and compliance risks
- [ ] **Project Manager** has added identified risks to the Risk Register with owners and mitigations
- [ ] **Product Manager** has prioritized the backlog and confirmed scope with the Stakeholder Sponsor

### Execution
- [ ] **Developers** have reviewed design specs and acceptance criteria before starting work
- [ ] **UX Designer** is available for implementation questions and has scheduled design reviews
- [ ] **Security Lead** has confirmed security scanning is enabled in CI (see [Execution & Tracking](./octoacme-execution-and-tracking.md))
- [ ] **QA / Testing** has a test plan ready that covers all acceptance criteria
- [ ] **Business Analyst** is available to clarify requirements and review in-progress work

### Release
- [ ] **QA / Testing** has completed end-to-end smoke tests and sign-off
- [ ] **Security Lead** has reviewed release artifacts for outstanding vulnerabilities
- [ ] **Project Manager** has communicated release status to the Stakeholder Sponsor
- [ ] **Stakeholder Sponsor** has approved the go/no-go decision for production release
- [ ] **Product Manager** has confirmed the release meets defined success metrics

### Post-Release
- [ ] **Project Manager** has scheduled a retrospective with all roles
- [ ] **Security Lead** has confirmed no post-release security incidents are open or has initiated runbook (see [Risk Management & Communication](./octoacme-risks-and-communication.md))
- [ ] **Business Analyst** has captured any new requirements or scope changes arising from release feedback
- [ ] **UX Designer** has collected post-release usability feedback for future iterations
- [ ] **Stakeholder Sponsor** has received a post-release summary and confirmed organizational satisfaction

---

## RACI-Lite Summary

| Activity | Project Manager | Product Manager | Business Analyst | UX Designer | Developers | QA / Testing | Security Lead | Stakeholder Sponsor |
|---|---|---|---|---|---|---|---|---|
| Project charter approval | A | C | I | I | I | I | C | R |
| Requirements definition | C | A | R | C | C | C | C | I |
| UX / design sign-off | C | A | C | R | C | I | I | I |
| Security review | I | C | I | I | C | C | R | I |
| Sprint planning | A | R | C | C | R | C | I | I |
| Test sign-off | C | I | C | I | C | R | C | I |
| Release go/no-go | R | C | I | I | I | C | C | A |
| Incident escalation | R | C | I | I | C | C | A | I |

**Key:** R = Responsible, A = Accountable, C = Consulted, I = Informed

---

## Related Documents
- [Roles & Personas](./octoacme-roles-and-personas.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Project Management Overview](./octoacme-project-management-overview.md)
