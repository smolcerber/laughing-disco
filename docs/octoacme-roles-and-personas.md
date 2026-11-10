# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It includes both core delivery roles and supporting roles that may be needed to improve clarity, accountability, and cross-functional coordination across the project lifecycle.

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

## UX/UI Designers or User Researchers

### Role Summary
UX/UI Designers and User Researchers connect product decisions to user needs, workflows, and usability outcomes. They help ensure that the solution is intuitive, accessible, and aligned with real customer behaviors.

### Responsibilities
- Gather user feedback, research insights, and usability findings
- Shape user journeys, interface flows, and design decisions
- Validate that features meet user needs and accessibility expectations
- Partner with Product Managers on problem framing and prioritization
- Work with Developers and QA to test usability and design feasibility

### Goals
- Improve customer experience and product clarity
- Reduce rework caused by weak user experience assumptions
- Align product decisions with evidence from users and stakeholders

### Typical Communication
- Discovery interviews and usability testing sessions
- Design reviews and prototype walkthroughs
- Collaboration with Product, Developers, and QA on feedback loops

### Interaction with Existing Roles
- With Product Managers: helps define user outcomes, desired flows, and validation criteria
- With Developers: translates experience goals into feasible interface and interaction decisions
- With Project Managers: contributes to sequencing and dependencies when design work impacts delivery milestones
- With QA: helps define usability and accessibility acceptance criteria

---

## Technical Leads or Architects

### Role Summary
Technical Leads or Architects set direction for the solution's technical design, quality, and long-term maintainability. They help teams make sound engineering trade-offs while balancing delivery speed and risk.

### Responsibilities
- Define architecture patterns, technical standards, and integration approaches
- Guide design decisions for complex or cross-cutting work
- Review technical trade-offs, risks, and dependencies
- Support developers in solving design and implementation challenges
- Coordinate technical decisions across teams and delivery milestones

### Goals
- Deliver scalable, resilient, and maintainable solutions
- Reduce technical debt and avoid late-stage rework
- Align implementation choices with product and business priorities

### Typical Communication
- Architecture reviews and technical design discussions
- Cross-team dependency tracking and technical risk reviews
- Planning and escalation conversations with PM and Product leadership

### Interaction with Existing Roles
- With Product Managers: helps assess feasibility, trade-offs, and sequencing decisions
- With Project Managers: identifies dependencies, technical risks, and complexity that affect timelines
- With Developers: provides technical direction, code-quality guidance, and design review support
- With QA: helps define testability, tooling, and environment needs for validation

---

## DevOps Engineers, SREs, or Release Managers

### Role Summary
DevOps Engineers, Site Reliability Engineers, and Release Managers ensure that the system can be built, deployed, monitored, and recovered reliably. They support stable delivery and operational readiness across environments.

### Responsibilities
- Manage CI/CD pipelines, environments, and deployment automation
- Monitor production health, incident readiness, and recovery workflows
- Support release planning, rollback readiness, and post-deploy validation
- Partner with engineering teams on observability, performance, and reliability requirements
- Document operational dependencies and deployment guardrails

### Goals
- Increase delivery reliability and reduce production risk
- Improve operational visibility and incident response readiness
- Support frequent, predictable, and safe releases

### Typical Communication
- Release readiness reviews and deployment checklists
- Monitoring dashboards and incident review updates
- Coordination with Product, PM, Developers, and QA around release timing and impact

### Interaction with Existing Roles
- With Developers: supports environment setup, deployment automation, and production readiness
- With Project Managers: coordinates release windows, dependencies, and communication plans
- With Product Managers: aligns release milestones and operational risk communication with business expectations
- With QA: validates smoke tests, staging readiness, and deployment validation steps

---

## Business Analysts or Requirements Leads

### Role Summary
Business Analysts or Requirements Leads translate stakeholder needs, process constraints, and business goals into clear requirements and acceptance criteria. They help ensure alignment between user needs, business value, and delivery execution.

### Responsibilities
- Capture business requirements and clarify scope decisions
- Translate stakeholder input into user stories, acceptance criteria, and decision records
- Identify process gaps, dependencies, and cross-functional impacts
- Support prioritization conversations with Product and Project leads
- Validate that delivered work matches business intent and operational needs

### Goals
- Improve clarity and reduce misunderstandings across teams
- Make business value and constraints visible throughout delivery
- Increase confidence that delivered work meets stakeholder expectations

### Typical Communication
- Requirements workshops and stakeholder interviews
- Backlog refinement and acceptance criteria reviews
- Status and change impact discussions with Product and Project teams

### Interaction with Existing Roles
- With Product Managers: helps refine problem statements, priorities, and business context
- With Developers and QA: clarifies requirements, scenarios, and expected outcomes
- With Project Managers: flags scope, scheduling, and dependency implications of requirements changes
- With stakeholders: ensures communication is consistent and decisions are captured clearly

---

## Role Combinations and Team Fit

Not every project needs every role filled by a separate person. Smaller teams often combine responsibilities such as:
- Product Manager + UX Researcher
- Technical Lead + Senior Developer
- Release Manager + DevOps Engineer
- Business Analyst + Project Manager

The goal is not to create rigid role boundaries, but to make ownership explicit and to identify where a gap may require support from another persona. This keeps accountability clear while allowing teams to scale roles based on project size and complexity.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These supporting roles are especially useful when projects require user validation, technical leadership, broader operational support, or clearer cross-functional requirements management.

