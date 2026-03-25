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

### Interactions
- **With Product Managers:** Discuss feature requirements and acceptance criteria
- **With QA Lead:** Coordinate testing and bug fixes
- **With Project Manager:** Report progress and blockers
- **With Security Lead:** Incorporate security best practices
- **With Release Manager:** Coordinate deployment activities

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

### Interactions
- **With Project Manager:** Align on timelines and resource planning
- **With Developers:** Define requirements and acceptance criteria
- **With UX Designer:** Collaborate on user research and design validation
- **With Support/Customer Success:** Gather user insights and feedback
- **With Stakeholders:** Present roadmap and business impact

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

### Interactions
- **With Product Manager:** Coordinate timelines and resource allocation
- **With Developers:** Track progress and manage blockers
- **With QA Lead:** Ensure quality standards and acceptance criteria
- **With Release Manager:** Coordinate release schedules
- **With Stakeholders:** Provide status updates and escalate issues

---

## QA Lead

### Role Summary
QA Leads coordinate and execute testing plans, ensuring that acceptance criteria are met and quality standards are maintained. They manage bug triage and work closely with developers to ensure quality throughout the delivery lifecycle.

### Responsibilities
- Design and execute comprehensive test plans aligned with acceptance criteria
- Coordinate and manage quality assurance activities
- Manage bug triage, prioritization, and verification
- Ensure adherence to Definition of Done standards
- Provide quality metrics and reporting
- Identify and escalate quality risks

### Goals
- Ensure features meet acceptance criteria before release
- Minimize bugs reaching production
- Continuously improve testing processes and coverage
- Enable rapid, confident releases

### Typical Communication
- Test plan reviews during sprint planning
- Daily standup updates on quality status
- Bug triage and root cause analysis
- Release readiness assessments

### Interactions
- **With Developers:** Collaborate on test design, reproduce bugs, and verify fixes
- **With Product Manager:** Clarify acceptance criteria and priority of issues
- **With Project Manager:** Report quality status and escalate blockers
- **With Release Manager:** Provide release readiness assessment
- **With UX Designer:** Validate user experience and usability

---

## UX Designer

### Role Summary
UX Designers conduct user research, create design specifications, and ensure that solutions deliver strong user experiences. They collaborate closely with Product Managers and Developers to translate requirements into intuitive, usable features.

### Responsibilities
- Conduct user research and gather user insights
- Create design specifications and prototypes
- Establish usability standards and design guidelines
- Review implementations for design fidelity and usability
- Validate designs with users through testing
- Support accessibility and inclusive design practices

### Goals
- Deliver intuitive, user-centered solutions
- Reduce user friction and support costs
- Establish consistent design language and patterns
- Enable user adoption and satisfaction

### Typical Communication
- Design review meetings and feedback sessions
- User research findings and insights
- Design specs and interaction documentation
- Usability testing results

### Interactions
- **With Product Managers:** Collaborate on feature requirements and user needs
- **With Developers:** Discuss implementation feasibility and design details
- **With QA Lead:** Validate user experience and usability during testing
- **With Support/Customer Success:** Gather user feedback and pain points
- **With Stakeholders:** Present design rationale and user impact

---

## Release Manager

### Role Summary
Release Managers plan, coordinate, and execute releases. They ensure that deployments follow established standards, manage release communications, and coordinate incident response when needed. They work across all teams to ensure readiness and smooth rollouts.

### Responsibilities
- Plan and schedule release windows
- Coordinate pre-release verification and testing
- Manage release notes and deployment communications
- Execute deployments and monitor post-release stability
- Coordinate rollback procedures if needed
- Facilitate incident response and root cause analysis for deployment issues

### Goals
- Execute reliable, repeatable releases with minimal risk
- Maintain stakeholder awareness and confidence in releases
- Minimize mean time to resolution (MTTR) for deployment issues
- Establish and maintain deployment standards

