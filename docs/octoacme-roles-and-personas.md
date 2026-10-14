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

## Tech Lead

### Role Summary
The Tech Lead provides technical direction for a project or team and helps translate product goals into a feasible implementation approach.

### Responsibilities
- Guide architecture, technical design, and code quality standards
- Review technical trade-offs and ensure alignment with engineering practices
- Mentor developers and support technical decision-making
- Coordinate with product and project stakeholders on feasibility and sequencing

### Decision Authority
- Owns technical design recommendations and engineering standards for the team
- Escalates architectural, capacity, or dependency issues to Engineering Manager or leadership when needed

### Typical Interactions
- Works closely with Developers on implementation approach and reviews
- Partners with Product Managers and Project Managers to assess scope, dependencies, and delivery risk
- Coordinates with Security, DevOps, and QA to ensure the solution is buildable, testable, and deployable

---

## Engineering Manager

### Role Summary
The Engineering Manager is responsible for team health, capacity, and cross-team execution support. They help remove blockers and improve the delivery environment.

### Responsibilities
- Manage team capacity, staffing, and workload balancing
- Support engineering planning, performance, and process improvements
- Help remove organizational blockers and escalate cross-team dependencies
- Coordinate with PMs and Product Managers on planning decisions that affect team pacing

### Decision Authority
- Has authority to adjust team staffing, priorities, and planning constraints within the agreed delivery plan
- Escalates resourcing, policy, or strategic trade-offs to leadership as needed

### Typical Interactions
- Works with Project Managers on delivery forecasts, dependencies, and staffing impacts
- Supports Tech Leads in aligning technical direction with business priorities
- Partners with Product Managers on prioritization trade-offs and impact assessment

---

## UX Researcher / Product Designer

### Role Summary
UX Researchers and Designers ensure solutions are useful, usable, and aligned with customer needs and product goals.

### Responsibilities
- Conduct user research, usability testing, and customer interviews
- Create workflows, prototypes, and interaction designs
- Translate user insights into product decisions and acceptance criteria
- Validate whether customer experience goals are met before release

### Decision Authority
- Owns UX quality, research findings, and design recommendations within the product scope
- Escalates product or business trade-offs when design conflicts with feasibility or delivery constraints

### Typical Interactions
- Works with Product Managers to define customer value and success criteria
- Collaborates with Developers and Tech Leads to ensure designs are feasible and implementable
- Coordinates with QA and Customer Success to validate usability and support readiness

---

## QA Lead

### Role Summary
The QA Lead ensures quality is built into delivery, with a focus on validation, risk coverage, and release confidence.

### Responsibilities
- Define and maintain test strategy, coverage, and regression plans
- Review acceptance criteria and support testability during planning
- Lead manual and automated validation efforts for critical flows
- Coordinate with engineering and release stakeholders on risk-based testing

### Decision Authority
- Determines when release readiness criteria are met based on test evidence and risk evaluation
- Escalates quality or regression risks that may impact release confidence or customer impact

### Typical Interactions
- Works with Developers on test planning and defect triage
- Partners with Product Managers and Project Managers on acceptance validation and milestone readiness
- Coordinates with Release Manager and DevOps on smoke tests and release verification

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers support reliable delivery, deployment automation, and production operations for the team.

### Responsibilities
- Maintain CI/CD pipelines, infrastructure automation, and deployment practices
- Design and support environments, observability, and production health
- Improve reliability, incident response readiness, and rollback capabilities
- Partner with engineering teams to operationalize product changes safely

### Decision Authority
- Owns deployment platform standards and operational guardrails for the project environment
- Escalates infrastructure risks or constraints that may affect delivery or service reliability

### Typical Interactions
- Collaborates with Developers and Tech Leads on deployment readiness and runtime dependencies
- Works with Release Manager on release windows, rollback plans, and operational verification
- Coordinates with Security to ensure secure infrastructure configurations and monitoring

---

## Security Engineer

### Role Summary
Security Engineers help identify and mitigate threats, enforce secure development practices, and support compliance requirements.

### Responsibilities
- Conduct threat modeling and security reviews for product changes
- Review architecture, dependencies, and data flows for security risks
- Support secure coding practices, testing, and ongoing monitoring
- Coordinate remediation for vulnerabilities and security-sanctioned release requirements

### Decision Authority
- Defines security requirements and risk acceptance recommendations for the project
- Escalates critical security concerns requiring prioritization or policy intervention

### Typical Interactions
- Works with Tech Leads and Developers during design and code review
- Partners with Product Managers and Project Managers on risk prioritization and release gating
- Coordinates with DevOps and Release Manager on secure deployment and incident handling

---

## Release Manager

### Role Summary
The Release Manager coordinates release planning, communication, and readiness checks so changes move to production with minimal disruption.

### Responsibilities
- Manage release timing, checkpoints, and deployment readiness reviews
- Coordinate rollback plans, stakeholder communications, and release documentation
- Track outstanding release dependencies and post-deploy follow-up
- Support communication with support, customer-facing teams, and leadership

### Decision Authority
- Owns the release plan and approval checkpoints within agreed deployment windows
- Escalates issues that threaten release quality, compliance, or business continuity

### Typical Interactions
- Works with PMs, Developers, and DevOps to confirm release readiness and deployment sequence
- Partners with QA and Security for smoke test validation and risk checks
- Coordinates with Customer Success or Support on customer communications and release impact

---

## Customer Success / Support Representative

### Role Summary
Customer Success and Support roles connect product delivery to real customer needs and post-release issues.

### Responsibilities
- Share customer feedback, issues, and adoption signals with the delivery team
- Help triage user-impacting bugs and escalations
- Validate whether release changes resolved customer pain points
- Support onboarding, rollout communications, and customer-facing documentation

### Decision Authority
- Provides input on customer impact and urgency for prioritization decisions
- Escalates customer-impacting issues to PMs, Product Managers, or leadership as needed

### Typical Interactions
- Feeds customer feedback into the backlog and prioritization process
- Works with Product Managers and QA to identify impact, severity, and acceptance checks
- Coordinates with Release Manager on rollout communication and support readiness

---

## Data Analyst

### Role Summary
Data Analysts help teams measure product value, monitor change effectiveness, and validate impact with data.

### Responsibilities
- Define instrumentation and success metrics for features and projects
- Analyze adoption, retention, performance, and quality trends
- Validate whether product outcomes match the original goals and success metrics
- Support product and stakeholder decision-making with evidence

### Decision Authority
- Provides recommendations on measurement quality, metric definitions, and analysis approach
- Escalates data quality or interpretation issues that affect business decisions

### Typical Interactions
- Works with Product Managers to define success metrics and dashboard requirements
- Partners with Developers and DevOps to ensure logging and instrumentation are in place
- Coordinates with PMs and stakeholders on reporting and ongoing decision-making

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional roles are expected to participate in planning, delivery, risk management, and release readiness according to their responsibilities and decision authority.
- Clear ownership across these roles helps reduce ambiguity, improve handoffs, and create more predictable execution.

</content