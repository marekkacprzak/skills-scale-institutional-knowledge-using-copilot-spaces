# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Quick Reference: Roles & Responsibilities Summary

| Role | Primary Responsibilities | Key Collaborations |
|------|-------------------------|-------------------|
| **Developer** | Implement features, write tests, code reviews | Product Manager, UX Designer, DevOps Engineer, Business Analyst, Technical Writer |
| **Product Manager** | Define product vision, prioritize backlog, measure outcomes | Project Manager, UX Designer, Business Analyst, Developers, Scrum Master |
| **Project Manager** | Coordinate delivery, manage schedules/risks, facilitate meetings | Product Manager, Developers, Scrum Master, Business Analyst, DevOps Engineer |
| **UX Designer** | Design user interfaces, conduct user research, maintain design systems | Product Manager, Developers, Business Analyst, Technical Writer |
| **Scrum Master** | Facilitate agile ceremonies, remove blockers, coach teams | Project Manager, Product Manager, Developers, DevOps Engineer |
| **Business Analyst** | Elicit and document requirements, create process flows, validate solutions | Product Manager, Developers, UX Designer, Project Manager |
| **Technical Writer** | Create documentation, API guides, user manuals, release notes | Developers, Product Manager, UX Designer, Project Manager, Business Analyst |
| **DevOps Engineer** | Build CI/CD pipelines, manage infrastructure, monitor systems | Developers, Project Manager, Scrum Master, Technical Writer |

---

## Role Interaction Matrix

Understanding how roles collaborate is essential for smooth handoffs and reducing single-person dependencies:

- **Product to Engineering**: Product Manager defines "what" and "why" → Business Analyst documents detailed requirements → UX Designer creates user experience → Developers implement → DevOps Engineer deploys
- **Design to Development**: UX Designer creates mockups → Developers review feasibility → Technical Writer documents UI → QA validates against acceptance criteria
- **Planning to Execution**: Product Manager prioritizes → Project Manager schedules → Scrum Master facilitates sprint planning → Team executes → All roles participate in retrospectives
- **Release Coordination**: Project Manager coordinates → DevOps Engineer prepares infrastructure → Developers merge code → Technical Writer publishes release notes → Product Manager validates metrics

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

### Key Collaborations
- Partners with **Product Managers** to understand requirements and acceptance criteria
- Works with **UX Designers** to implement designs and ensure UI/UX fidelity
- Collaborates with **Business Analysts** to clarify requirements and edge cases
- Engages **DevOps Engineers** on CI/CD pipelines, infrastructure needs, and deployment
- Supports **Technical Writers** with technical details for documentation
- Participates in ceremonies facilitated by **Scrum Master** (standups, planning, retros)
- Coordinates with **Project Managers** on estimates, timelines, and risk identification

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

### Key Collaborations
- Partners with **Project Managers** on scope, timelines, and prioritization trade-offs
- Works closely with **UX Designers** on user research, design validation, and usability
- Collaborates with **Business Analysts** to refine requirements and business cases
- Engages **Developers** to understand technical constraints and validate feasibility
- Coordinates with **Scrum Master** on backlog refinement and sprint planning
- Works with **Technical Writers** on user-facing documentation and release communications

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

### Key Collaborations
- Works with **Product Managers** on prioritization, scope changes, and trade-offs
- Coordinates with **Developers** on estimates, dependencies, and delivery timelines
- Partners with **Scrum Master** on agile ceremonies and team velocity
- Engages **Business Analysts** for requirements clarity and stakeholder alignment
- Collaborates with **DevOps Engineers** on deployment schedules and infrastructure readiness
- Works with **Technical Writers** to ensure documentation is delivered alongside features

---

## UX Designers

### Role Summary
UX Designers create intuitive, user-centered experiences by conducting research, designing interfaces, and validating designs with users. They ensure products are accessible, usable, and aligned with user needs.

### Responsibilities
- Conduct user research and create user personas
- Design wireframes, prototypes, and high-fidelity mockups
- Collaborate with Product Managers to define user stories and acceptance criteria
- Validate designs through usability testing and user feedback
- Maintain design systems and component libraries
- Ensure accessibility standards (WCAG) are met

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction scores
- Build reusable design patterns and components

### Typical Communication
- Design critiques and stakeholder walkthroughs
- Usability testing reports and insights
- Collaboration in design tools (Figma, Sketch) with annotations

### Key Collaborations
- Partners with **Product Managers** on user needs, feature prioritization, and success metrics
- Works closely with **Developers** to ensure design feasibility and implementation fidelity
- Collaborates with **Business Analysts** on user flows and requirements validation
- Engages **Technical Writers** to align UI copy and help documentation
- Coordinates with **QA** on acceptance criteria for UI/UX features

---

## Scrum Masters

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and coach teams in Scrum practices. They protect the team from distractions and foster a culture of continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, retrospectives, and sprint reviews
- Remove impediments that block team progress
- Coach team members on agile principles and self-organization
- Track and visualize team velocity, burndown, and capacity
- Ensure Definition of Done is clear and followed
- Shield the team from scope creep and external interruptions

### Goals
- Enable predictable sprint delivery
- Improve team velocity and collaboration
- Foster psychological safety and continuous learning

### Typical Communication
- Daily facilitation of standups
- Sprint metrics and velocity reports
- Retrospective action items and follow-ups

