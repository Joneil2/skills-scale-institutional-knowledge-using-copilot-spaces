# OctoAcme — Cross-Functional Collaboration Guide

## Purpose
Define how different personas and roles collaborate effectively throughout the project lifecycle, with emphasis on touchpoints, handoffs, and communication patterns.

## Collaboration Framework

### Project Initiation Phase
**Key Personas:** Project Manager, Product Manager, Stakeholders, Security Lead (for risk assessment)

**Handoffs & Checkpoints:**
- Stakeholders define business objectives and approve project charter
- Product Manager creates Project One-pager with success metrics
- Project Manager identifies initial team composition and resource needs
- Security Lead flags initial security considerations and compliance requirements

**Communication Cadence:** Kickoff meeting, email alignment

---

### Project Planning Phase
**Key Personas:** Project Manager, Product Manager, Developers, QA Lead, UX Designer, Release Manager (for timeline planning)

**Handoffs & Checkpoints:**
- Product Manager: Provides prioritized backlog and acceptance criteria
- UX Designer: Creates design specifications and user stories
- Developers: Estimate effort and identify technical risks
- QA Lead: Defines test strategy and acceptance criteria validation approach
- Project Manager: Creates release timeline and dependency map
- Release Manager: Confirms deployment windows and pre-release activities

**Communication Cadence:** Planning sessions, backlog refinement, written specifications

---

### Execution & Development Phase
**Key Personas:** Developers, QA Lead, Project Manager, UX Designer, Security Lead

**Handoffs & Checkpoints:**
- Developers: Implement features, write tests, submit PRs
- UX Designer: Review implementations for design fidelity
- Security Lead: Review code and architecture for security risks
- Developers & QA Lead: Collaborate on test design and quality validation
- Project Manager: Track progress and escalate blockers

**Communication Cadence:** Daily standups, sprint reviews, PR reviews, design reviews

---

### Quality Assurance & Testing Phase
**Key Personas:** QA Lead, Developers, Product Manager, UX Designer

**Handoffs & Checkpoints:**
- QA Lead: Executes test plan and reports quality metrics
- Developers: Fix bugs and verify corrections
- Product Manager: Validates that acceptance criteria are met
- UX Designer: Conducts usability testing and validates user experience

**Communication Cadence:** Test results, bug triage meetings, UAT sessions

---

### Release & Deployment Phase
**Key Personas:** Release Manager, Project Manager, Developers, QA Lead, Operations/DevOps, Security Lead

**Handoffs & Checkpoints:**
- Release Manager: Coordinates release planning and communications
- QA Lead: Provides release readiness sign-off
- Security Lead: Approves security clearance
- Developers: Confirm build readiness and coordinate deployment
- Release Manager: Executes deployment and monitors stability
- Support/Customer Success: Communicates release to customers

**Communication Cadence:** Pre-release checklist review, release notes, deployment status updates

---

### Post-Release & Retrospective Phase
**Key Personas:** All team members, Project Manager, Product Manager

**Handoffs & Checkpoints:**
- Support/Customer Success: Gathers customer feedback and impact assessment
- Developers: Monitor systems and respond to post-release issues
- Project Manager: Facilitates retrospective and captures lessons learned
- Product Manager: Measures success metrics and impact

**Communication Cadence:** Incident reports, retrospective session, follow-up action items

---

## Escalation Paths

### Quality/Acceptance Criteria Issues
QA Lead → Product Manager → Project Manager → Stakeholders

### Technical/Architectural Blockers
Developer → Tech Lead/Architect → Project Manager → Stakeholders

### Security Issues
Security Lead → Project Manager → Stakeholders (escalate if blocking release)

### Timeline/Resource Constraints
Project Manager → Stakeholders (may involve Sponsor)

### Customer-Impacting Issues
Support/Customer Success → Product Manager → Project Manager → Stakeholders

---

## Key Principles for Cross-Functional Collaboration

1. **Clear Ownership:** Each deliverable and decision has a named owner
2. **Early Communication:** Share dependencies and risks early in the project
3. **Documented Handoffs:** Use checklists and templates to ensure nothing falls through cracks
4. **Regular Syncs:** Maintain consistent cadence for alignment and issue resolution
5. **Psychological Safety:** Encourage honest feedback and raise concerns early
6. **Single Source of Truth:** Use consistent documentation for requirements, status, and decisions

---

## Communication Channels & Tools

- **Synchronous:** Daily standups, weekly syncs, ad-hoc meetings
- **Asynchronous:** Project board updates, status emails, design docs, architecture decision records
- **Escalation:** Dedicated escalation channels for blockers and critical issues

---

## Collaboration Checklist

- [ ] Project roles and responsibilities clearly assigned at project start
- [ ] Communication cadence established and agreed by all personas
- [ ] Handoff points documented and validated
- [ ] Escalation paths defined and communicated
- [ ] Shared tools and access configured (project board, documentation, etc.)
- [ ] Success criteria for collaboration defined (e.g., PR review SLA, bug triage cadence)
