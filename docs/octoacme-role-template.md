# Role Template

This template provides a standardized format for documenting roles and personas in OctoAcme project management documentation. Use this structure to ensure consistency and completeness when adding new roles.

## Template Structure

Each role should include the following sections:

### Role Summary
A 1-2 sentence overview that captures the essence of the role and its primary purpose within the organization.

### Responsibilities
A list of 4-6 key responsibilities that define what this role does day-to-day. Be specific and actionable.

### Goals
3-4 high-level objectives that this role works toward. These should align with organizational success metrics.

### Typical Communication
Examples of how this role communicates, including meeting types, documentation they produce, and collaboration patterns.

### Typical Communication / Interactions
A brief paragraph (4-6 sentences) describing how this role coordinates with other key roles including Project Managers (PM), Product Managers (PdM), Developers, QA, and Support. Highlight key handoffs and collaboration points.

---

## YAML Front-matter Example

For tools or systems that support YAML front-matter, you can include structured metadata at the top of role documents:

```yaml
---
role_name: "Business Analyst"
role_category: "Requirements & Analysis"
primary_focus: "Requirements gathering and documentation"
interacts_with:
  - "Product Managers"
  - "Project Managers"
  - "Developers"
  - "QA Teams"
key_artifacts:
  - "User Stories"
  - "Requirements Documents"
  - "Process Flows"
  - "Acceptance Criteria"
seniority_levels:
  - "Junior BA"
  - "BA"
  - "Senior BA"
  - "Principal BA"
---
```

---

## Complete Example: Business Analyst

```yaml
---
role_name: "Business Analyst"
role_category: "Requirements & Analysis"
primary_focus: "Requirements gathering and documentation"
interacts_with:
  - "Product Managers"
  - "Project Managers"
  - "Developers"
  - "QA Teams"
key_artifacts:
  - "User Stories"
  - "Requirements Documents"
  - "Process Flows"
  - "Acceptance Criteria"
---
```

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

## How to Use This Template

1. **Start with the Role Summary**: Clearly articulate the role's purpose in 1-2 sentences
2. **List Responsibilities**: Focus on 4-6 key duties that define the role
3. **Define Goals**: Identify 3-4 measurable objectives
4. **Document Communication Patterns**: Show typical meetings, docs, and collaboration styles
5. **Describe Interactions**: Explain how this role works with other key personas
6. **Add YAML metadata** (optional): For systems that parse front-matter, include structured data

**Tips:**
- Keep language consistent with existing OctoAcme documentation
- Use action verbs for responsibilities (e.g., "Create", "Coordinate", "Manage")
- Be specific about collaboration patterns and handoffs
- Align role goals with organizational principles from the Project Management Overview
- Review other personas in `octoacme-roles-and-personas.md` for style and tone consistency
