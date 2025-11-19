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

## Business Analyst

### Role Summary
Business Analysts bridge business requirements and technical implementation. They work with stakeholders to gather, document, and refine requirements, ensuring that solutions align with business goals and user needs.

### Responsibilities
- Gather and document business requirements from stakeholders
- Translate business needs into clear functional specifications
- Create process flows, user stories, and acceptance criteria
- Collaborate with Product Managers and Developers to clarify requirements
- Validate solutions against business objectives and user needs
- Support change management and user adoption activities

### Goals
- Ensure requirements are clear, complete, and testable
- Reduce rework through thorough upfront analysis
- Maximize alignment between business needs and technical solutions

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story creation and backlog refinement sessions
- Collaboration with PdM on feature prioritization
- Regular check-ins with development team on requirement clarifications

### Typical Communication / Interactions
Business Analysts coordinate closely with Product Managers to understand the product vision and translate it into detailed requirements. They work with Project Managers during planning phases to ensure requirements are well-defined before handoff to developers. Throughout execution, they support Developers by clarifying requirements and validating implementation. They also collaborate with QA teams to ensure test cases adequately cover business scenarios and with Support teams to document known issues and workarounds.

---

## Release Manager

### Role Summary
Release Managers orchestrate the end-to-end release process, coordinating across teams to ensure smooth, reliable deployments. They manage release schedules, coordinate testing and validation, and ensure proper communication of release changes.

### Responsibilities
- Plan and coordinate release schedules across multiple teams
- Manage release readiness activities (code freeze, testing, sign-offs)
- Coordinate deployment activities and rollback procedures
- Track and communicate release status to stakeholders
- Maintain release documentation and changelogs
- Conduct post-release validation and coordinate hotfix deployments

### Goals
- Deliver high-quality releases on schedule
- Minimize deployment risks and production incidents
- Ensure clear communication and coordination across all stakeholders

### Typical Communication
- Release planning meetings with PM and engineering leads
- Daily release status updates during release windows
- Release notes and deployment communications
- Post-deployment retrospectives

### Typical Communication / Interactions
Release Managers work closely with Project Managers to align release schedules with project milestones and dependencies. They coordinate with Developers to manage code freezes, merge windows, and deployment readiness. During the release process, they collaborate intensively with QA teams to validate release candidates and coordinate with Support teams to prepare for customer impact. After releases, they partner with Product Managers to validate that deployed features meet expectations and with Support teams to monitor customer feedback and address any issues.

---

## Support / Customer Success Lead

### Role Summary
Support and Customer Success Leads ensure customers successfully adopt and derive value from the product. They manage escalations, gather customer feedback, and advocate for customer needs within the product development process.

### Responsibilities
- Manage critical customer escalations and coordinate resolutions
- Gather and synthesize customer feedback and feature requests
- Coordinate with Product and Engineering on customer-reported issues
- Develop and maintain customer-facing documentation and knowledge base
- Train support team members on new features and capabilities
- Track and report on customer satisfaction and support metrics

### Goals
- Maximize customer satisfaction and product adoption
- Minimize time-to-resolution for customer issues
- Provide actionable customer insights to inform product decisions

### Typical Communication
- Daily escalation reviews with support team
- Weekly sync with Product and Engineering on top issues
- Customer-facing communications for incident updates
- Monthly reporting on support trends and customer feedback

### Typical Communication / Interactions
Support Leads coordinate with Product Managers to communicate customer needs and prioritize fixes based on customer impact. They work with Developers to troubleshoot complex issues and verify bug fixes before customer communication. During releases, they partner with Release Managers to understand changes, prepare support documentation, and brief the support team. They provide QA teams with real-world usage patterns and edge cases discovered through customer interactions. After major releases, they monitor customer feedback closely and escalate any critical issues to the appropriate teams.

---

## UX Designer

### Role Summary
UX Designers create intuitive, user-centered experiences that meet both user needs and business goals. They conduct user research, design interfaces, and validate designs through testing and iteration.

### Responsibilities
- Conduct user research to understand user needs and pain points
- Create wireframes, prototypes, and high-fidelity designs
- Design information architecture and user flows
- Collaborate with Product Managers on feature design and prioritization
- Work with Developers to ensure design feasibility and implementation quality
- Conduct usability testing and iterate based on feedback

### Goals
- Create intuitive, accessible, and delightful user experiences
- Reduce user friction and support adoption
- Ensure design consistency across the product

### Typical Communication
- Design review sessions with Product and Engineering teams
- User research presentations and insights sharing
- Collaborative design workshops and brainstorming sessions
- Regular design critiques and feedback sessions

### Typical Communication / Interactions
UX Designers partner closely with Product Managers to understand user problems and business objectives, translating them into design solutions. They work with Business Analysts to ensure requirements capture user experience needs and with Developers during implementation to maintain design quality and address technical constraints. They collaborate with QA teams to define usability testing criteria and with Support teams to understand user pain points from real-world usage. Throughout the project, they coordinate with Project Managers to align design milestones with overall project timelines.

