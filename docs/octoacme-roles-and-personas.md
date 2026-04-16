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

## QA / Test Engineers

### Role Summary
QA and Test Engineers are responsible for validating that features meet
acceptance criteria and that the product is reliable before it ships. They work
closely with developers and product managers throughout the development cycle,
not just at the end.

### Responsibilities
- Define and execute test plans for features and releases
- Automate regression and acceptance test suites
- File and triage defects with clear reproduction steps
- Participate in sprint planning to scope testing work
- Verify bug fixes and validate acceptance criteria with the product team

### Goals
- Catch defects early to reduce the cost of rework
- Maintain a reliable, fast test suite that supports continuous delivery
- Ensure product quality meets stakeholder and customer expectations

### Typical Communication
- Daily standups and sprint reviews
- Defect reports and test result summaries
- Collaboration with developers during feature development and code review

### Interaction with Other Roles
- **Developers**: Pair on acceptance criteria before development begins; review
  PRs for testability; triage defects together.
- **Product Managers**: Clarify acceptance criteria and expected behaviour; review
  edge cases and error scenarios.
- **Project Managers**: Report test coverage status; flag quality risks that might
  affect release timelines.

---

## UX / Design

### Role Summary
UX Designers translate customer needs and product goals into clear, usable
interfaces and workflows. They collaborate with Product Managers to shape
requirements and with Developers to ensure designs are implemented faithfully.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define interaction patterns and accessibility standards
- Maintain and evolve the design system
- Review implemented features against design specifications

### Goals
- Deliver intuitive, accessible experiences that delight users
- Reduce ambiguity in requirements by providing clear design artefacts
- Advocate for user needs throughout the project lifecycle

### Typical Communication
- Design reviews and critique sessions
- Handoff documents and annotated prototypes
- Ongoing collaboration with developers via design tools and PR comments

### Interaction with Other Roles
- **Product Managers**: Co-create user stories and define acceptance criteria with
  a UX lens; validate design decisions against business goals.
- **Developers**: Provide detailed specifications and stay available to answer
  implementation questions; review completed work before sign-off.
- **QA Engineers**: Collaborate on usability and accessibility test cases.

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders and Sponsors provide strategic direction, secure resources, and
approve major decisions. They are kept informed of project progress and are
engaged at key decision points rather than day-to-day execution.

### Responsibilities
- Approve project charters and significant scope changes
- Remove organisational blockers that are beyond the team's control
- Provide timely input on trade-offs when escalated by the Project Manager
- Champion the project within the broader organisation

### Goals
- Ensure the project delivers business value aligned with organisational strategy
- Keep investment risk visible and manageable
- Enable the team to move quickly by resolving escalations promptly

### Typical Communication
- Monthly stakeholder updates (status, risks, decisions needed)
- Ad-hoc escalations for critical decisions or blockers
- Executive summaries for major milestones and releases

### Interaction with Other Roles
- **Project Managers**: Primary point of contact; escalations flow up to sponsors
  when the team cannot unblock themselves.
- **Product Managers**: Alignment on roadmap priorities and trade-offs.
- **Developers / QA**: Rarely direct; engagement occurs through demos and
  milestone reviews.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When creating issues or pull requests, reference the relevant persona(s) to clarify who is impacted
  and who should review the proposed change.

