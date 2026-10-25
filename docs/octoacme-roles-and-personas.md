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

## Engineering Manager

### Role Summary
Engineering Managers support engineering teams through people leadership, capacity planning, and delivery enablement while maintaining a healthy, sustainable team.

### Responsibilities
- Plan engineering capacity and identify staffing or skills gaps
- Coach Developers and support team growth
- Remove organizational blockers and escalate delivery concerns
- Partner on technical staffing and execution-quality decisions

### Goals
- Build a capable, sustainable engineering team
- Give the team the support and capacity needed to meet commitments
- Surface delivery risks early and resolve them effectively

### Typical Communication
- Team check-ins and development conversations
- Capacity and staffing discussions
- Delivery-risk and escalation updates

### Interactions
- **Developers:** Coach and unblock them; coordinate capacity and execution concerns without taking over implementation ownership.
- **Product Managers:** Discuss feasibility and capacity implications of priorities and scope.
- **Project Managers:** Align on delivery forecasts, resource constraints, risks, and schedule trade-offs.
- **QA/Testing:** Coordinate engineering capacity for quality work and address recurring quality or resourcing concerns.

---

## Technical Lead / Staff Engineer

### Role Summary
Technical Leads and Staff Engineers guide technical direction and help teams make sound architecture and implementation decisions across project boundaries.

### Responsibilities
- Propose and communicate architecture and technical design decisions
- Identify technical risks, dependencies, and maintainability concerns
- Guide implementation through design discussions and code reviews
- Promote testability, reliability, and consistent engineering practices

### Goals
- Deliver a coherent, maintainable technical solution
- Reduce technical risk and avoid costly rework
- Help Developers make well-informed implementation decisions

### Typical Communication
- Design documents and architecture reviews
- Technical discussions and code review feedback
- Risk and dependency updates during planning

### Interactions
- **Developers:** Provide design guidance and review; Developers own their implementation and raise emerging technical risks.
- **Product Managers:** Explain technical trade-offs and scope implications so product decisions account for feasibility.
- **Project Managers:** Surface dependencies and technical risks that affect estimates, sequencing, or delivery commitments.
- **QA/Testing:** Collaborate on testability, coverage strategy, and investigation of complex defects.

---

## UX/UI Designer

### Role Summary
UX/UI Designers shape user flows and interfaces so that solutions are usable, accessible, and consistent with user needs and product intent.

### Responsibilities
- Research user needs and design end-to-end user flows
- Create interaction designs, prototypes, and interface specifications
- Consider accessibility and usability in design decisions
- Review implementation and incorporate usability feedback

### Goals
- Make product experiences intuitive, accessible, and consistent
- Validate design assumptions with users and evidence
- Reduce ambiguity about expected user-facing behavior

### Typical Communication
- User research findings and design reviews
- Prototypes, specifications, and design-system references
- Usability feedback and implementation reviews

### Interactions
- **Developers:** Clarify design intent and collaborate on feasible implementation; Developers flag technical constraints or behavior differences early.
- **Product Managers:** Translate product goals and requirements into user flows, and validate that designs address user needs.
- **Project Managers:** Identify design dependencies and review milestones that affect the delivery plan.
- **QA/Testing:** Share interaction and accessibility expectations so tests cover key user journeys and edge cases.

---

## Security Engineer / Security Champion

### Role Summary
Security Engineers and Security Champions help teams identify and reduce security risks throughout design, implementation, and release.

### Responsibilities
- Advise on security requirements and threat-modeling activities
- Review security-sensitive designs and implementation risks
- Recommend mitigations and support security testing
- Help assess security readiness and incident preparedness

### Goals
- Protect users, systems, and data
- Identify security concerns early enough to address them safely
- Make security practices a routine part of delivery

### Typical Communication
- Threat models and security review findings
- Practical guidance during design and code reviews
- Risk, mitigation, and incident-readiness updates

### Interactions
- **Developers:** Advise on secure implementation and remediation; Developers implement mitigations and report unresolved risks.
- **Product Managers:** Explain security requirements and risks that affect scope, user impact, or release decisions.
- **Project Managers:** Communicate security dependencies and unresolved risks for planning, escalation, and status reporting.
- **QA/Testing:** Coordinate security-focused test coverage and ensure findings are tracked through resolution.

---

## DevOps / SRE

### Role Summary
DevOps and Site Reliability Engineering (SRE) practitioners enable safe, reliable delivery and operation through deployment automation, observability, and operational readiness.

### Responsibilities
- Maintain or advise on CI/CD pipelines and deployment practices
- Establish observability, reliability, and operational-readiness expectations
- Plan safe releases, rollback approaches, and recovery procedures
- Monitor service health and coordinate operational incident response

### Goals
- Make releases repeatable, observable, and safe
- Improve service reliability and recovery time
- Ensure operational risks are understood before launch

### Typical Communication
- Deployment plans and release-readiness reviews
- Dashboards, alerts, and service-health reports
- Incident updates and operational runbooks

### Interactions
- **Developers:** Coordinate deployment, infrastructure, and observability needs; Developers help instrument and troubleshoot their services.
- **Product Managers:** Explain reliability and operational trade-offs that affect product scope or launch timing.
- **Project Managers:** Align release windows, dependencies, readiness checkpoints, and operational risks.
- **QA/Testing:** Coordinate environment readiness and release validation, including rollback or recovery checks where appropriate.

---

## Business Analyst / Operations Representative

### Role Summary
Business Analysts and Operations Representatives connect delivery work to business processes, operational workflows, and stakeholder readiness.

### Responsibilities
- Clarify business rules, process impacts, and operational requirements
- Validate proposed workflows with affected stakeholders
- Identify adoption, training, and support needs
- Contribute to acceptance planning and readiness checks

### Goals
- Ensure delivered changes address the intended business need
- Prepare affected teams to adopt and support process changes
- Reduce gaps between documented requirements and real workflows

### Typical Communication
- Process maps and requirements discussions
- Stakeholder walkthroughs and workflow validation
- Operational-readiness and acceptance updates

### Interactions
- **Developers:** Clarify business rules and answer workflow questions; Developers identify constraints that may change the proposed process.
- **Product Managers:** Refine requirements and validate that the solution addresses the business and user need.
- **Project Managers:** Coordinate stakeholder reviews, acceptance activities, and adoption dependencies.
- **QA/Testing:** Provide business scenarios and expected outcomes for acceptance and workflow testing.

---

## Cross-role collaboration and handoffs

- Product Managers own product outcomes, priorities, and scope decisions; Project Managers coordinate the plan, dependencies, risks, and stakeholder updates.
- Technical Leads guide technical direction with Developers, who own implementation and communicate progress or blockers. Engineering Managers support team capacity and remove organizational obstacles.
- UX/UI Designers and Business Analysts clarify user and business workflows early; Developers and QA/Testing use those decisions and acceptance criteria to implement and verify behavior.
- Security Engineers/Champions advise on security risks and mitigations; DevOps/SRE advise on deployment and operational readiness. Record unresolved risks, owners, and decisions so release stakeholders can act on them.
- At each handoff, share the relevant decision or artifact, the next owner, acceptance or readiness criteria, dependencies, and open risks. Confirm ownership when plans or requirements change.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