---

## Data Analyst

### Role Summary
Data Analysts transform raw data into actionable insights that drive product and business decisions. They design metrics, create dashboards, and conduct analyses to measure success and identify opportunities.

### Responsibilities
- Define and track key product and business metrics
- Build dashboards and reporting infrastructure
- Conduct ad-hoc analyses to answer specific business questions
- Collaborate with Product Managers to define success metrics for features
- Identify trends, patterns, and opportunities through data exploration
- Ensure data quality and integrity across systems

### Goals
- Enable data-driven decision making across the organization
- Provide timely, accurate insights that drive action
- Build scalable analytics infrastructure and self-service capabilities

### Typical Communication
- Weekly metrics reviews with Product and leadership teams
- Ad-hoc analysis presentations and recommendations
- Documentation of metric definitions and data models
- Collaboration sessions on experiment design and measurement

### Typical Communication / Interactions
Data Analysts work with Product Managers to define success metrics and measure feature impact post-launch. They collaborate with Business Analysts to ensure requirements include necessary instrumentation and tracking. During planning, they partner with Project Managers to scope analytics work and integrate it into project timelines. They support Developers by providing data specifications and validating instrumentation implementation. After releases, they work with Support teams to analyze user behavior patterns and with UX Designers to provide quantitative validation of design hypotheses.

---

## Security Champion

### Role Summary
Security Champions promote security best practices within development teams and serve as a bridge between security specialists and engineers. They help identify and mitigate security risks throughout the development lifecycle.

### Responsibilities
- Conduct security reviews of code, designs, and infrastructure
- Advocate for security best practices within development teams
- Coordinate with security team on threat modeling and risk assessments
- Respond to security incidents and coordinate remediation
- Maintain security documentation and guidelines
- Provide security training and awareness for team members

### Goals
- Build security into the development process from the start
- Reduce security vulnerabilities and incident response time
- Foster a security-aware culture within engineering teams

### Typical Communication
- Security review sessions during design and code review
- Regular syncs with central security team
- Incident response coordination during security events
- Training sessions and security awareness communications

### Typical Communication / Interactions
Security Champions work with Developers to integrate security practices into daily workflows, reviewing code and designs for potential vulnerabilities. They collaborate with Project Managers to ensure security requirements are included in project planning and timelines. During execution, they partner with QA teams to validate security test coverage and with Release Managers to assess deployment risks. They coordinate with Product Managers to balance security requirements with feature priorities and work with Support teams to handle security-related customer inquiries and incidents.

---

## Interactions Matrix

This section summarizes key handoffs and coordination points between roles:

**Planning Phase:**
- **Requirements Handoff** — Product Manager → Business Analyst → Project Manager
  - PdM defines product vision and priorities
  - BA gathers detailed requirements and creates user stories
  - PM incorporates into project plan with timelines and resources

**Planning → Execution Handoff:**
- **Project Kickoff** — Project Manager → Development Team
  - PM confirms scope, timeline, and success criteria
  - BA ensures requirements are clear and acceptance criteria defined
  - Devs confirm understanding and technical feasibility
  - QA confirms test strategy and coverage plan
  - UX Designer confirms design specifications are complete

**During Execution:**
- **Design → Development** — UX Designer → Developers → QA
  - Designer provides specifications and assets
  - Developers implement per design specs
  - QA validates implementation against designs and usability criteria

- **Development → QA** — Developers → QA Team
  - Devs signal feature completion and provide test builds
  - QA executes test plans and reports issues
  - Devs address defects in collaboration with QA

- **Security Reviews** — Security Champion → Developers → PM
  - Security Champion reviews designs and code for vulnerabilities
  - Developers address findings with Security Champion guidance
  - PM tracks security issues as part of project risk management

**Pre-Release:**
- **Release Readiness** — Release Manager → All Teams
  - Release Manager coordinates final testing and validations
  - PM confirms scope completion and sign-offs
  - QA confirms test completion and critical bugs resolved
  - Support Lead confirms documentation and team readiness

**Release → Support Handoff:**
- **Release Coordination** — Release Manager → Developers → Support/QA
  - Release Manager executes deployment plan
  - Developers provide technical support during deployment
  - Support team monitors customer impact and escalates issues
  - QA validates production deployment

**Post-Release:**
- **Post-Release Monitoring** — Support Lead → Product Manager → Developers
  - Support Lead tracks customer feedback and critical issues
  - PdM analyzes feature adoption and success metrics (with Data Analyst)
  - Developers address critical bugs and performance issues
  - Data Analyst provides usage metrics and insights

**Continuous:**
- **Data & Insights** — Data Analyst → Product Manager → All Teams
  - Data Analyst monitors metrics and surfaces insights
  - PdM uses data to inform prioritization and strategy
  - Findings shared with relevant teams to drive improvements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

