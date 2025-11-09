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

## Stakeholders

### Role Summary
Stakeholders are key decision-makers, sponsors, or end users who provide business requirements, feedback, and approvals at critical project stages. They may be internal executives, business unit leaders, or external clients.

### Responsibilities
- Define and communicate business requirements and constraints
- Provide timely feedback and approvals at decision gates
- Allocate budget and resources for the project
- Review deliverables and validate business value
- Champion the project within their organization

### Goals
- Ensure project outcomes align with business objectives
- Maximize return on investment
- Manage organizational change and adoption

### Typical Communication
- Kickoff meetings and milestone reviews
- Steering committee updates and decision gates
- Email approvals and escalation channels

### Interaction Points
- **Product Managers**: Collaborate on defining success metrics and prioritization
- **Project Managers**: Receive status updates and provide strategic direction
- **Business Analysts**: Work together to clarify and refine requirements
- **Technical Lead**: Discuss feasibility and architectural constraints

---

## Business Analysts

### Role Summary
Business Analysts translate business requirements into actionable technical tasks and documentation. They bridge the gap between stakeholders and the development team, ensuring clarity and alignment.

### Responsibilities
- Elicit and document business requirements
- Create functional specifications and user stories
- Analyze gaps between current and desired states
- Validate that solutions meet business needs
- Facilitate requirements workshops and walkthroughs

### Goals
- Ensure requirements are clear, complete, and testable
- Reduce rework caused by ambiguous specifications
- Enable smooth handoff between business and technical teams

### Typical Communication
- Requirements documents and user story mappings
- Process flow diagrams and decision matrices
- Requirements review sessions with stakeholders and developers

### Interaction Points
- **Stakeholders**: Gather and validate requirements
- **Product Managers**: Align on feature priorities and acceptance criteria
- **Developers**: Clarify implementation details and edge cases
- **QA Specialists**: Define testable acceptance criteria

---

## Scrum Masters

### Role Summary
Scrum Masters facilitate agile practices, remove impediments, and enable the team to work efficiently. They coach the team on agile principles and ensure ceremonies are effective.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments
- Coach the team on agile practices and continuous improvement
- Shield the team from external distractions
- Track and communicate sprint progress

### Goals
- Maximize team velocity and predictability
- Foster a culture of continuous improvement
- Ensure adherence to agile principles and practices

### Typical Communication
- Daily standup facilitation
- Sprint burndown and velocity reports
- Impediment logs and action items
- Retrospective summaries and improvement plans

### Interaction Points
- **Developers**: Remove blockers and facilitate daily collaboration
- **Product Managers**: Coordinate backlog refinement and sprint planning
- **Project Managers**: Align on delivery timelines and risk management
- **QA Specialists**: Ensure quality processes are integrated into sprints

---

## QA Specialists

### Role Summary
QA Specialists define test strategy, ensure quality standards are met throughout the development lifecycle, and collaborate closely with developers and product managers on acceptance criteria.

### Responsibilities
- Define test strategy and test plans
- Create and execute test cases (manual and automated)
- Identify, document, and track defects
- Validate that deliverables meet acceptance criteria
- Advocate for quality practices and standards

### Goals
- Prevent defects from reaching production
- Maintain high product quality and reliability
- Reduce time spent on defect triage and rework

### Typical Communication
- Test plans and test case documentation
- Bug reports and quality metrics
- QA sign-off and release readiness reports
- Feedback during code reviews and demos

### Interaction Points
- **Developers**: Collaborate on testability and defect resolution
- **Product Managers**: Validate acceptance criteria and feature completeness
- **Business Analysts**: Ensure test coverage aligns with requirements
- **Scrum Masters**: Report on quality metrics and testing progress

---

## Technical Leads

### Role Summary
Technical Leads guide implementation decisions, mentor developers, review design and code, and serve as the technical voice for the team. They interface between the team and architectural stakeholders.

### Responsibilities
- Define technical approach and architecture decisions
- Review and approve design documents and critical code changes
- Mentor developers on best practices and technical skills
- Identify and mitigate technical risks
- Represent the team in architectural discussions

### Goals
- Ensure technical solutions are scalable, maintainable, and secure
- Build team technical capabilities through mentorship
- Balance technical excellence with delivery timelines

### Typical Communication
- Architecture decision records (ADRs)
- Technical design reviews and code review comments
- Technical risk assessments
- Knowledge sharing sessions and tech talks

### Interaction Points
- **Developers**: Mentor and review their code and designs
- **Product Managers**: Advise on technical feasibility and trade-offs
- **Project Managers**: Communicate technical risks and dependencies
- **Stakeholders**: Explain technical constraints and opportunities

---

## Role Interaction Matrix

| From / To | Developers | Product Managers | Project Managers | Stakeholders | Business Analysts | Scrum Masters | QA Specialists | Technical Leads |
|-----------|-----------|------------------|------------------|--------------|-------------------|---------------|----------------|-----------------|
| **Developers** | Code reviews | Feature clarification | Status updates | Demo features | Requirement questions | Daily standups | Bug fixes, test support | Design reviews |
| **Product Managers** | Requirements, priorities | Strategy alignment | Timeline input | Value validation | Scope definition | Backlog refinement | Acceptance criteria | Feasibility checks |
| **Project Managers** | Resource planning | Milestone tracking | Status reporting | Steering updates | Requirement sign-off | Sprint coordination | Quality gates | Risk discussions |
| **Stakeholders** | Feature feedback | Strategic priorities | Governance oversight | Decision alignment | Requirement input | — | Acceptance validation | Architecture input |
| **Business Analysts** | Technical specs | Requirement validation | Scope documentation | Requirement gathering | Peer review | Story refinement | Test scenario input | Feasibility analysis |
| **Scrum Masters** | Coaching, blocker removal | Backlog health | Velocity reporting | — | Workshop facilitation | Best practice sharing | Sprint quality tracking | Process improvement |
| **QA Specialists** | Test feedback | Quality metrics | Defect reporting | Quality sign-off | Test case review | Sprint testing status | Quality standards | Test strategy review |
| **Technical Leads** | Mentorship | Technical guidance | Architecture updates | Technical briefings | Feasibility input | Technical debt discussions | Quality automation | Architecture decisions |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the Role Interaction Matrix to understand collaboration patterns and accountability touchpoints.

