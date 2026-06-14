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

## Additional Personas

The following personas represent operational and cross-functional roles that often emerge in larger or more complex OctoAcme projects. Including these personas in your project planning improves clarity of ownership, reduces handoff ambiguity, and accelerates onboarding.

### Technical Program Manager (TPM)

#### Role Summary
Technical Program Managers coordinate cross-team technical dependencies and delivery for complex initiatives. They bridge technical and business concerns to ensure seamless execution across multiple engineering teams.

#### Responsibilities
- Drive dependency tracking and critical path management
- Coordinate schedule harmonization across teams
- Facilitate risk coordination and mitigation planning
- Run integrated status syncs with multiple technical stakeholders
- Escalate technical blockers and resource constraints
- Maintain cross-team project roadmaps and milestones

#### Goals
- Reduce dependencies and bottlenecks in delivery
- Improve predictability and on-time delivery across teams
- Maintain alignment on technical trade-offs and decisions

#### Interaction Patterns
- Works closely with **Product Manager** on prioritization and trade-offs
- Partners with **Product Lead** on outcome alignment
- Collaborates with **Engineering Lead** on technical feasibility and architecture decisions
- Coordinates with **Release Manager** on deployment windows and rollback scenarios
- Engages **Project Manager** on overall project timeline and scope

#### Typical Communication
- Cross-team dependency tracking and escalation
- Technical architecture and integration reviews
- Resource planning and conflict resolution meetings
- Risk and mitigation planning sessions

---

### Engineering Lead / Tech Lead

#### Role Summary
Engineering Leads provide technical leadership, mentorship, and design direction for the delivery team. They ensure technical decisions align with project goals while maintaining code quality and architecture standards.

#### Responsibilities
- Approve and guide architecture and design decisions
- Pair with developers for complex technical challenges
- Own technical debt prioritization and remediation
- Mentor and develop team members
- Conduct code and design reviews
- Identify and communicate technical risks early

#### Goals
- Maintain high code quality and architectural consistency
- Reduce technical debt and rework
- Build a high-performing, collaborative engineering team
- Enable faster feature delivery through good design

#### Interaction Patterns
- Collaborates with **Developers** on design and implementation
- Works with **Technical Program Manager** on architecture decisions and dependencies
- Partners with **QA Lead** to ensure testability and quality standards
- Engages **Project Manager** on technical timeline and risk mitigation
- Reviews work with **Product Manager** to ensure alignment with requirements

#### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and feedback
- One-on-ones and team technical syncs
- Risk identification and mitigation planning

---

### Release Manager

#### Role Summary
Release Managers own release scheduling, deployment coordination, and rollback planning. They ensure releases are predictable, well-communicated, and minimize production risk.

#### Responsibilities
- Coordinate release windows and schedules
- Verify pre-release and post-deploy verification checklists
- Communicate release status and rollback scenarios
- Own incident communication during deployments
- Maintain release documentation and runbooks
- Plan and execute rollback procedures when necessary

#### Goals
- Reduce deployment risk and production incidents
- Improve release predictability and communication
- Enable rapid rollback if issues occur
- Maintain clear visibility into release status

#### Interaction Patterns
- Works with **Project Manager** on release timelines and stakeholder communication
- Coordinates with **Technical Program Manager** on cross-team deployment sequencing
- Partners with **Engineering Lead** on deployment readiness and technical validation
- Engages **Support Lead** on post-release support and incident response
- Communicates with **Product Manager** on feature delivery status

#### Typical Communication
- Release planning and coordination meetings
- Pre-release verification checklists and sign-offs
- Deployment day communications and status updates
- Post-incident retrospectives and rollback documentation

---

### Support Lead / On-call Liaison

#### Role Summary
Support Leads bridge engineering and customer support to ensure timely incident handling, effective communication, and resolution. They maintain runbooks and escalation paths while helping engineering learn from production issues.

