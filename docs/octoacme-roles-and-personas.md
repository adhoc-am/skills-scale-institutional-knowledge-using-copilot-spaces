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

## Risk Owner

### Role Summary
Risk Owner is responsible for identifying, assessing, and managing risks throughout the project lifecycle. They maintain the risk register and coordinate mitigation strategies to ensure project success.

### Responsibilities
- Identify and document risks during planning and execution phases
- Assess risk impact and likelihood, maintaining the risk register
- Develop and coordinate mitigation plans with relevant stakeholders
- Monitor risk status and report on risk trends
- Escalate critical risks to Steering Group and Stakeholder Liaison
- Facilitate risk review sessions with the project team

### Goals
- Proactively identify and mitigate project risks
- Minimize impact of risks on project delivery
- Ensure transparency in risk visibility across stakeholders
- Build organizational risk awareness and preparedness

### Typical Communication
- Weekly risk reviews with Project Lead and Product Owner
- Risk register updates and escalation reports
- Monthly risk briefings to steering committee
- Ad-hoc alerts for newly identified high-priority risks

### Key Interactions
- **Project Manager**: Collaborates on risk assessment and mitigation planning
- **Product Owner**: Discusses product-related risks and prioritization impacts
- **Steering Group**: Escalates major risks requiring executive decisions
- **Stakeholder Liaison**: Coordinates risk communication to key stakeholders
- **All roles**: Gathers risk inputs during regular reviews and retrospectives

---

## Change Manager

### Role Summary
Change Manager oversees the change request process, ensuring that scope changes are properly documented, assessed for impact, and routed through appropriate approval workflows.

### Responsibilities
- Receive and document change requests from stakeholders
- Assess impact of proposed changes on scope, timeline, and resources
- Coordinate change review and approval process
- Maintain change log and track implementation status
- Communicate approved changes to affected teams
- Ensure change documentation is updated in project artifacts

### Goals
- Maintain project scope integrity while accommodating necessary changes
- Ensure transparent and efficient change approval process
- Minimize disruption from uncontrolled scope changes
- Document change history for future reference and learning

### Typical Communication
- Change request intake and impact assessments
- Change review board meetings and approval decisions
- Change notification emails to project team
- Change log reports in status updates

### Key Interactions
- **Project Lead**: Discusses impact of changes on project timeline and resources
- **Technical Lead**: Assesses technical feasibility and implementation effort
- **Stakeholder Liaison**: Interfaces on change requests from business stakeholders
- **Product Owner**: Evaluates changes against product priorities and roadmap
- **Team Members**: Communicates approved changes and implementation requirements

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaison serves as the primary communication bridge between the project team and key business stakeholders, ensuring alignment, managing expectations, and gathering feedback.

### Responsibilities
- Identify and maintain stakeholder map with communication needs
- Facilitate regular stakeholder communication and updates
- Gather stakeholder input, concerns, and feedback
- Ensure stakeholder requirements are understood by the team
- Manage stakeholder expectations around timelines and deliverables
- Coordinate stakeholder participation in reviews and approvals

### Goals
- Maintain strong stakeholder engagement and satisfaction
- Ensure clear, consistent, and timely stakeholder communication
- Prevent misalignment between stakeholder expectations and delivery
- Build trust and transparency with business partners

### Typical Communication
- Weekly stakeholder status updates and newsletters
- Monthly stakeholder review meetings and demos
- Ad-hoc communications for urgent issues or decisions
- Feedback sessions and surveys

### Key Interactions
- **Business Owners**: Primary stakeholders providing requirements and feedback
- **Release Readiness Lead**: Coordinates on release communication and readiness
- **Team Members**: Gathers input and feedback to relay to stakeholders
- **Risk Owner**: Receives risk escalations requiring stakeholder awareness
- **Change Manager**: Receives and routes change requests from stakeholders
- **Project Manager**: Aligns on messaging and timing of stakeholder communications

---

## Release Readiness Lead

### Role Summary
Release Readiness Lead ensures all deployment prerequisites are met, manages the release checklist, and facilitates the go/no-go decision process for production releases.

### Responsibilities
- Maintain and execute release readiness checklist
- Validate that all acceptance criteria and quality gates are met
- Coordinate pre-release activities (smoke tests, backups, rollback plans)
- Facilitate go/no-go meetings with stakeholders
- Track and report release readiness status
- Coordinate release communication with support and operations teams

### Goals
- Ensure high-quality, low-risk production releases
- Minimize deployment-related incidents and rollbacks
- Maintain clear release readiness criteria and accountability
- Enable confident go-live decisions based on objective criteria

### Typical Communication
- Daily release readiness status during release window
- Go/no-go decision meetings with Technical Lead, QA, and Project Lead
- Release readiness reports to stakeholders
- Post-release verification and handoff communications

### Key Interactions
- **Technical Lead**: Validates technical readiness and deployment procedures
- **QA**: Confirms testing completion and quality standards
- **Project Lead**: Reports readiness status and escalates blockers
- **Operations/DevOps**: Coordinates deployment execution and monitoring
- **Stakeholder Liaison**: Ensures stakeholder awareness of release timing and impact

---

## Role Collaboration & Handoffs

This section clarifies how roles work together and where key handoffs occur:

### Planning Phase
- **Product Owner** defines requirements → **Project Manager** creates project plan
- **Risk Owner** conducts initial risk assessment → shares with **Project Manager** and **Technical Lead**
- **Stakeholder Liaison** gathers stakeholder input → provides to **Product Owner** and **Project Manager**

### Execution Phase
- **Developers** identify technical risks → report to **Risk Owner** and **Technical Lead**
- **Change Manager** receives change requests → coordinates with **Project Lead** and **Product Owner** for approval
- **Project Manager** tracks progress → provides updates to **Stakeholder Liaison** for stakeholder communication

### Pre-Release Phase
- **Release Readiness Lead** validates readiness criteria → coordinates with **QA**, **Technical Lead**, and **DevOps**
- **Risk Owner** assesses release risks → reports to **Release Readiness Lead** and **Project Manager**
- **Stakeholder Liaison** prepares stakeholders for release → coordinates timing with **Release Readiness Lead**

### Release & Deployment
- **Release Readiness Lead** facilitates go/no-go decision → includes **Technical Lead**, **QA**, **Project Manager**
- **Technical Lead** executes deployment → **Release Readiness Lead** monitors and validates
- **Stakeholder Liaison** announces release → coordinates with **Release Readiness Lead** on status

### Post-Release & Continuous Improvement
- **Risk Owner** reviews risk mitigation effectiveness → shares learnings in retrospective
- **Change Manager** reviews change impact → contributes to retrospective insights
- **All roles** participate in retrospectives → **Project Manager** captures action items

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded role set helps clarify responsibilities, reduce ambiguity, and improve collaboration across the project lifecycle.

