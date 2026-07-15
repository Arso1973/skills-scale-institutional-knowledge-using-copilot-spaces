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

## QA/Testing Specialist

### Role Summary
QA/Testing Specialists ensure product quality through rigorous testing, validation of acceptance criteria, and continuous improvement of test processes. They work closely with developers and product managers to define testability requirements early and prevent defects from reaching production.

### Responsibilities
- Define and execute test plans aligned with acceptance criteria
- Perform manual and automated testing across unit, integration, and end-to-end levels
- Identify, document, and triage defects with clear reproduction steps
- Collaborate with developers on test-driven development and CI/CD quality gates
- Report quality metrics and coverage to the team
- Participate in release readiness reviews and post-deployment verification

### Goals
- Catch defects early to reduce rework and production incidents
- Maintain high test coverage and reliability of automated test suites
- Enable fast, confident releases through comprehensive validation

### Typical Communication
- Sprint planning and backlog refinement (test case discussions)
- QA sign-off in PR reviews and acceptance criteria validation
- Weekly quality metrics reports in delivery syncs
- Release readiness meetings pre-deployment

### Interaction with Other Roles
- **Works with Developers**: Defines testability requirements during planning; reviews PRs for test coverage
- **Works with Product Managers**: Validates acceptance criteria and prioritizes test coverage
- **Works with Technical Leads**: Discusses testing strategy and automation frameworks
- **Coordinates with Security/Compliance Officer**: Ensures security test cases are included in test plans

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, prioritization guidance, and approvals for projects. They represent customer needs, business goals, and organizational constraints, and serve as escalation points for cross-team dependencies and budget/timeline decisions.

### Responsibilities
- Define business objectives and success metrics with Product Manager
- Approve project charter and funding
- Participate in project initiation and major milestones
- Escalate blockers and resolve cross-team conflicts
- Communicate project status and outcomes to broader organization
- Provide feedback on releases and outcomes

### Goals
- Ensure projects deliver business value and meet strategic objectives
- Minimize delays caused by unclear priorities or approval gates
- Enable rapid decision-making on trade-offs and scope changes

### Typical Communication
- Project initiation and go/no-go decisions
- Monthly stakeholder updates and demos
- Ad-hoc escalations for priority conflicts or resource constraints
- Release announcements and post-launch reviews

### Interaction with Other Roles
- **Works with Product Managers**: Co-defines success metrics and business objectives
- **Works with Project Managers**: Reviews risk registers and approves scope changes
- **Works with Development Team**: Attends demos and provides business feedback
- **Escalation Point**: Resolves conflicts between teams and prioritizes cross-team dependencies

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects define system design, technology strategy, and technical standards that guide development. They mentor developers, review architectural decisions, and ensure solutions are scalable, maintainable, and aligned with long-term technical vision.

### Responsibilities
- Design system architecture and technical approach for features
- Review and approve technical designs and code for architectural alignment
- Identify technical risks, dependencies, and mitigation strategies
- Mentor developers on best practices and design patterns
- Maintain technical documentation and standards
- Participate in technology selection and vendor evaluation

### Goals
- Ensure scalable, maintainable, and secure architecture
- Reduce technical debt and rework
- Enable team velocity through clear technical standards and patterns

### Typical Communication
- Design review meetings during planning phase
- PR reviews and architecture feedback
- Risk assessments in project kickoff and planning
- Quarterly technical roadmap discussions

### Interaction with Other Roles
- **Works with Developers**: Mentors on design patterns; reviews architecture in PRs
- **Works with Project Managers**: Identifies technical risks and dependencies
- **Works with QA/Testing Specialist**: Advises on testing strategy and automation frameworks
- **Works with Security/Compliance Officer**: Ensures secure-by-design principles are followed

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team delivery through process coaching, impediment removal, and continuous process improvement. They help teams adopt agile practices, remove blockers, and foster psychological safety and collaboration.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and help remove team impediments and blockers
- Coach teams on agile practices and mindset
- Monitor team velocity and health metrics
- Drive continuous improvement action items from retrospectives
- Escalate process-level blockers to leadership

### Goals
- Maintain team velocity and predictability
- Foster a culture of continuous improvement and psychological safety
- Remove process blockers so teams can focus on delivery

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospectives and action item tracking
- Weekly coaching check-ins with team members
- Stakeholder updates on team health and velocity trends

### Interaction with Other Roles
- **Works with Project Managers**: Coordinates sprint planning and status reporting
- **Works with Development Team**: Removes impediments and facilitates ceremonies
- **Works with Product Managers**: Manages backlog refinement and prioritization discussions
- **Escalation Point**: Escalates process-level blockers to Project Manager and leadership

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security, privacy, and regulatory requirements. They conduct threat assessments, guide secure design practices, and verify compliance before release. They work across all phases of the project lifecycle to embed security into the process.

### Responsibilities
- Participate in design reviews to identify security risks
- Define security acceptance criteria and compliance requirements
- Conduct or oversee security testing (pen tests, scans, code review)
- Review and approve release readiness from security perspective
- Maintain security policies and incident response procedures
- Report on compliance status and audit findings

### Goals
- Prevent security incidents and data breaches
- Ensure projects meet regulatory requirements
- Enable secure-by-design practices across the organization

### Typical Communication
- Security design reviews during planning
- Acceptance criteria definition for security requirements
- Release security sign-off
- Incident response and post-incident reviews

### Interaction with Other Roles
- **Works with Product Managers**: Defines security-related acceptance criteria early
- **Works with Technical Leads**: Advises on secure architecture and technology choices
- **Works with Developers**: Reviews code for security vulnerabilities; advises on secure coding practices
- **Works with QA/Testing Specialist**: Ensures security testing is included in test plans
- **Works with Project Managers**: Reports security risks to risk register; participates in escalation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interaction with Other Roles" section to understand RACI mappings and communication flows across the project lifecycle.
