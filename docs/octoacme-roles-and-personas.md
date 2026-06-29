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

## QA/Testing Lead

### Role Summary
QA/Testing Leads ensure quality standards are met, create test plans, and validate that features meet acceptance criteria before release. They work across the project lifecycle to catch defects early and build confidence in product quality.

### Responsibilities
- Define testing strategy and acceptance criteria review
- Create and maintain test plans and test cases
- Execute manual QA and coordinate automated testing
- Identify defects, regression issues, and quality risks
- Validate smoke tests before production deployment
- Participate in acceptance testing with stakeholders
- Report on test coverage and quality metrics

### Goals
- Ensure zero critical bugs reach production
- Improve test coverage and automation rates
- Reduce time spent on manual regression testing
- Enable faster, more confident releases

### Interaction with other roles
- **Developers**: Collaborate on acceptance criteria, test automation, and defect resolution
- **Product Managers**: Validate feature acceptance and prioritize test scenarios
- **Release Managers**: Execute pre-release smoke tests and post-deploy verification
- **Project Managers**: Report quality blockers and risks that impact timelines

### Typical Communication
- Test plans and quality reports in sprint reviews
- Defect logs and regression test results
- Pre-release quality gates and sign-offs

---

## Stakeholder/Sponsor

### Role Summary
Sponsors and key stakeholders provide business context, approvals, and priority guidance. They ensure projects align with organizational goals and communicate outcomes to leadership and other departments.

### Responsibilities
- Define business objectives and success metrics
- Provide approval at key gates (initiation, planning, release)
- Communicate project status to leadership and other departments
- Prioritize competing requests and trade-offs
- Escalate blockers that require executive intervention
- Champion the project and secure necessary resources

### Goals
- Ensure projects deliver business value
- Maintain alignment between technical delivery and business strategy
- Reduce scope creep through clear prioritization
- Enable rapid decision-making on trade-offs

### Interaction with other roles
- **Product Managers**: Align on business objectives and success metrics
- **Project Managers**: Receive status updates and provide strategic guidance
- **All team members**: Provide context and feedback during demos and retrospectives

### Typical Communication
- Monthly stakeholder updates and executive briefings
- Gate approval decisions
- Feedback during demos and milestone reviews

---

## Technical Lead/Architect

### Role Summary
Technical Leads guide architectural decisions, review technical design, and help identify technical risks and dependencies. They ensure the system maintains quality, scalability, and alignment with long-term technical strategy.

### Responsibilities
- Review technical designs and architecture decisions
- Identify scalability, performance, and security concerns
- Mentor developers and guide coding standards
- Help estimate technical complexity and effort
- Identify cross-team dependencies and integration points
- Define technical risk mitigation strategies
- Conduct design reviews and provide technical guidance

### Goals
- Maintain system quality and architectural coherence
- Reduce technical debt and rework
- Enable sustainable delivery velocity
- Share knowledge and build team capability

### Interaction with other roles
- **Developers**: Collaborate on design reviews and technical decisions
- **Project Managers**: Highlight technical risks and dependencies in planning
- **Product Managers**: Advise on technical feasibility of features
- **Security/Compliance Officer**: Ensure security is built into architecture

### Typical Communication
- Technical design reviews and architecture documentation
- Risk assessments and mitigation plans
- Code review feedback and technical mentoring

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security and regulatory requirements, and that incidents are handled appropriately. They embed security thinking throughout the project lifecycle.

### Responsibilities
- Review security requirements and threat models
- Conduct or coordinate security reviews and scans
- Advise on secure design and code practices
- Ensure incident response procedures are followed
- Maintain compliance with regulatory requirements
- Conduct post-incident security reviews
- Provide security training and awareness

### Goals
- Prevent security incidents and data breaches
- Maintain compliance with industry standards
- Enable secure-by-default development practices
- Build security awareness across the team

### Interaction with other roles
- **Developers**: Provide security guidance and code review feedback
- **Project Managers**: Escalate security incidents and ensure response procedures
- **Technical Lead/Architect**: Review architectural security decisions
- **All roles**: Participate in security training and incident response drills

### Typical Communication
- Security review results and compliance reports
- Incident reports and post-mortems
- Security guidance and best practices

---

## Release Manager

### Role Summary
Release Managers coordinate and execute deployments, manage release documentation, and ensure smooth transitions to production. They are the central hub for release planning and execution across teams.

### Responsibilities
- Plan and schedule deployment windows
- Coordinate pre-release checklist and readiness verification
- Execute or oversee deployment automation
- Prepare and distribute release notes
- Manage rollback procedures if needed
- Coordinate post-deployment verification and announcements
- Document lessons learned from releases
- Track deployment metrics and success criteria

### Goals
- Execute zero-downtime or low-impact deployments
- Reduce deployment risk through checklists and automation
- Ensure stakeholders are informed of releases
- Enable rapid response to deployment issues

### Interaction with other roles
- **Developers**: Prepare deployment packages and rollback plans
- **QA/Testing**: Execute smoke tests and deployment verification
- **Project Managers**: Schedule deployments and communicate timelines
- **Stakeholders**: Provide release notifications and status updates
- **Technical Lead**: Validate technical readiness and architecture changes

### Typical Communication
- Release notes and deployment plans
- Pre-deployment readiness checklists
- Post-deployment status updates and announcements

---

## Delivery Lead/Scrum Master

### Role Summary
Delivery Leads facilitate the execution cadence, remove blockers, and help the team maintain velocity and quality. They foster team collaboration, psychological safety, and continuous improvement throughout sprints and releases.

### Responsibilities
- Facilitate daily standups and sprint ceremonies
- Track sprint progress and identify blockers early
- Help remove impediments to progress
- Manage WIP and sprint commitments
- Track and report on velocity and team health metrics
- Promote team collaboration and psychological safety
- Facilitate retrospectives and track action items

### Goals
- Maintain consistent delivery velocity
- Reduce cycle time from planning to release
- Improve team engagement and satisfaction
- Enable rapid escalation and resolution of blockers

### Interaction with other roles
- **All team members**: Facilitate standups, retrospectives, and planning
- **Project Managers**: Report on sprint health and escalate blockers
- **Product Managers**: Facilitate backlog refinement and prioritization
- **Developers**: Support problem-solving and remove technical blockers

### Typical Communication
- Daily standups and sprint status updates
- Velocity and burndown charts
- Retrospective notes and action items

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-reference these personas when reading the other OctoAcme process documents to understand responsibilities and interactions.
- When new processes or workflows are defined, ensure they account for all relevant personas and their interaction points.
