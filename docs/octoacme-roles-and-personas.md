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
QA/Testing Leads ensure product quality meets acceptance criteria and customer expectations. They own the quality strategy, test planning, and acceptance validation across all delivery phases.

### Responsibilities
- Define quality standards and acceptance criteria frameworks
- Plan and execute comprehensive testing strategy (unit, integration, end-to-end, security, performance)
- Identify quality risks and propose mitigations
- Approve features as meeting acceptance criteria before release
- Report quality metrics, defect trends, and testing status to Product Manager and Project Manager
- Mentor team members on testing best practices and quality assurance
- Establish and maintain test automation infrastructure

### Goals
- Ensure product quality meets customer expectations and regulatory requirements
- Reduce bugs and rework in production
- Enable faster, more confident deployments through robust testing

### Typical Communication
- Quality status updates in weekly syncs and standups
- Testing plans and test case documentation
- Defect reports and quality metrics dashboards
- Collaboration sessions with Developers on testability requirements

### Interactions with Other Roles
- **Works with Developers**: Defines testability requirements, reviews test design, partners on test automation
- **Collaborates with Product Manager**: Refines acceptance criteria, validates feature completeness
- **Reports to Project Manager**: Quality status, risks, and readiness for release milestones
- **Partners with Release Manager**: Provides release readiness assessment and testing sign-off
- **Advises Technical Architect**: Quality and testability implications of architectural decisions

---

## Technical Architect

### Role Summary
Technical Architects provide technical direction and ensure system design supports current and future needs. They review technical decisions, identify architectural risks, and mentor the team on engineering best practices.

### Responsibilities
- Review and approve technical designs and architecture decisions for scalability and maintainability
- Identify technical risks and propose mitigation strategies
- Mentor developers on architecture principles, design patterns, and engineering best practices
- Ensure scalability, security, performance, and maintainability considerations are addressed
- Support estimation and feasibility assessment with technical insights
- Define and enforce coding standards and architectural guidelines
- Evaluate technology selections and tooling decisions

### Goals
- Build systems that are scalable, maintainable, and resilient
- Reduce technical debt and refactoring needs
- Enable team growth through mentorship and knowledge sharing
- Align technical decisions with business objectives

### Typical Communication
- Technical design reviews and architecture documentation
- Mentoring sessions and code review guidance
- Risk assessments and technical feasibility studies
- Escalations to Product Lead on technical trade-offs

### Interactions with Other Roles
- **Guides Developers**: Code reviews, design feedback, technical mentoring
- **Advises Project Manager**: Technical feasibility, effort estimation, and risk assessment
- **Partners with QA/Testing Lead**: Testability requirements and quality architecture
- **Collaborates with Product Manager**: Technical trade-offs impacting features and timelines
- **Escalates to Sponsor**: Strategic technical risks and architectural decisions affecting business

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and coach the team on agile practices. They serve the team and organization by enabling effective collaboration, continuous improvement, and adherence to agile principles.

### Responsibilities
- Facilitate agile ceremonies (standups, planning, retrospectives, demos) and ensure effectiveness
- Remove blockers and impediments that prevent team progress
- Coach team members and stakeholders on agile practices and principles
- Track sprint metrics (velocity, burn-down) and support process improvements
- Protect team focus and manage scope creep during sprints
- Foster psychological safety and encourage open communication
- Help resolve conflicts and facilitate difficult conversations

### Goals
- Maximize team velocity and sustainable pace
- Build a high-performing, collaborative team culture
- Continuously improve processes and practices
- Ensure transparency and stakeholder alignment

### Typical Communication
- Facilitating daily standups and sprint ceremonies
- Sprint metrics and retrospective action items
- One-on-one coaching conversations
- Process improvement recommendations

### Interactions with Other Roles
- **Supports all team members**: Removes blockers, facilitates communication, coaches on agile practices
- **Works with Project Manager**: Coordinates on sprint planning, timeline management, and escalations
- **Partners with Product Manager**: Helps clarify requirements, manages backlog refinement
- **Coaches Developers**: Encourages technical excellence, supports time-boxing, manages WIP
- **Supports QA/Testing Lead**: Integrates quality gates into sprint ceremonies

---

## Release Manager

### Role Summary
Release Managers coordinate all release activities to ensure smooth, reliable deployments. They manage release planning, verify readiness, orchestrate deployment execution, and communicate status to stakeholders.

### Responsibilities
- Create and maintain release plans, deployment schedules, and rollback procedures
- Verify all pre-release requirements are met (testing complete, documentation ready, rollback plan approved)
- Coordinate deployment execution across environments (staging, production)
- Run post-deployment verifications and smoke tests
- Communicate release status, known issues, and deployment windows to stakeholders and support teams
- Manage incident response and rollback decisions if deployment issues occur
- Maintain release notes and deployment documentation
- Track release metrics and post-deployment stability

### Goals
- Enable reliable, predictable deployments with minimal risk
- Reduce deployment-related incidents and downtime
- Maintain clear communication with all stakeholders during releases
- Support rapid iteration while ensuring production stability

### Typical Communication
- Release plans and deployment schedules
- Pre-release checklists and readiness reports
- Deployment status updates and incident notifications
- Post-release retrospectives and lessons learned

### Interactions with Other Roles
- **Works with Project Manager**: Release scheduling, milestone planning, and stakeholder communication
- **Coordinates with QA/Testing Lead**: Release readiness, testing sign-off, and final quality verification
- **Partners with Developers**: Deployment procedures, rollback coordination, and production support
- **Collaborates with Technical Architect**: Infrastructure readiness and deployment architecture
- **Reports to Product Manager and Sponsor**: Release status, business impact, and risk mitigation

---

## Stakeholder / Sponsor

### Role Summary
Sponsors provide business context, strategic direction, and decision-making authority. They represent business needs, approve scope and investment, and ensure project alignment with organizational goals.

### Responsibilities
- Define business objectives and success metrics for projects
- Approve project scope, budget, and resource allocation
- Prioritize competing initiatives and make strategic trade-off decisions
- Review and approve significant scope changes or timeline impacts
- Communicate project status and outcomes to executive leadership
- Unblock organizational and cross-team dependencies
- Provide regular feedback and course correction

### Goals
- Ensure projects deliver business value and ROI
- Align project execution with strategic priorities
- Make timely decisions to minimize delays and scope creep
- Communicate outcomes to stakeholders and leadership

### Typical Communication
- Monthly or milestone-based status updates
- Scope change approvals and decision documentation
- Strategic guidance and business context
- Executive briefings and board communications

### Interactions with Other Roles
- **Provides direction to Product Manager**: Business goals, priorities, and strategic constraints
- **Reviews with Project Manager**: Project status, risks, and major milestone approvals
- **Escalation point for all roles**: Final decision authority on scope, budget, and timeline conflicts
- **Collaborates with Technical Architect**: Strategic implications of technical decisions
- **Works with Release Manager**: Final approval on release timing and business announcements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
