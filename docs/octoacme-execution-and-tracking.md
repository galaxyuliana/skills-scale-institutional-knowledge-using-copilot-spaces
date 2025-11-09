# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist

### Cross-Functional Collaboration
- [ ] Daily standups include all key roles (Dev, QA, Scrum Master)
- [ ] Business Analyst available for requirement clarifications
- [ ] Technical Lead reviews architecture and design decisions
- [ ] QA Specialist validates acceptance criteria before development starts
- [ ] Regular touchpoints with Product Manager on priorities

### Stakeholder Engagement
- [ ] Weekly status updates shared with stakeholders
- [ ] Stakeholder demo/review sessions scheduled at milestone completion
- [ ] Escalations communicated promptly with impact and mitigation plans
- [ ] Feedback loops established for stakeholder input

### Accountability Touchpoints
- [ ] Code review assignments clear with defined turnaround times
- [ ] RACI matrix referenced for decision-making and approvals
- [ ] Blocker owners identified and tracked in daily standups
- [ ] Quality gates defined with QA sign-off requirements
- [ ] Risk owners assigned and accountability tracked in risk register

### Process & Tooling
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Project board reflects current state and priorities
