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

### Interactions with Other Roles
- **QA Lead**: Provide testable code; receive feedback on edge cases and quality issues
- **UX Designer**: Collaborate on implementation details; provide technical feasibility input
- **DevOps Engineer**: Coordinate on deployment requirements and CI/CD pipeline updates
- **Security Lead**: Incorporate security reviews; ask for guidance on secure coding practices

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

### Interactions with Other Roles
- **Project Manager**: Align on priorities and timelines; flag scope changes
- **UX Designer**: Define user needs; validate designs and flows
- **Stakeholder Representatives**: Gather requirements; communicate priorities and trade-offs
- **QA Lead**: Define acceptance criteria; review release readiness

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

### Interactions with Other Roles
- **Product Manager**: Align on scope and timeline; escalate blockers
- **DevOps Engineer**: Coordinate deployment windows and release schedules
- **Stakeholder Representatives**: Provide status updates and escalations
- **All Team Members**: Facilitate standups and planning sessions; monitor progress

---

## QA Lead

### Role Summary
QA Leads own the test strategy and quality assurance approach for a project. They ensure that acceptance criteria are verifiable, test coverage is adequate, and quality standards are met before release.

### Responsibilities
- Define and maintain the test strategy (unit, integration, end-to-end, security)
- Create and prioritize test cases based on acceptance criteria
- Coordinate QA activities and manual testing efforts
- Establish Definition of Done standards for testability
- Report on test coverage and quality metrics
- Identify blockers and quality risks early

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce defects reaching production
- Enable fast, confident releases

### Typical Communication
- Quality status in weekly syncs
- Test plans and coverage reports
- Bug reports and release readiness assessments

### Interactions with Other Roles
- **Developers**: Provide testability feedback; receive code for quality assurance
- **Product Manager**: Clarify acceptance criteria; ensure requirements are testable
- **Project Manager**: Report blockers; coordinate test timelines
- **Security Lead**: Plan security testing activities; share results
- **DevOps Engineer**: Prepare test environments; automate regression testing

---

## UX Designer

### Role Summary
UX Designers design interfaces, user flows, and experiences. They collaborate with product and development teams to ensure solutions are usable and meet user needs.

### Responsibilities
- Conduct user research and define user flows
- Design interfaces and interaction patterns
- Establish and maintain usability standards
- Validate designs with users and stakeholders
- Provide design specs and handoff documentation to developers
- Incorporate feedback from QA and product teams

### Goals
- Ensure features are intuitive and meet user expectations
- Reduce usability issues and support burden
- Drive user satisfaction and adoption

### Typical Communication
- Design specs and wireframes
- User research findings and feedback
- Design review meetings with stakeholders and developers

### Interactions with Other Roles
- **Product Manager**: Align on user needs and priorities; validate solutions
- **Developers**: Provide detailed design specs; discuss technical feasibility
- **QA Lead**: Include usability in acceptance criteria
- **Stakeholder Representatives**: Gather domain-specific feedback; incorporate constraints

---

## DevOps Engineer

### Role Summary
DevOps Engineers maintain CI/CD pipelines, ensure smooth deployments, and contribute to observability and incident response. They enable reliable, automated delivery of features.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Automate testing and deployment processes
- Manage deployment environments and infrastructure
- Set up monitoring, logging, and alerting
- Document and execute deployment and rollback procedures
- Contribute to incident response playbooks

### Goals
- Enable fast, reliable, automated deployments
- Reduce deployment errors and downtime
- Maintain observability and incident response readiness

### Typical Communication
- Deployment status and release notes
- Infrastructure and pipeline changes
- Incident post-mortems and action items

### Interactions with Other Roles
- **Developers**: Support automated testing; provide deployment guidance
- **Project Manager**: Coordinate deployment windows; manage release schedules
- **QA Lead**: Provide test environments; enable automated testing
- **Security Lead**: Implement security scanning in pipelines; support incident response

---

## Security Lead

### Role Summary
Security Leads advise on security best practices, review code for vulnerabilities, and help establish incident response plans. They ensure projects meet security standards and compliance requirements.

### Responsibilities
- Establish and communicate security requirements for projects
- Review code and architecture for vulnerabilities
- Advise on secure coding practices and frameworks
- Coordinate security testing and penetration testing
- Establish incident response procedures and escalation paths
- Monitor compliance with security policies

### Goals
- Prevent security breaches and vulnerabilities
- Ensure compliance with organizational policies
- Enable rapid incident response and recovery

### Typical Communication
- Security requirements and best practices guidance
- Code review comments and vulnerability reports
- Security testing plans and incident response procedures

### Interactions with Other Roles
- **Developers**: Provide secure coding guidance; review code for vulnerabilities
- **QA Lead**: Plan security testing; share vulnerability findings
- **DevOps Engineer**: Implement security scanning in pipelines; support incident response
- **Project Manager**: Escalate security risks; advise on incident response
- **Stakeholder Representatives**: Report compliance status; communicate security incidents

---

## Stakeholder Representatives

### Role Summary
Stakeholder Representatives provide real-world feedback, make priority decisions on trade-offs, and communicate domain-specific constraints. They bridge business needs and technical delivery.

### Responsibilities
- Articulate business requirements and constraints
- Provide feedback on proposed solutions and trade-offs
- Make priority decisions when conflicts arise
- Communicate project status to their stakeholder groups
- Identify and escalate business risks
- Validate that solutions meet business and user needs

### Goals
- Ensure delivery aligns with business strategy and needs
- Reduce misalignment between teams and stakeholders
- Enable fast, informed decision-making

### Typical Communication
- Stakeholder briefings and status updates
- Feedback on designs and prototypes
- Trade-off discussions and priority calls
- Escalations and risk reporting

### Interactions with Other Roles
- **Product Manager**: Provide business context and priorities; validate solutions
- **Project Manager**: Receive status updates; escalate blockers
- **UX Designer**: Provide domain feedback on usability; validate user flows
- **Developers**: Clarify requirements; provide feedback on feasibility
- **All Team Members**: Participate in kickoffs, reviews, and retrospectives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" sections to understand cross-functional dependencies and communication patterns.
