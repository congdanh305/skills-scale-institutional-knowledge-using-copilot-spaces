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

## Release Manager

### Role Summary
Release Managers coordinate the end-to-end release process, ensuring that software is deployed safely, efficiently, and with minimal disruption. They bridge development, operations, and stakeholder communication to manage release schedules and quality gates.

### Responsibilities
- Plan and coordinate release schedules and deployment windows
- Maintain release readiness checklists and ensure all pre-release requirements are met
- Coordinate go/no-go decisions with stakeholders
- Manage release documentation, including release notes and runbooks
- Track deployment metrics and identify process improvements
- Coordinate rollback procedures when issues arise
- Ensure compliance with change management policies

### Goals
- Achieve zero-downtime deployments
- Reduce mean time to deploy (MTTD)
- Minimize post-deployment incidents
- Maintain clear release documentation and audit trails

### Typical Communication
- Pre-release readiness reviews with Project Managers and technical leads
- Release status updates to stakeholders and leadership
- Post-deployment summary reports
- Release retrospectives to identify process improvements

### Touchpoints with Other Roles
- **Developers**: Validates code readiness, CI/CD pipeline status, and technical prerequisites
- **Project Managers**: Aligns on release timelines, risk mitigation, and stakeholder communications
- **Product Managers**: Reviews feature completion, acceptance criteria validation, and release scope
- **Project Sponsor**: Reports on release status, escalates critical issues, and confirms go/no-go decisions
- **Communications Lead**: Coordinates release announcements and customer-facing communications
- **Stakeholders**: Provides release updates, gathers feedback, and manages expectations

---

## Stakeholder

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project's outcome. They provide input, feedback, and approvals at key decision points, and consume project communications to stay informed.

### Responsibilities
- Provide domain expertise and business context
- Review and approve key project deliverables and milestones
- Participate in project reviews and feedback sessions
- Escalate concerns or blockers to Project Sponsors when needed
- Validate that delivered solutions meet business needs

### Goals
- Ensure project outcomes align with business objectives
- Maintain visibility into project progress and risks
- Provide timely feedback to keep the project on track

### Typical Communication
- Monthly stakeholder updates and demos
- Milestone review sessions
- Feedback forms and surveys
- Ad-hoc consultations on specific decisions

### Touchpoints with Other Roles
- **Project Managers**: Receives regular status updates, provides input on priorities and constraints
- **Product Managers**: Validates product direction, provides user feedback and market insights
- **Project Sponsor**: Escalates issues requiring executive decisions or additional resources
- **Communications Lead**: Receives targeted communications based on stakeholder interest areas
- **Release Manager**: Reviews release plans and provides input on deployment timing

---

## Communications Lead

### Role Summary
Communications Leads develop and execute communication strategies for projects, ensuring that the right information reaches the right audiences at the right time. They manage internal and external messaging, coordinate announcements, and maintain communication channels.

### Responsibilities
- Develop project communication plans and strategies
- Create and distribute project updates, announcements, and newsletters
- Manage stakeholder communication matrices and preferences
- Coordinate messaging across teams and departments
- Draft customer-facing release notes and announcements
- Facilitate feedback collection from various audiences
- Ensure consistent messaging and brand alignment

### Goals
- Ensure stakeholders are well-informed and engaged
- Minimize communication gaps and misunderstandings
- Build enthusiasm and support for project deliverables
- Streamline information flow across teams

### Typical Communication
- Stakeholder communication plans and schedules
- Release announcements and change notifications
- Project newsletters and status summaries
- Customer-facing documentation and FAQs

### Touchpoints with Other Roles
- **Project Managers**: Collaborates on status reports and stakeholder communications
- **Product Managers**: Translates product features into customer-facing messaging
- **Release Manager**: Coordinates release announcements and deployment communications
- **Project Sponsor**: Seeks approval for major announcements and messaging strategies
- **Stakeholders**: Delivers targeted communications and gathers feedback
- **Developers**: Obtains technical details for accurate messaging

---

## Project Sponsor

### Role Summary
Project Sponsors are senior leaders who provide executive oversight, secure resources, and make strategic decisions for projects. They champion the project at the leadership level and have ultimate accountability for project success.

### Responsibilities
- Provide strategic direction and align projects with organizational goals
- Secure funding, resources, and executive support
- Make or approve high-impact decisions and trade-offs
- Remove organizational blockers and escalations
- Review project status and hold teams accountable for delivery
- Approve major scope changes and timeline adjustments
- Champion the project with senior leadership and external partners

### Goals
- Ensure project delivers expected business value and ROI
- Maintain alignment with strategic priorities
- Enable teams to execute efficiently by removing obstacles
- Build organizational support for project outcomes

### Typical Communication
- Monthly executive briefings and steering committee meetings
- Escalation reviews and decision forums
- Budget and resource allocation discussions
- Strategic direction and trade-off decisions

### Touchpoints with Other Roles
- **Project Managers**: Reviews project status, approves major changes, resolves escalations
- **Product Managers**: Validates product strategy and business case alignment
- **Release Manager**: Approves go/no-go decisions for critical releases
- **Communications Lead**: Approves major communication strategies and public-facing announcements
- **Stakeholders**: Represents stakeholder interests at executive level and communicates strategic decisions

---

## Role Interaction Matrix

The following matrix shows key interaction points and handoff processes between roles:

| From Role | To Role | Interaction Type | Frequency | Key Handoffs/Decisions |
|-----------|---------|------------------|-----------|------------------------|
| **Developer** | **Project Manager** | Status updates, blockers | Daily/Weekly | Code completion, technical blockers |
| **Developer** | **Release Manager** | Release readiness | Per release | Code freeze, deployment artifacts |
| **Product Manager** | **Project Manager** | Prioritization, scope | Weekly | Backlog updates, scope changes |
| **Product Manager** | **Communications Lead** | Feature messaging | Per release | Feature descriptions, customer value |
| **Project Manager** | **Release Manager** | Release coordination | Per release | Timeline alignment, risk assessment |
| **Project Manager** | **Project Sponsor** | Status & escalations | Weekly/Monthly | Budget approval, scope changes |
| **Project Manager** | **Communications Lead** | Status distribution | Weekly | Stakeholder updates, team communications |
| **Project Manager** | **Stakeholders** | Progress updates | Weekly/Monthly | Status reports, feedback requests |
| **Release Manager** | **Project Sponsor** | Go/no-go decision | Per release | Deployment approval for critical releases |
| **Release Manager** | **Communications Lead** | Release announcements | Per release | Release timing, customer notifications |
| **Release Manager** | **Stakeholders** | Release readiness | Per release | Deployment schedules, impact assessment |
| **Communications Lead** | **Project Sponsor** | Message approval | As needed | Major announcements, strategic communications |
| **Communications Lead** | **Stakeholders** | Information delivery | Scheduled | Updates, newsletters, announcements |
| **Stakeholders** | **Project Sponsor** | Escalations | As needed | Critical concerns, resource requests |

### Decision Rights and Accountabilities

**Clear Decision Authority:**
- **Project Sponsor**: Strategic direction, budget allocation, major scope changes
- **Product Manager**: Feature prioritization, acceptance criteria, product roadmap
- **Project Manager**: Day-to-day execution decisions, resource allocation, schedule management
- **Release Manager**: Deployment timing, release process adherence, rollback decisions
- **Communications Lead**: Message timing and channels, communication strategy

**Escalation Path:**
Team Member → Project Manager → Product Manager/Release Manager (as appropriate) → Project Sponsor

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

**Reference**: This document addresses improvements identified in [Issue #4](https://github.com/congdanh305/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)

