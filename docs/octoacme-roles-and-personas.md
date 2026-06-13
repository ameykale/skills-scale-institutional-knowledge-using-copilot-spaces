# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Personas

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Key Interactions
- **With Product Manager**: Clarify requirements and acceptance criteria
- **With Engineering Manager**: Technical guidance and mentoring
- **With Product Designer**: Implementation feasibility and design handoff
- **With QA/Testing**: Coordinate test coverage and validation
- **With DevOps/Platform Engineer**: Deployment and environment concerns

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- **With Project Manager**: Plan iterations and manage delivery commitments
- **With Developers**: Refine requirements and acceptance criteria
- **With Product Designer**: Define requirements and validate designs
- **With UX Researcher**: Synthesize user research to inform prioritization
- **With Data Analyst**: Define success metrics and analyze impact

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- **With Product Manager**: Align on priorities and timelines
- **With Delivery Lead**: Ensure sprint commitments and impediment resolution
- **With Engineering Manager**: Resource planning and capacity
- **With Release Manager**: Coordinate release schedules
- **With all roles**: Weekly syncs and escalation path

---

### QA/Testing

#### Role Summary
QA professionals ensure product quality through comprehensive testing, validation of acceptance criteria, and identification of defects before release.

#### Responsibilities
- Develop and execute test plans aligned with acceptance criteria
- Perform manual and automated testing (unit, integration, E2E)
- Identify, document, and triage defects
- Validate fixes and regression testing
- Contribute to security and performance testing

#### Goals
- Catch defects early in the development cycle
- Ensure features meet acceptance criteria before release
- Reduce production incidents and rework
- Maintain product reliability and user trust

#### Typical Communication
- Test case documentation and bug reports
- QA status in standups and sprint reviews
- Release readiness validation

#### Key Interactions
- **With Developers**: Clarify test requirements and coordinate testing
- **With Product Manager**: Understand acceptance criteria and validation needs
- **With Security Engineer**: Coordinate security and compliance testing
- **With DevOps/Platform Engineer**: Coordinate environment setup and smoke tests

---

## Extended Personas

### Delivery Lead

#### Role Summary
Delivery Leads coordinate cross-team execution, maintain sprint commitments, resolve delivery impediments, and ensure integration points are tracked. They work closely with Project Managers and serve as the single point of escalation for team-level blockers.

#### Responsibilities
- Facilitate daily standups and sprint ceremonies
- Identify and escalate delivery impediments within 24 hours
- Track sprint velocity and burndown
- Manage cross-team dependencies and integration points
- Ensure Definition of Done is maintained
- Support retrospectives and action item tracking

#### Goals
- Maintain sprint commitments and predictability
- Reduce time-to-resolution for blockers
- Improve cross-team collaboration and handoffs
- Enable the team to self-organize around shared goals

#### Typical Communication
- Daily standups (15 min)
- Sprint planning and review meetings
- Impediment escalation to Engineering Manager or Product Lead
- Weekly sprint metrics review

#### Key Interactions
- **With Project Manager**: Escalate cross-team and resource blockers
- **With Engineering Manager**: Technical impediment resolution
- **With Developers**: Daily coordination and unblocking
- **With Product Manager**: Sprint prioritization and acceptance validation

---

### Engineering Manager

#### Role Summary
Engineering Managers provide technical leadership, capacity planning, team health, and performance management. They ensure technical debt is prioritized, designs are feasible, and the team has the support needed to succeed.

#### Responsibilities
- Technical leadership and architectural guidance
- Capacity planning and resource allocation
- Team health, onboarding, and performance management
- Design review and technical decision-making
- Technical debt prioritization and mitigation
- Code quality and testing standards enforcement

#### Goals
- Build a high-performing, sustainable engineering team
- Ensure technical solutions are scalable and maintainable
- Balance feature delivery with technical health
- Support team growth and career development

#### Typical Communication
- Weekly 1:1s with direct reports
- Technical design reviews
- Sprint planning and capacity discussion
- Monthly skip-level syncs with leadership

#### Key Interactions
- **With Project Manager**: Resource planning and capacity
- **With Delivery Lead**: Technical impediment resolution
- **With Developers**: Mentorship, career growth, and technical guidance
- **With Product Manager**: Feasibility assessment and technical trade-offs
- **With Security Engineer**: Technical security requirements

---

### Product Designer

