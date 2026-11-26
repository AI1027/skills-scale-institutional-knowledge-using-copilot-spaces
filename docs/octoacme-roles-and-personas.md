# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles describe capabilities and accountabilities, not necessarily separate positions: one person may cover multiple roles when appropriate, but each responsibility should have a named owner for the project.

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

## UX/Design Leads

### Role Summary
UX/Design Leads are accountable for coherent, accessible user experiences and design decisions across the project. Depending on the team, this responsibility may be held by a designer or another team member with the appropriate expertise.

### Responsibilities
- Lead user research, interaction and visual design, and accessibility considerations
- Translate user needs and product goals into design concepts and usability requirements
- Maintain design artifacts and communicate design decisions and trade-offs
- Validate designs with users and incorporate feedback

### Goals
- Make product experiences useful, understandable, inclusive, and consistent
- Identify usability issues early, before they become costly implementation changes

### Typical Communication
- Design reviews and user research readouts
- Design specifications and accessibility guidance
- Collaboration during discovery, backlog refinement, and acceptance reviews

### Interactions with Existing Roles
- Partners with Product Managers to frame user problems, align designs with desired outcomes, and refine acceptance criteria
- Works with Developers and Engineering/Technical Leads to assess feasibility and resolve implementation questions
- Collaborates with QA/Testing to include usability and accessibility in test plans and acceptance checks
- Shares research findings with Project Managers and stakeholders to inform planning and decisions

---

## Engineering/Technical Leads

### Role Summary
Engineering/Technical Leads guide technical direction and engineering practices for a project or workstream. They provide technical coordination without replacing the delivery responsibilities of the Project Manager or the product decisions of the Product Manager.

### Responsibilities
- Guide architecture, technical design, and engineering standards
- Facilitate technical reviews and identify technical risks and dependencies
- Support Developers with implementation decisions, estimates, and quality practices
- Coordinate technical handoffs and surface trade-offs that affect scope, sequence, or timelines

### Goals
- Deliver maintainable, secure, reliable solutions
- Make technical decisions and dependencies visible early

### Typical Communication
- Technical design documents and architecture reviews
- Engineering planning, code reviews, and dependency discussions
- Risk and status updates with the Project Manager and Product Manager

### Interactions with Existing Roles
- Works with Developers to clarify design, review implementation, and resolve technical blockers
- Advises Product Managers on feasibility and technical trade-offs while leaving product priority decisions with them
- Partners with Project Managers to make technical dependencies, risks, and sequencing visible in plans
- Coordinates with QA/Testing, Security Leads, and Release/DevOps Engineers on testability, security, and operational readiness

---

## Release/DevOps Engineers

### Role Summary
Release/DevOps Engineers support reliable delivery to production through deployment automation, environment readiness, observability, and operational practices. These responsibilities may be shared with engineering or operations team members.

### Responsibilities
- Maintain or improve build, deployment, and release automation
- Prepare and verify deployment environments and release procedures
- Ensure monitoring, alerting, and rollback or mitigation approaches are ready
- Help investigate deployment and operational issues and document runbooks

### Goals
- Make releases repeatable, observable, and recoverable
- Reduce deployment risk and time to restore service

### Typical Communication
- Release-readiness reviews and deployment plans
- Pipeline, environment, monitoring, and runbook documentation
- Incident and post-deployment updates

### Interactions with Existing Roles
- Partners with Developers and Engineering/Technical Leads on build pipelines, release readiness, and operational design
- Coordinates with QA/Testing on staging environments, smoke tests, and verification criteria
- Works with Project Managers on deployment windows, dependencies, risks, and status communications
- Provides Product Managers and Support/Customer Success Representatives with release timing and service-impact information

---

## Data/Analytics Leads

### Role Summary
Data/Analytics Leads help teams define and use trustworthy evidence to understand product outcomes and user behavior.

### Responsibilities
- Translate success metrics into measurement plans and instrumentation requirements
- Advise on data quality, privacy-aware collection, and metric definitions
- Build or coordinate dashboards and analysis for releases or experiments
- Explain findings, limitations, and recommendations to the team