### Typical Communication
- Release planning meetings and timelines
- Pre-release checklists and readiness assessments
- Release notes and deployment announcements
- Post-deployment verification reports
- Incident communications and status updates

### Interactions
- **With Project Manager:** Coordinate release schedules and timelines
- **With Developers:** Confirm build readiness and coordinate deployment
- **With QA Lead:** Obtain release readiness sign-off
- **With Operations/DevOps:** Execute deployment and monitor systems
- **With Support/Customer Success:** Coordinate release communication to customers
- **With Security Lead:** Verify security clearance for release

---

## Security Lead

### Role Summary
Security Leads ensure that security best practices are followed throughout the project delivery lifecycle. They review features for security impacts, manage vulnerability response, and lead incident response for security issues.

### Responsibilities
- Establish and maintain security standards and practices
- Review features and code for security risks
- Manage vulnerability assessment and remediation
- Coordinate security scanning in CI/CD pipeline
- Lead security incident response
- Provide security guidance and best practices training
- Ensure compliance with organizational security policies

### Goals
- Prevent security breaches and data loss
- Enable secure-by-default development practices
- Minimize mean time to remediation (MTTR) for vulnerabilities
- Build organizational security awareness

### Typical Communication
- Security reviews and threat assessments
- Vulnerability reports and remediation plans
- Security scanning results and findings
- Security incident notifications and status updates
- Security best practices guidance

### Interactions
- **With Developers:** Review code and architecture for security risks
- **With Project Manager:** Escalate security blockers and track remediation
- **With QA Lead:** Coordinate security testing and validation
- **With Release Manager:** Approve security readiness for releases
- **With Operations/DevOps:** Coordinate security monitoring and incident response
- **With Stakeholders:** Report on security posture and compliance

---

## Support/Customer Success Representative

### Role Summary
Support and Customer Success Representatives serve as the voice of the customer within the project lifecycle. They gather customer insights, identify pain points, and feed real-world feedback into the project planning process. They communicate releases and changes to customers.

### Responsibilities
- Gather customer feedback and identify pain points
- Communicate with customers about releases and changes
- Validate that solutions address customer needs
- Identify customer-impacting issues and escalate to the team
- Document customer use cases and requirements
- Support customer onboarding and adoption of new features

### Goals
- Ensure customer value is prioritized in projects
- Reduce customer frustration and support tickets
- Accelerate customer adoption of new features
- Build strong customer relationships and loyalty

### Typical Communication
- Customer feedback sessions and surveys
- Feature request and issue documentation
- Release announcements and change communications
- Customer success metrics and satisfaction reporting

### Interactions
- **With Product Managers:** Share customer insights and feature requests
- **With Project Manager:** Report on customer-impacting issues and timelines
- **With Developers:** Clarify feature behavior and customer expectations
- **With UX Designer:** Validate user experience and usability with customers
- **With Release Manager:** Coordinate customer communications for releases
- **With Stakeholders:** Present customer feedback and impact

---

## Stakeholders

### Role Summary
Stakeholders provide business context, strategic direction, and approval authority for projects. They represent organizational interests, resources, and strategic priorities.

### Responsibilities
- Define business objectives and constraints
- Provide project approval and sponsorship
- Ensure alignment with organizational strategy
- Allocate resources and budget
- Escalate organizational blockers
- Provide executive visibility and reporting

### Goals
- Ensure projects deliver business value
- Align projects with organizational strategy
- Manage organizational resource constraints
- Maintain executive confidence and visibility

### Typical Communication
- Monthly stakeholder updates and business reviews
- Escalation of business-level blockers
- Budget and resource allocation decisions
- Strategic guidance and priority setting

### Interactions
- **With Project Manager:** Receive status updates and escalations
- **With Product Manager:** Review business impact and strategic alignment
- **With Release Manager:** Receive release announcements and impact reports
- **With all team members:** Provide strategic direction and constraints

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When working across multiple personas, refer to the "Interactions" section to understand collaboration points and communication pathways.