### Key Collaborations
- Works with **Project Managers** on delivery timelines and risk management
- Partners with **Product Managers** to refine backlog and prioritize user stories
- Supports **Developers** in identifying and removing blockers
- Coordinates with **DevOps Engineers** on deployment readiness and CI/CD improvements
- Engages all team members to improve team health and delivery processes

---

## Business Analysts

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They elicit, analyze, and document requirements, ensuring solutions align with business goals and user needs.

### Responsibilities
- Elicit requirements from stakeholders through interviews, workshops, and observation
- Document functional and non-functional requirements
- Create process flows, data models, and use cases
- Validate requirements with stakeholders and development teams
- Support acceptance testing by defining test scenarios
- Analyze impact of changes on existing systems and processes

### Goals
- Ensure clear, testable, and complete requirements
- Reduce rework from misunderstood requirements
- Align solutions with business value and strategic goals

### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and data models
- Stakeholder workshops and validation sessions

### Key Collaborations
- Partners with **Product Managers** to refine product vision and prioritize features
- Works closely with **Developers** to clarify requirements and validate technical feasibility
- Collaborates with **UX Designers** on user flows and interface requirements
- Engages **Project Managers** on scope, dependencies, and timelines
- Supports **QA** in defining acceptance criteria and test scenarios

---

## Technical Writers

### Role Summary
Technical Writers create and maintain user-facing documentation, developer guides, API references, and internal process documentation. They make complex technical information accessible and discoverable.

### Responsibilities
- Write and maintain user guides, help articles, and FAQs
- Document APIs, SDKs, and developer onboarding guides
- Collaborate with engineers to understand features and technical details
- Maintain documentation versioning aligned with product releases
- Ensure documentation is clear, accurate, and accessible
- Gather feedback and analytics to improve documentation effectiveness

### Goals
- Reduce support tickets through self-service documentation
- Enable faster user and developer onboarding
- Maintain up-to-date and accurate documentation

### Typical Communication
- Documentation reviews with engineers and product managers
- Style guides and documentation standards
- Release notes and changelog updates

### Key Collaborations
- Works with **Developers** to document features, APIs, and technical details
- Partners with **Product Managers** on user-facing documentation and release notes
- Collaborates with **UX Designers** to align UI copy with help documentation
- Engages **Project Managers** to ensure documentation is part of Definition of Done
- Coordinates with **Business Analysts** on process documentation and user guides

---

## DevOps Engineers

### Role Summary
DevOps Engineers build and maintain CI/CD pipelines, infrastructure, and monitoring systems. They enable reliable, automated deployments and ensure system reliability, security, and scalability.

### Responsibilities
- Design and maintain CI/CD pipelines for automated builds, tests, and deployments
- Manage infrastructure as code (IaC) using tools like Terraform, CloudFormation
- Monitor system health, performance, and security
- Implement and maintain observability tools (logging, metrics, alerts)
- Automate operational tasks and improve deployment reliability
- Respond to incidents and perform root cause analysis

### Goals
- Achieve zero-downtime deployments
- Reduce lead time from commit to production
- Maintain high system availability and reliability (SLOs)

### Typical Communication
- Incident reports and post-mortems
- Infrastructure change logs and deployment notifications
- Runbooks and operational documentation

### Key Collaborations
- Works closely with **Developers** on build, test, and deployment automation
- Partners with **Project Managers** on release schedules and deployment readiness
- Collaborates with **Scrum Masters** on sprint capacity for infrastructure work
- Engages **Technical Writers** to document deployment procedures and runbooks
- Supports all roles by ensuring reliable infrastructure and tooling

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The collaboration patterns help identify handoff points and reduce single-person dependency risks.

## Onboarding Checklist for Team Members

When joining an OctoAcme project, use this checklist to understand your role and key touchpoints:

- [ ] Review your role's responsibilities, goals, and typical communication patterns
- [ ] Identify your key collaborators from the Role Interaction Matrix
- [ ] Schedule introductory meetings with primary collaboration partners
- [ ] Understand handoff points where your work depends on or feeds into other roles
- [ ] Review existing project artifacts relevant to your role (backlog, design files, docs, infrastructure)
- [ ] Clarify communication channels and meeting cadences (standups, planning, reviews)
- [ ] Identify who to escalate blockers to based on the issue type
- [ ] Review the Definition of Done and understand your role's contribution to it

## Reducing Single-Person Dependencies

To minimize risks from knowledge silos and single points of failure:

1. **Cross-training**: Encourage knowledge sharing between Developers, rotation in DevOps tasks, and paired design reviews with UX Designers
2. **Documentation**: Technical Writers ensure runbooks, API docs, and process guides are kept current
3. **Code Reviews**: Multiple Developers review each PR; Business Analysts validate requirements with multiple stakeholders
4. **Shared Ownership**: Scrum Masters facilitate team-wide ownership; Project Managers maintain transparent risk registers
5. **Regular Handoffs**: Use the Role Interaction Matrix to ensure clear handoff ceremonies (design → dev, dev → QA, QA → release)
6. **Backup Coverage**: Identify backup roles for critical responsibilities in the Project Charter

## Living Documentation

This personas document is living documentation. Teams should:
- Update role definitions when processes evolve
- Add new roles as team structure changes
- Refine collaboration patterns based on retrospective feedback
- Submit improvements back to the central OctoAcme docs repository

---

**Last Updated**: 2025-12-14  
**Maintained By**: OctoAcme Project Management Team
