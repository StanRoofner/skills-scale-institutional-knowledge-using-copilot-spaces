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

## Project Sponsor / Executive Sponsor

### Role Summary
The Project Sponsor provides strategic sponsorship, business context, and decision-making authority for the initiative. They confirm the priority of the work and help unblock major trade-offs when cross-functional decisions are needed.

### Responsibilities
- Own the business case and alignment to strategic goals
- Approve major scope, funding, or prioritization changes
- Support escalation when risks or blockers impact outcomes
- Provide executive sponsorship at decision gates
- Align stakeholders around goals, constraints, and trade-offs

### Decision Authority
- Approves major scope and funding decisions
- Signals whether the initiative remains aligned with business priorities
- Resolves higher-level conflicts between strategic, financial, or schedule priorities

### Interactions with Existing Roles
- Project Manager: status reviews, escalations, and strategic decisions
- Product Manager: priority alignment, outcome framing, and trade-offs
- Developers: usually indirect; may provide context on delivery constraints and business impacts
- QA/Testing: usually indirect; may be informed of release or risk decisions
- Stakeholders: executive communication, sponsorship, and approval

### Participation Across the Lifecycle
- Initiation: confirms sponsor alignment and business case
- Planning: approves scope and major trade-offs
- Execution: escalates constraints and unresolved decisions
- Release: approves go/no-go when major business impact exists
- Retrospective: supports learning and strategic follow-up

---

## Technical Lead / Engineering Lead

### Role Summary
The Technical Lead sets the technical direction for the solution and ensures the implementation is feasible, maintainable, and aligned with architectural standards.

### Responsibilities
- Define technical approach, architecture, and design constraints
- Review engineering estimates and implementation feasibility
- Own technical risks, dependencies, and architecture decisions
- Guide engineering quality, maintainability, and delivery rhythm
- Coordinate technical design discussions with the team

### Decision Authority
- Recommends or approves technical design decisions
- Determines whether proposed solutions align with architecture and standards
- Escalates technical trade-offs that affect schedule, scope, or quality

### Interactions with Existing Roles
- Project Manager: milestones, technical dependencies, and escalations
- Product Manager: feasibility, trade-offs, and prioritization impacts
- Developers: architecture guidance, design reviews, and implementation support
- QA/Testing: validation strategy, defect triage, and release readiness
- Stakeholders: usually indirect, through status and technical risk framing

### Participation Across the Lifecycle
- Initiation: early feasibility and technical fit review
- Planning: estimates, architecture, dependencies, and technical risks
- Execution: design oversight, issue resolution, and delivery tracking
- Release: readiness and rollback considerations
- Retrospective: technical process improvements and lessons learned

---

## UX / Product Designer

### Role Summary
The UX / Product Designer represents user needs in the product experience and ensures the solution is usable, understandable, and aligned with the intended user journey.

### Responsibilities
- Translate user needs and business goals into workflow and interface design
- Help define usability and accessibility requirements
- Contribute to acceptance criteria and validation scenarios
- Partner with product, engineering, and stakeholders on design decisions
- Identify design risks or dependencies that affect delivery

### Decision Authority
- Recommends interaction and experience decisions
- Validates whether designs meet usability and user needs
- Escalates design risks that affect outcomes or scope

### Interactions with Existing Roles
- Project Manager: design timing, dependencies, and milestone impacts
- Product Manager: discovery, problem framing, and outcome validation
- Developers: implementation feasibility, design handoff, and iteration feedback
- QA/Testing: usability validation and acceptance scenarios
- Stakeholders: feedback, signoff, and business context

### Participation Across the Lifecycle
- Initiation: user journey and problem framing
- Planning: experience requirements and design sequencing
- Execution: design iteration, usability reviews, and implementation feedback
- Release: usability validation and launch readiness
- Retrospective: improvements to user-centered practices

---

## Business Analyst / Requirements Lead

### Role Summary
The Business Analyst / Requirements Lead clarifies needs, structures requirements, and maintains traceability from stakeholder needs to backlog items and acceptance criteria.

### Responsibilities
- Elicit, document, and refine requirements
- Map business processes and dependencies
- Clarify scope, ambiguity, and decision points
- Maintain traceability from requirements to delivery artifacts
- Support prioritization and readiness reviews

### Decision Authority
- Recommends requirement clarity and scope boundaries
- Identifies missing or conflicting requirements
- Helps resolve ambiguity that affects delivery and acceptance

### Interactions with Existing Roles
- Project Manager: scope control, dependencies, and planning support
- Product Manager: requirement refinement and prioritization
- Developers: clarification of functional intent and edge cases
- QA/Testing: acceptance criteria and validation completeness
- Stakeholders: requirements gathering and alignment