#### Role Summary
Product Designers lead user experience and interface design, ensuring products are usable, accessible, and delightful. They own design handoff to engineering and support acceptance criteria validation.

#### Responsibilities
- Lead user research synthesis and design exploration
- Create prototypes, wireframes, and high-fidelity designs
- Ensure accessibility and usability standards
- Own design specification and handoff to engineering
- Participate in design reviews and feedback loops
- Support QA in acceptance validation from a UX perspective

#### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Align design with business goals and user needs
- Maintain design consistency across product

#### Typical Communication
- Design critiques and feedback sessions
- Specification documents and design system updates
- Collaboration with Product Manager on requirements
- Handoff documentation for developers

#### Key Interactions
- **With Product Manager**: Understand requirements and user needs
- **With Developers**: Ensure feasible implementation of designs
- **With UX Researcher**: Validate designs with user research
- **With QA/Testing**: Coordinate acceptance validation

---

### UX Researcher

#### Role Summary
UX Researchers conduct user research, synthesize insights, and validate hypotheses with users. They provide evidence-based input to inform prioritization and design decisions.

#### Responsibilities
- Plan and conduct user research (interviews, surveys, usability tests)
- Synthesize research findings and create actionable insights
- Validate prototypes and proposed solutions with users
- Identify user pain points and opportunities
- Support product strategy with research evidence

#### Goals
- Ensure product decisions are user-centric and evidence-based
- Reduce risk through early validation
- Identify unmet user needs and opportunities
- Support continuous product improvement

#### Typical Communication
- Research plans and methodologies
- Research findings and insight reports
- Presentation to product and design teams
- Ad-hoc validation and feedback sessions

#### Key Interactions
- **With Product Manager**: Inform prioritization with research evidence
- **With Product Designer**: Validate and iterate on designs
- **With Developers**: User research context for implementation
- **With Customer Success Liaison**: Gather customer feedback and pain points

---

### Data Analyst

#### Role Summary
Data Analysts define metrics, create dashboards, and validate success criteria. They support experiments, measure impact, and provide data-driven insights for decision-making.

#### Responsibilities
- Define success metrics aligned with product goals
- Create dashboards and monitoring for key signals
- Design and analyze A/B tests and experiments
- Validate impact of launched features
- Troubleshoot data anomalies and quality issues
- Support post-launch monitoring and incident investigation

#### Goals
- Enable data-driven decision-making across the organization
- Measure product impact and ROI
- Identify optimization opportunities and risks early
- Support continuous improvement through measurement

#### Typical Communication
- Metric definitions and success criteria
- Dashboard reviews and status updates
- Experiment results and recommendations
- Data insights and trend analysis

#### Key Interactions
- **With Product Manager**: Define success metrics and analyze impact
- **With Developers**: Instrument events and data collection
- **With DevOps/Platform Engineer**: Monitor system performance and health
- **With Release Manager**: Post-deployment validation

---

### DevOps / Platform Engineer

#### Role Summary
DevOps and Platform Engineers maintain CI/CD pipelines, deployment automation, monitoring, and runbooks. They ensure safe, reliable deployments and support infrastructure scaling.

#### Responsibilities
- Build and maintain CI/CD pipelines
- Automate deployment processes and rollback procedures
- Monitor system health, performance, and uptime
- Create and maintain operational runbooks
- Support incident response and post-mortems
- Manage infrastructure scaling and security

#### Goals
- Enable fast, safe deployments with minimal risk
- Maintain high system reliability and uptime
- Reduce deployment cycle time
- Support team scalability and self-service deployment

#### Typical Communication
- Deployment changelogs and release notes
- Incident response and status updates
- Infrastructure and scaling documentation
- On-call escalation and runbooks

#### Key Interactions
- **With Developers**: Support local development and testing environments
- **With Release Manager**: Coordinate production deployments
- **With Security Engineer**: Infrastructure security and compliance
- **With Data Analyst**: Monitor performance metrics and system health

---

### Security Engineer

#### Role Summary
Security Engineers conduct threat modeling, security reviews, dependency scanning, and incident response support. They ensure products and processes meet security and compliance standards.

#### Responsibilities
- Conduct threat modeling and security architecture reviews
- Review code and designs for security vulnerabilities
- Manage vulnerability scanning and dependency management
- Support incident response and forensic investigation
- Define and enforce security standards and practices
- Coordinate with compliance and risk management