### Goals
- Make project outcomes measurable and interpretable
- Help teams use reliable evidence to learn and adjust priorities

### Typical Communication
- Measurement plans and metric definitions
- Dashboard reviews and experiment readouts
- Collaboration during discovery, planning, and post-release evaluation

### Interactions with Existing Roles
- Partners with Product Managers to define success metrics and interpret outcomes against product goals
- Works with Developers and Engineering/Technical Leads to implement and validate instrumentation
- Collaborates with UX/Design Leads on research questions and user behavior insights
- Shares evidence and caveats with Project Managers and stakeholders to support transparent decisions and reporting

---

## Security Leads

### Role Summary
Security Leads guide security and privacy risk management for the project and help teams meet applicable security requirements.

### Responsibilities
- Clarify security requirements and advise on threat modeling and secure design
- Identify, assess, and track security risks and remediation actions
- Coordinate security reviews and help teams respond to security findings or incidents
- Advise on security readiness and escalation paths before release

### Goals
- Reduce security and privacy risks throughout the delivery lifecycle
- Make security responsibilities and release-related risks explicit

### Typical Communication
- Threat models, security review findings, and remediation tracking
- Security requirements during planning and design reviews
- Security incident coordination through the established incident process

### Interactions with Existing Roles
- Works with Engineering/Technical Leads and Developers to build and verify appropriate security controls
- Advises Product Managers on security implications and Project Managers on risk ownership, escalation, and release gates
- Coordinates with QA/Testing and Release/DevOps Engineers on security testing and deployment controls
- Follows the security incident runbook and works with the relevant on-call responders when incidents occur

---

## Support/Customer Success Representatives

### Role Summary
Support/Customer Success Representatives bring customer and operational support needs into project decisions and help prepare teams to support delivered changes.

### Responsibilities
- Share customer feedback, recurring issues, and support trends
- Identify support impacts and readiness needs for planned changes
- Help prepare support guidance, known-issue information, and escalation routes
- Relay post-release feedback and incidents to the delivery team

### Goals
- Ensure customers and support teams can understand and use changes successfully
- Close the feedback loop between users and the product team

### Typical Communication
- Customer feedback summaries and support-readiness reviews
- Knowledge-base articles, FAQs, and release communications
- Post-release issue and trend reports

### Interactions with Existing Roles
- Partners with Product Managers to surface customer needs and validate product impact
- Works with Project Managers on stakeholder updates, rollout coordination, and support dependencies
- Coordinates with Developers and Engineering/Technical Leads on issue triage and known technical limitations
- Collaborates with Release/DevOps Engineers on operational notices and with QA/Testing on customer-relevant acceptance scenarios

---

## Change/Training Coordinators

### Role Summary
Change/Training Coordinators (when needed) prepare affected users and teams to adopt a change through enablement, communications, and training.

### Responsibilities
- Identify audiences, adoption impacts, and readiness needs
- Plan training, documentation, and rollout communications
- Coordinate enablement activities and gather adoption feedback
- Track readiness actions and escalate gaps that could affect rollout

### Goals
- Support smooth adoption and reduce confusion or disruption during rollout
- Ensure users know what is changing and where to get help

### Typical Communication
- Change impact and readiness plans
- Training materials, release communications, and adoption feedback
- Coordination with support teams before and after rollout

### Interactions with Existing Roles
- Partners with Product Managers to explain the purpose and expected value of a change
- Coordinates with Project Managers on rollout milestones, stakeholders, and readiness risks
- Works with Support/Customer Success Representatives to align training, help materials, and post-release support
- Consults Developers and QA/Testing for accurate product guidance and known limitations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Engage roles according to project needs; smaller teams may combine responsibilities, but each responsibility should have a clear owner and handoffs should be explicit.
- The expanded role model is intended to make decisions, dependencies, and accountability clearer, helping teams identify usability, technical, security, measurement, release, support, and adoption needs earlier and improve delivery outcomes.
