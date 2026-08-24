# OctoAcme Personas

Last modified: 2026-08-24 by @tonylds1

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
QA/Testing Leads own quality assurance, test planning, and validation of acceptance criteria. They ensure features meet quality standards and user expectations before release.

### Responsibilities
- Define test strategy and test plans aligned with project scope
- Create and maintain test cases and test automation
- Manage QA environments and testing schedules
- Validate that acceptance criteria are met before release
- Identify quality risks early and escalate blockers
- Coordinate with developers on test automation practices
- Report quality metrics and test coverage

### Goals
- Ensure high quality and user confidence in releases
- Catch issues early to reduce defects in production
- Enable fast, reliable releases through effective testing
- Maintain high test coverage and automation

### Typical Communication
- Sprint planning and review meetings
- Daily standups focused on test progress and blockers
- Test reports and quality metrics
- Coordination with developers on test requirements

### Interaction with Existing Roles
- **Developers**: Collaborate on test automation, code review for testability, and defining test requirements
- **Product Managers**: Validate acceptance criteria and ensure tests cover feature requirements
- **Project Managers**: Report quality status and escalate blockers that impact timelines

---

## Technical Lead/Architect

### Role Summary
Technical Leads/Architects provide technical direction, make architectural decisions, and help the team mitigate technical risks. They ensure the system is designed for quality, scalability, and maintainability.

### Responsibilities
- Design system architecture and technical solutions
- Review technical designs and code for alignment with standards
- Identify technical risks and propose mitigations
- Guide developers on architectural decisions and best practices
- Mentor developers and help resolve technical blockers
- Evaluate technology choices and trade-offs
- Ensure system quality, scalability, and long-term maintainability

### Goals
- Ensure system reliability, performance, and maintainability
- Reduce technical debt and design issues
- Enable team to make sound technical decisions
- Accelerate delivery by reducing rework and refactoring

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback on complex changes
- Technical risk assessments and mitigation plans
- Knowledge sharing and mentoring sessions

### Interaction with Existing Roles
- **Developers**: Lead design reviews, provide technical guidance, mentor on best practices
- **Project Managers**: Escalate technical risks, provide effort estimates for architectural work
- **QA/Testing Lead**: Advise on testability and test strategy for complex features

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders/Sponsors provide business context, funding decisions, and executive oversight of projects. They ensure projects align with organizational strategy and deliver business value.

### Responsibilities
- Approve project charters and business cases
- Provide business priorities and context for decisions
- Allocate budget and resources for projects
- Remove organizational blockers and enable team access
- Receive status updates and escalations
- Make go/no-go decisions at key project gates
- Ensure alignment with organizational strategy

### Goals
- Ensure projects deliver measurable business value
- Align project delivery with organizational strategy
- Maximize return on investment
- Enable efficient resource allocation

### Typical Communication
- Project kickoff and approval meetings
- Monthly or quarterly stakeholder updates
- Milestone reviews and decision gates
- Escalation paths for business-impacting issues

### Interaction with Existing Roles
- **Project Managers**: Receive status reports, make prioritization decisions, approve key milestones
- **Product Managers**: Review business value and strategic alignment, approve roadmap prioritization
- **Development Team**: Provide business context and priorities at project initiation

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters/Agile Coaches facilitate agile ceremonies, remove process blockers, and coach the team on agile practices. They foster psychological safety and optimize team flow and velocity.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Protect team from interruptions and maintain focus on sprint goals
- Identify and help remove process blockers and impediments
- Coach team on agile practices and continuous improvement
- Track and optimize team velocity and throughput
- Foster psychological safety and encourage candid feedback
- Help team adopt and adapt agile practices

### Goals
- Optimize team velocity and delivery flow
- Foster psychological safety and team morale
- Continuously improve processes and practices
- Enable self-organizing teams

### Typical Communication
- Facilitation of all agile ceremonies
- One-on-ones with team members
- Retrospective notes and action items
- Coaching on agile practices

### Interaction with Existing Roles
- **Project Managers**: Collaborate on process effectiveness and team health
- **Development Team**: Facilitate ceremonies, coach on agile practices, help resolve blockers
- **Product Managers**: Coordinate on backlog refinement and sprint planning

---

## UX/Design Lead

### Role Summary
UX/Design Leads ensure features are usable, accessible, and aligned with the product vision. They conduct user research, create designs, and define design standards across the team.

### Responsibilities
- Conduct user research and validate design assumptions
- Create designs, prototypes, and wireframes
- Define design standards and style guides
- Validate usability and accessibility of features
- Collaborate with product and engineering on design trade-offs
- Provide design feedback and acceptance criteria to developers
- Ensure consistent user experience across products

### Goals
- Deliver user-centered solutions that meet customer needs
- Maintain design consistency and quality
- Reduce rework from design issues
- Maximize user satisfaction and adoption

### Typical Communication
- Design reviews and critique sessions
- Collaboration with product and engineering
- Usability testing and research findings
- Design specifications and handoffs

### Interaction with Existing Roles
- **Product Managers**: Collaborate on requirements, validate user research findings, align on design direction
- **Developers**: Provide design specifications, conduct design reviews, define acceptance criteria
- **QA/Testing Lead**: Define accessibility requirements and usability test scenarios

---

## Operations/DevOps Engineer

### Role Summary
Operations/DevOps Engineers manage infrastructure, deployment pipelines, monitoring, and operational excellence. They enable fast, reliable deployments and maintain system reliability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage production and staging environments
- Configure monitoring, logging, and alerting
- Execute deployments and rollbacks
- Manage infrastructure and resource allocation
- Troubleshoot operational issues and incidents
- Document operational procedures and runbooks
- Coordinate disaster recovery and business continuity

### Goals
- Enable fast, reliable deployments
- Maintain high system availability and performance
- Reduce manual work through automation
- Enable incident response and recovery

### Typical Communication
- Deployment coordination and planning
- Infrastructure and scaling discussions
- Incident response and post-mortems
- Operational metrics and alerts

### Interaction with Existing Roles
- **Developers**: Collaborate on CI/CD practices, environment setup, and deployment standards
- **Project Managers**: Execute deployment checklist, coordinate deployment windows, report operational status
- **QA/Testing Lead**: Manage QA environments and support smoke testing before releases

---

## Security Lead

### Role Summary
Security Leads ensure security is designed into features and processes from the start. They conduct threat modeling, security reviews, and coordinate incident response to reduce organizational risk.

### Responsibilities
- Conduct threat modeling and security architecture reviews
- Perform security assessments of high-risk features
- Configure and monitor security scanning in CI/CD
- Coordinate incident response and investigation
- Define security standards and best practices
- Provide security guidance to development team
- Ensure compliance with security policies and regulations
- Lead blameless security incident retrospectives

### Goals
- Reduce security risk and vulnerabilities
- Enable secure, compliant product delivery
- Build security culture within the team
- Minimize security incident impact

### Typical Communication
- Security design reviews for high-risk changes
- Security incident response and communications
- Security metrics and vulnerability reports
- Security training and best practices sharing

### Interaction with Existing Roles
- **Developers**: Provide security guidance, review high-risk code, conduct security training
- **Technical Lead/Architect**: Collaborate on security architecture and threat modeling
- **Project Managers**: Escalate security risks, coordinate security incident response
- **Operations/DevOps Engineer**: Configure security scanning and monitoring in CI/CD pipelines

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When creating issues or planning work, assign clear ownership using these personas.
- Use the interaction patterns to identify cross-functional dependencies and communication needs.