### Participation Across the Lifecycle
- Initiation: needs discovery and framing
- Planning: backlog hygiene, scope clarity, and acceptance criteria
- Execution: requirement clarification and change management
- Release: validation readiness and traceability
- Retrospective: lessons on ambiguity and process improvement

---

## Release Manager / Deployment Coordinator

### Role Summary
The Release Manager / Deployment Coordinator ensures that releases are prepared, scheduled, and communicated consistently with minimal operational disruption.

### Responsibilities
- Coordinate deployment windows and release readiness
- Draft or coordinate release notes and stakeholder communication
- Manage rollback planning and deployment checklists
- Align release activities with product and engineering milestones
- Support go/no-go decisions for production release

### Decision Authority
- Recommends release readiness and timing
- Coordinates deployment conditions and rollback readiness
- Escalates risks that affect safe release execution

### Interactions with Existing Roles
- Project Manager: schedule, readiness, and communications
- Product Manager: release scope and stakeholder messaging
- Developers: verification and rollback readiness
- QA/Testing: signoff and validation evidence
- Stakeholders: announcements, dependencies, and customer impact communication

### Participation Across the Lifecycle
- Initiation: release expectations and dependencies
- Planning: release plan and milestone mapping
- Execution: readiness checks and deployment coordination
- Release: production deployment and verification
- Retrospective: improvement to release processes

---

## Operations / Site Reliability / Support Representative

### Role Summary
This role ensures the solution is supportable, observable, and safe to operate in production. It helps reduce operational risk and supports customer impact management.

### Responsibilities
- Provide input on operational readiness and monitoring
- Validate supportability, observability, and alerting
- Help assess operational risk and customer impact
- Support incident response and communication during disruptions
- Advise on production-readiness criteria

### Decision Authority
- Recommends operational risk thresholds and mitigation
- Contributes to production readiness and rollback or incident escalation decisions
- Identifies supportability gaps that block launch or stability

### Interactions with Existing Roles
- Project Manager: risks, incidents, communication, and operational dependencies
- Product Manager: business impacts and support expectations
- Developers: observability, deployment safety, and operational support
- QA/Testing: production-like validation and failure scenarios
- Stakeholders: support readiness and customer impact communication

### Participation Across the Lifecycle
- Initiation: supportability and operational needs
- Planning: monitoring, incident response, and rollout readiness
- Execution: observability, performance, and production risk review
- Release: production verification and issue triage
- Retrospective: incident learning and resilience improvements

---

## Security / Privacy Representative

### Role Summary
The Security / Privacy Representative helps protect the solution, its users, and the organization by identifying risks, required controls, and compliance considerations.

### Responsibilities
- Evaluate security and privacy risks
- Review controls, threat models, and compliance requirements
- Support secure design and implementation decisions
- Validate security and privacy requirements during testing
- Coordinate escalation for review gates or incidents

### Decision Authority
- Recommends security requirements and acceptable risk
- Identifies mandatory review gates or controls
- Escalates unresolved risks that affect launch or compliance

### Interactions with Existing Roles
- Project Manager: review gates, escalation paths, and dependency management
- Product Manager: trade-offs between feature goals and risk posture
- Developers: secure implementation and validation
- QA/Testing: security and privacy verification
- Stakeholders: compliance, acceptable risk, and governance concerns

### Participation Across the Lifecycle
- Initiation: risk and compliance framing
- Planning: security requirements and review gates
- Execution: control validation and issue monitoring
- Release: release gating and final risk review
- Retrospective: lessons from incidents or control gaps

---

## Lightweight Project Guidance

Not every role is needed on every project. Smaller projects may combine responsibilities when a person can reasonably own multiple areas, but accountability should still be explicit.

### Guidance for Small Teams
- One person may serve as both Product Manager and Project Manager on a very small initiative, but decision ownership and communication responsibilities should still be documented.
- A Technical Lead may also be one of the Developers, but architecture decisions still need review when the change affects cross-team or critical systems.
- Security, privacy, or operations input may be lightweight and advisory for low-risk work, while high-risk changes should include explicit review.
- Release and support responsibilities may be shared with the Project Manager or engineering lead if the project is narrow in scope.

### Best Practice
When responsibilities are combined, document:
- Who is accountable
- Who is consulted
- Who must be informed
- Which decisions still require stakeholder or sponsor approval

This helps preserve clarity without requiring every project to staff every role full-time.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The roles are intended to be practical and adaptable to different team sizes and project complexity.