#### Responsibilities
- Own incident triage and customer communication during outages
- Coordinate between engineering and support teams
- Document post-incident action items and learnings
- Maintain and improve runbooks for common issues
- Contribute to on-call rotations and incident response
- Identify patterns in support tickets for product improvements

#### Goals
- Reduce incident resolution time
- Improve customer communication during incidents
- Enable faster learning and improvement from production issues
- Build trust between support and engineering teams

#### Interaction Patterns
- Works with **Developers** and **Engineering Lead** on incident response and remediation
- Coordinates with **Release Manager** on deployment communication and rollback decisions
- Engages **Security Liaison** on security-related incidents
- Partners with **Project Manager** on incident tracking and follow-up
- Communicates with **Stakeholders** during critical outages

#### Typical Communication
- Incident response and escalation channels
- Post-incident retrospectives and documentation
- Runbook updates and maintenance
- Regular communication with support team on common issues

---

### Security Liaison

#### Role Summary
Security Liaisons ensure security and compliance considerations are integrated throughout project planning and release. They serve as advocates for security best practices and help teams move fast without compromising safety.

#### Responsibilities
- Coordinate security reviews and threat modeling sessions
- Track security findings and remediation efforts
- Verify security fixes are complete before release
- Maintain security policies and compliance documentation
- Facilitate security training and awareness
- Escalate critical security issues to leadership

#### Goals
- Reduce security vulnerabilities and compliance gaps
- Enable secure delivery without slowing teams down
- Build security awareness across the organization
- Maintain customer trust through secure practices

#### Interaction Patterns
- Works with **Engineering Lead** on secure design and architecture decisions
- Partners with **Release Manager** on security sign-off before deployment
- Engages **Product Manager** on security implications of features
- Collaborates with **Technical Program Manager** on cross-team security coordination
- Communicates with **Stakeholders** on compliance and risk posture

#### Typical Communication
- Security review and threat modeling sessions
- Vulnerability tracking and remediation follow-up
- Release security sign-off and approval
- Security incident response and escalation

---

### UX Researcher / Design Liaison

#### Role Summary
UX Researchers and Design Liaisons provide user research input and ensure design alignment with product goals. They advocate for user needs and help teams validate that features meet customer expectations.

#### Responsibilities
- Conduct user research and usability testing
- Validate acceptance criteria against actual user needs
- Provide design assets and interaction guidance
- Identify usability gaps and improvement opportunities
- Document user feedback and insights
- Collaborate on accessibility and inclusive design

#### Goals
- Ensure features deliver real customer value
- Reduce rework from misaligned designs
- Improve user satisfaction and adoption
- Build user empathy across the team

#### Interaction Patterns
- Works with **Product Manager** on feature prioritization and validation
- Collaborates with **Developers** on design implementation and feasibility
- Partners with **QA Lead** on acceptance criteria and user scenarios
- Engages **Engineering Lead** on technical constraints and design trade-offs
- Communicates **Stakeholders** on user research findings and recommendations

#### Typical Communication
- User research and usability testing sessions
- Design review and feedback meetings
- User insight presentations and documentation
- Acceptance criteria and scenario validation workshops

---

## Interaction Matrix: Who to Contact for Common Decisions

| Decision or Blocker | Primary Owner | Escalation Path |
|---|---|---|
| What features to prioritize? | Product Manager | Sponsor / Product Lead |
| How should we build this? | Engineering Lead | Technical Program Manager → CTO |
| When can we release? | Release Manager | Project Manager → Sponsor |
| Is this production-ready? | QA Lead | Engineering Lead → Project Manager |
| How do users feel about this? | UX Researcher | Product Manager → Sponsor |
| What are the security implications? | Security Liaison | CISO / Security Lead |
| Customer impact during incident? | Support Lead | Project Manager → Sponsor |
| Can we meet the timeline? | Project Manager | Sponsor / Product Lead |
| Cross-team dependencies resolved? | Technical Program Manager | VP Engineering / CTO |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning a project, identify which personas are relevant and clarify their roles upfront to reduce ambiguity.