#### Goals
- Prevent security breaches and data loss
- Reduce vulnerability exposure and risk
- Maintain security posture and compliance
- Build security culture and awareness

#### Typical Communication
- Security review findings and recommendations
- Vulnerability reports and remediation guidance
- Security incident notifications and status
- Security standards and policy documentation

#### Key Interactions
- **With Developers**: Security code review and guidance
- **With Product Manager**: Security requirements and trade-offs
- **With DevOps/Platform Engineer**: Infrastructure and deployment security
- **With QA/Testing**: Security and compliance testing
- **With Project Manager**: Security incident escalation

---

### Release Manager

#### Role Summary
Release Managers coordinate release windows, run deployment checklists, validate post-deploy checks, and communicate releases to stakeholders. They serve as the single point of accountability for release success.

#### Responsibilities
- Schedule and coordinate release windows
- Execute pre-deployment and deployment checklists
- Coordinate with all teams for release readiness
- Validate post-deployment checks and smoke tests
- Manage release notes and communication
- Lead rollback procedures if issues arise
- Post-release retrospectives and action tracking

#### Goals
- Ensure reliable, predictable releases with zero critical incidents
- Reduce deployment risk and rollback frequency
- Maintain stakeholder confidence in releases
- Continuous improvement of release processes

#### Typical Communication
- Release schedules and deployment plans
- Release readiness sign-offs
- Release notes and customer communications
- Post-deployment verification and status

#### Key Interactions
- **With Project Manager**: Release scheduling and coordination
- **With DevOps/Platform Engineer**: Deployment execution and rollback
- **With Developers**: Code readiness and hot-fix support
- **With Data Analyst**: Post-deployment metrics validation
- **With QA/Testing**: Smoke test execution and validation

---

### Customer Success Liaison

#### Role Summary
Customer Success Liaisons represent customer needs, gather feedback, and coordinate support readiness. They bridge the gap between customers and the product team.

#### Responsibilities
- Gather and synthesize customer feedback and pain points
- Represent customer voice in prioritization discussions
- Coordinate support readiness for new features
- Maintain escalation procedures for critical customer issues
- Support account teams with product insights
- Track customer satisfaction metrics

#### Goals
- Ensure product decisions are informed by customer needs
- Reduce customer churn and support burden
- Accelerate time-to-value for customers
- Build customer-centric culture across organization

#### Typical Communication
- Customer feedback summaries and trends
- Support readiness checklists
- Escalation protocols and status
- Customer satisfaction and health metrics

#### Key Interactions
- **With Product Manager**: Surface customer feedback and prioritization input
- **With Product Designer**: Customer perspective on usability and features
- **With Release Manager**: Communicate releases to customers and support teams
- **With Support team**: Gather and relay product insights

---

## How These Personas Work Together

### End-to-End Workflow Example

1. **Initiation Phase**
   - *Product Manager* identifies customer need with input from *Customer Success Liaison*
   - *UX Researcher* validates the opportunity with user research
   - *Project Manager* creates project charter with stakeholder alignment

2. **Planning Phase**
   - *Product Manager* and *UX Researcher* define acceptance criteria
   - *Engineering Manager* and *Delivery Lead* assess feasibility and capacity
   - *Data Analyst* defines success metrics
   - *Security Engineer* identifies security requirements

3. **Design Phase**
   - *Product Designer* creates design specifications
   - *UX Researcher* validates prototypes with users
   - *Developers* provide feasibility feedback
   - *Accessibility specialist* ensures inclusive design

4. **Execution Phase**
   - *Delivery Lead* coordinates daily standups and removes impediments
   - *Developers* implement features with *Engineering Manager* guidance
   - *QA/Testing* validates against acceptance criteria
   - *Security Engineer* conducts code and design reviews

5. **Release Phase**
   - *Release Manager* executes deployment checklist
   - *DevOps/Platform Engineer* manages CI/CD and deployment
   - *Data Analyst* monitors post-deployment metrics
   - *Customer Success Liaison* supports communication to customers

6. **Retrospective Phase**
   - *Project Manager* facilitates retrospective with all contributors
   - *Delivery Lead* tracks action items
   - *Engineering Manager* captures technical learnings
   - *Product Manager* measures impact against success metrics

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
- Reference the "Key Interactions" section to understand handoff points and communication patterns
- Use the "End-to-End Workflow Example" to understand how personas collaborate across project phases
