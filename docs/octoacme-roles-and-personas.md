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

## Scrum Master

### Role Summary
The Scrum Master facilitates agile ceremonies, removes team impediments, and drives process improvements. They enable the team to self-organize and continuously improve their delivery velocity and quality.

### Responsibilities
- Facilitate daily standups, sprint planning, retrospectives, and reviews
- Identify and help resolve team blockers and impediments
- Coach team members on agile practices and values
- Maintain sprint board and tracking artifacts
- Drive process improvement initiatives based on team feedback
- Protect team focus and shield from external distractions

### Goals
- Maximize team velocity and predictability
- Foster a culture of continuous improvement
- Enable self-organization and accountability
- Reduce cycle time and improve delivery rhythm

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones with team members to identify blockers
- Retrospective summaries and action items
- Process improvement recommendations

### Interactions with Other Roles
- **Project Manager:** Collaborates on timeline adjustments and risk escalation
- **Product Manager:** Coordinates sprint planning and prioritization ceremonies
- **Developers:** Removes impediments and facilitates technical discussions
- **QA Lead:** Collaborates on test planning and acceptance criteria clarity

---

## UI/UX Designer

### Role Summary
UI/UX Designers craft user interfaces, design user flows, and prototype solutions to ensure products are intuitive, accessible, and delightful. They advocate for user needs throughout the delivery cycle.

### Responsibilities
- Create wireframes, mockups, and interactive prototypes
- Conduct user research and usability testing
- Define information architecture and user flows
- Ensure accessibility and inclusive design principles
- Collaborate with Developers on implementation fidelity
- Iterate on designs based on user feedback and metrics

### Goals
- Deliver intuitive and accessible user experiences
- Reduce friction in critical user journeys
- Measure and improve usability metrics
- Bridge user needs with technical constraints

### Typical Communication
- Design reviews with Product Manager and Developers
- User research findings and recommendations
- Prototype walkthroughs and feedback sessions
- Accessibility and design system documentation

### Interactions with Other Roles
- **Product Manager:** Aligns designs with product strategy and user needs
- **Developers:** Collaborates on technical feasibility and implementation details
- **QA Lead:** Partners on usability testing and acceptance criteria
- **Business Analyst:** Validates designs against business requirements

---

## QA Lead

### Role Summary
The QA Lead defines testing strategies, manages test planning and execution, and ensures quality standards are met before release. They bridge product expectations with quality assurance.

### Responsibilities
- Define test strategies and test plans for features
- Create and maintain test cases and acceptance criteria
- Manage manual and automated testing efforts
- Identify and track quality issues and regressions
- Collaborate on Definition of Done and quality metrics
- Report quality status and recommend go/no-go decisions

### Goals
- Ensure features meet acceptance criteria
- Reduce production defects and regressions
- Maintain high test coverage and automation
- Enable fast, confident releases

### Typical Communication
- Test plans and strategy documents
- Defect reports and quality dashboards
- Test case reviews and acceptance criteria clarity
- Release readiness assessments

### Interactions with Other Roles
- **Product Manager:** Clarifies acceptance criteria and success metrics
- **Developers:** Partners on test automation and technical quality
- **Project Manager:** Reports quality status for go/no-go decisions
- **UI/UX Designer:** Validates usability and user acceptance
- **Scrum Master:** Discusses quality blockers in standups

---

## Business Analyst

### Role Summary
Business Analysts clarify requirements, analyze feasibility and business impact, and ensure solutions align with organizational goals. They bridge stakeholders, product, and engineering.

### Responsibilities
- Gather and document business and technical requirements
- Analyze feasibility, trade-offs, and business impact
- Refine acceptance criteria with Product Manager and Developers
- Identify and escalate scope changes and dependencies
- Validate alignment between solutions and business objectives
- Create requirements documentation and traceability matrices

### Goals
- Ensure solutions solve the right business problem
- Reduce scope creep and rework
- Improve stakeholder alignment and satisfaction
- Enable informed trade-off decisions

### Typical Communication
- Requirements documents and user stories
- Feasibility assessments and impact analyses
- Stakeholder interviews and feedback summaries
- Trade-off recommendations and decision logs

### Interactions with Other Roles
- **Product Manager:** Partners on requirement refinement and prioritization
- **Developers:** Collaborates on feasibility and technical trade-offs
- **Project Manager:** Escalates scope changes and dependency risks
- **Stakeholders:** Gathers and validates business needs

---

## Site Reliability Engineer (SRE)

### Role Summary
Site Reliability Engineers implement observability, reliability, and security strategies in production systems. They coordinate incident response and partner with Developers to ensure operational excellence.

### Responsibilities
- Design and implement monitoring, logging, and alerting systems
- Define reliability targets and error budgets
- Coordinate major incident response and post-mortems
- Work on performance optimization and capacity planning
- Implement infrastructure improvements and automation
- Partner with Developers on deployability and observability

### Goals
- Maximize system reliability and uptime
- Enable fast incident detection and resolution
- Automate operational toil and manual processes
- Reduce mean time to recovery (MTTR) and mean time between failures (MTBF)

### Typical Communication
- Observability dashboards and alerting strategies
- Incident reports and post-mortem findings
- Performance and reliability metrics
- Infrastructure and automation documentation

### Interactions with Other Roles
- **Developers:** Collaborates on deployment strategies and observability instrumentation
- **QA Lead:** Partners on performance and load testing
- **Project Manager:** Reports reliability metrics and operational status
- **Security/Ops Teams:** Aligns on security hardening and compliance

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [Role Interaction Matrix](octoacme-role-interaction-matrix.md) to understand how roles collaborate across the project lifecycle.
