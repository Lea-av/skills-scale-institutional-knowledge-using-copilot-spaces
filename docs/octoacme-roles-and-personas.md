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

## UX/UI Designers

### Role Summary
UX/UI Designers research user needs and design usable, accessible workflows and interfaces that support product goals.

### Responsibilities
- Conduct user research and synthesize usability needs
- Create and maintain user flows, wireframes, prototypes, and design specifications
- Identify accessibility and usability considerations
- Validate designs through feedback and usability testing

### Goals
- Make product experiences intuitive, inclusive, and aligned with user needs
- Resolve design questions early enough to support predictable implementation

### Typical Communication
- Research findings and design reviews with Product Managers and stakeholders
- Design specifications and prototypes shared with Developers
- Usability findings and design decisions documented for the project team

### Collaboration with Other Roles
- Partner with Product Managers to turn user and business goals into experience requirements and to validate design choices.
- Work with Developers and Technical Leads to assess feasibility, clarify design details, and resolve implementation trade-offs.
- Share design dependencies and review timing with Project Managers so they can be reflected in plans and stakeholder updates.
- Coordinate with QA/Test Engineers on usability and accessibility scenarios that should be validated.

---

## QA/Test Engineers

### Role Summary
QA/Test Engineers plan and perform quality validation so that delivered work meets requirements, acceptance criteria, and agreed quality standards.

### Responsibilities
- Define test approaches and identify coverage needs across features and workflows
- Validate acceptance criteria through appropriate testing
- Record, prioritize, and communicate defects and quality risks
- Support regression, integration, and release-readiness testing

### Goals
- Find important issues early and reduce preventable regressions
- Provide clear evidence of product quality and remaining risks

### Typical Communication
- Test plans, test results, and defect reports shared with Developers and Product Managers
- Quality and release-readiness updates in project tracking and status reviews
- Test scenarios clarified during refinement and planning

### Collaboration with Other Roles
- Work with Product Managers and Business Analysts to make requirements and acceptance criteria testable, including edge cases.
- Coordinate with Developers to reproduce defects, agree on fixes, and improve test coverage; QA supports quality throughout development rather than replacing developer testing.
- Align with UX/UI Designers on usability and accessibility checks and with DevOps/Release Engineers on environment and deployment validation.
- Report blockers, quality risks, and readiness evidence to Project Managers for delivery planning and escalation.

---

## Technical Leads / Architects

### Role Summary
Technical Leads / Architects guide technical design and implementation, helping the team make coherent, maintainable decisions while managing technical constraints and risks.

### Responsibilities
- Shape and communicate technical designs and architecture decisions
- Guide implementation practices and participate in design and code reviews
- Identify technical risks, dependencies, and trade-offs
- Support Developers with complex technical questions and integration planning

### Goals
- Keep solutions reliable, secure, maintainable, and fit for purpose
- Help the team make timely technical decisions without obscuring ownership

### Typical Communication
- Architecture notes and technical design reviews
- Technical guidance and code reviews with Developers
- Feasibility, estimates, dependencies, and risk updates with product and project leads

### Collaboration with Other Roles
- Partner with Developers on implementation choices, standards, and technical problem solving; Developers remain responsible for their assigned work and quality.
- Advise Product Managers on feasibility, options, and technical consequences of product trade-offs.
- Give Project Managers visibility into technical dependencies, estimates, and risks so plans and escalations are informed.
- Coordinate with QA/Test Engineers and DevOps/Release Engineers on testability, observability, deployment, and operational concerns.

---

## Business Analysts / Domain Experts

### Role Summary
Business Analysts / Domain Experts clarify business processes, rules, and stakeholder needs so the team can build and validate the right solution.

### Responsibilities
- Elicit and document requirements, workflows, and business rules
- Identify assumptions, exceptions, and process impacts
- Clarify requirements and answer domain questions during delivery
- Validate that proposed solutions address stakeholder and operational needs

### Goals
- Reduce ambiguity and avoid preventable rework
- Ensure domain rules and stakeholder needs are represented in delivery decisions

### Typical Communication
- Requirements and process documentation shared with Product Managers and the delivery team
- Refinement discussions and examples of expected behavior with Developers and QA/Test Engineers
- Decision and dependency updates with Project Managers and stakeholders

### Collaboration with Other Roles
- Work with Product Managers to clarify problems, user and business needs, and prioritization inputs; Product Managers retain ownership of product direction and backlog priority.
- Translate agreed needs into clear rules and examples for Developers and QA/Test Engineers, and help resolve questions as implementation and testing progress.
- Provide Project Managers with visibility into stakeholder decisions, requirement dependencies, and unresolved questions that may affect delivery.
- Consult UX/UI Designers when business workflows shape user journeys or interface behavior.

---

## DevOps / Release Engineers

### Role Summary
DevOps / Release Engineers support the systems, automation, and operational practices needed to build, deploy, and run software reliably.

### Responsibilities
- Maintain or improve build, deployment, and infrastructure automation
- Support environment configuration, monitoring, and operational readiness
- Identify deployment, reliability, and infrastructure risks
- Coordinate release execution and operational handoffs

### Goals
- Make delivery repeatable and reduce deployment risk
- Improve service reliability and visibility into production behavior

### Typical Communication
- Deployment pipeline and infrastructure documentation shared with Developers and Technical Leads
- Release checklists and readiness updates with QA/Test Engineers and Project Managers
- Operational changes and rollout considerations communicated to Product Managers and relevant stakeholders

### Collaboration with Other Roles
- Work with Developers and Technical Leads on delivery pipelines, infrastructure needs, and observability; teams jointly address the operational quality of the service.
- Coordinate with QA/Test Engineers on environment availability, deployment validation, and release checks.
- Advise Product Managers on rollout constraints and operational considerations that affect user impact.
- Keep Project Managers informed about release dependencies, readiness, and risks so timing and stakeholder communications reflect the actual delivery status.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- A person may hold more than one role depending on team size; teams should still make responsibilities, decision ownership, and handoffs explicit.
