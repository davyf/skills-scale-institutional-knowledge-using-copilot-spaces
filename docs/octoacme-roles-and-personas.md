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

## Release Managers

### Role Summary
Release Managers coordinate release readiness and deployment so changes can be delivered safely and predictably.

### Responsibilities
- Coordinate release scope, readiness reviews, and deployment windows
- Confirm required acceptance criteria, CI checks, security scans, and smoke tests are complete
- Maintain release notes and rollback or mitigation plans
- Track release blockers and coordinate their resolution

### Interaction with Existing Roles
- Partner with Project Managers to align release dates, dependencies, and stakeholder updates
- Coordinate with Developers to confirm release candidates and technical deployment needs
- Work with QA Engineers to review validation results and smoke-test coverage
- Coordinate with Support/Operations Representatives on operational readiness and release communications
- Consult Product Managers on release scope and customer impact

### Goals
- Deliver planned changes with clear readiness and rollback plans
- Reduce release risk and improve stakeholder awareness

### Typical Communication
- Release readiness reviews and deployment coordination
- Release notes, go/no-go updates, and post-deployment verification reports

---

## Scrum Masters / Delivery Facilitators

### Role Summary
Scrum Masters or Delivery Facilitators help teams use their agreed delivery practices effectively, make impediments visible, and improve the flow of work. This role facilitates the team and does not replace the Project Manager's accountability for project coordination.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives as agreed by the team
- Help surface and remove delivery impediments
- Encourage clear work items, manageable increments, and continuous improvement
- Help the team monitor flow and capacity without taking ownership of product priorities

### Interaction with Existing Roles
- Coordinate with Project Managers on delivery risks, dependencies, and progress while leaving project plans and stakeholder reporting with the PM
- Work with Developers to expose blockers and improve collaboration and delivery flow
- Support Product Managers in preparing prioritized work with clear goals and acceptance criteria
- Bring recurring process issues and improvement actions to retrospectives and the relevant project owner

### Goals
- Help the team deliver sustainably and improve its working practices
- Make impediments, capacity concerns, and improvement opportunities visible

### Typical Communication
- Facilitated team ceremonies and retrospective action tracking
- Impediment updates with the Project Manager and delivery team

---

## QA Engineers

### Role Summary
QA Engineers help ensure that delivered work meets acceptance criteria and quality expectations through risk-based test planning and validation.

### Responsibilities
- Define and maintain test approaches for features and critical user flows
- Perform or coordinate manual, automated, integration, and end-to-end testing as appropriate
- Record test evidence, defects, and quality risks clearly
- Help make acceptance criteria testable and identify coverage gaps early

### Interaction with Existing Roles
- Collaborate with Developers on testability, defect triage, and automated checks
- Work with Product Managers to clarify acceptance criteria and expected behavior
- Coordinate with Project Managers on test status, quality risks, and schedule implications
- Partner with Release Managers on release validation and smoke-test readiness
- Consult Security Leads on security-related validation needs

### Goals
- Find important issues early and provide clear evidence of release quality
- Improve confidence that changes satisfy user and business needs

### Typical Communication
- Test plans, defect reports, and CI/test results
- Acceptance and release-readiness discussions

---

## UX / Design Leads

### Role Summary
UX / Design Leads translate customer needs and research into usable, accessible experiences and design guidance for delivery teams.

### Responsibilities
- Plan or conduct user research and synthesize customer insights
- Create and validate user flows, interaction designs, and prototypes
- Document design decisions, usability requirements, and accessibility considerations
- Gather feedback and refine designs as product understanding evolves

### Interaction with Existing Roles
- Partner with Product Managers to frame user problems, validate opportunities, and align designs with product outcomes
- Work with Developers to assess feasibility and resolve implementation questions
- Coordinate with QA Engineers on usability, accessibility, and experience validation
- Share research findings and design decisions with Project Managers and stakeholders to inform planning and dependencies

### Goals
- Deliver coherent, usable experiences grounded in customer needs
- Identify usability risks early and reduce avoidable rework

### Typical Communication
- Research summaries, design reviews, and prototypes
- Design specifications and implementation feedback

---

## Security Leads

### Role Summary
Security Leads help teams identify and manage security risks throughout planning, development, testing, and release.

### Responsibilities
- Define or clarify security requirements and applicable controls
- Guide threat modeling and security risk assessment
- Advise on secure design and implementation practices
- Coordinate security reviews, findings, and remediation priorities
- Escalate security incidents through the established security incident process

### Interaction with Existing Roles
- Work with Product Managers to incorporate security needs into scope and acceptance criteria
- Advise Developers on secure implementation and remediation options
- Coordinate with QA Engineers on security validation and evidence
- Partner with Project Managers to record security risks, owners, mitigations, and escalation needs
- Consult Release Managers on security readiness and unresolved release risks

### Goals
- Reduce security exposure without losing sight of delivery context
- Make security ownership, findings, and mitigations visible to the team

### Typical Communication
- Threat models, security review findings, and mitigation tracking
- Security risk updates and incident escalation communications

---

## Support / Operations Representatives

### Role Summary
Support / Operations Representatives bring customer support and production operations needs into delivery and help prepare teams to operate and support released changes.

### Responsibilities
- Identify operational requirements, support workflows, and customer-impact considerations
- Review monitoring, alerting, runbooks, and support documentation for readiness
- Share production feedback, recurring issues, and support trends with the team
- Coordinate incident triage and operational handoffs with responsible teams

### Interaction with Existing Roles
- Work with Developers on observability, runbooks, and operational fixes
- Coordinate with Project Managers on operational dependencies, risks, and incident communications
- Partner with Release Managers on deployment readiness, customer notices, and post-release verification
- Share customer-facing impacts and support trends with Product Managers to inform prioritization
- Coordinate with QA Engineers on operational scenarios and critical user-flow checks

### Goals
- Ensure changes can be supported and operated effectively after release
- Reduce customer impact through clear readiness and incident handoffs

### Typical Communication
- Operational readiness reviews, runbooks, and incident updates
- Support trend summaries and post-release feedback

---

## Data / Analytics Roles

### Role Summary
Data / Analytics roles help teams define, instrument, and interpret measures of product and project outcomes.

### Responsibilities
- Define measurement plans and ensure metrics have clear definitions and sources
- Advise on instrumentation, data quality, dashboards, and analysis methods
- Analyze results and communicate evidence, limitations, and trends
- Support experiments or post-release evaluation where appropriate

### Interaction with Existing Roles
- Partner with Product Managers to connect success metrics to product goals and interpret outcomes
- Work with Developers to plan and implement instrumentation and resolve data-quality issues
- Coordinate with Project Managers to make agreed progress and outcome measures visible in reporting
- Collaborate with UX / Design Leads on research findings and behavioral signals

### Goals
- Enable trustworthy, actionable decisions based on measurable outcomes
- Close the loop between delivery, customer impact, and product learning

### Typical Communication
- Metric definitions, dashboards, and analysis summaries
- Measurement planning and post-release outcome reviews

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
