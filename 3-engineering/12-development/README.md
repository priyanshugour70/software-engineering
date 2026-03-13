## Development

### Overview

The **Development** phase is where engineers **design, implement, and refine code** that meets the defined requirements and architecture. In enterprises, development must balance **feature delivery, maintainability, performance, and regulatory constraints**.

Development is iterative and closely integrated with **code review, CI, and testing**.


### Objectives

- **Implement features and fixes** according to requirements and design.
- **Write automated tests** to validate behavior.
- **Refactor and improve existing code** while maintaining stability.
- **Adhere to coding standards and security practices**.
- **Collaborate closely** with product, QA, and other engineers.


### Activities

- **Task Breakdown and Planning**
  - Refine user stories into technical tasks.
  - Estimate and plan work in sprints or flow-based systems.

- **Coding and Implementation**
  - Write application code, configuration, and infrastructure-as-code where relevant.
  - Implement APIs, UI components, data models, and integrations.
  - Follow secure coding and performance best practices.

- **Unit and Component Testing**
  - Write tests close to the code (unit, component, integration where appropriate).
  - Maintain test coverage thresholds.

- **Refactoring and Technical Debt Reduction**
  - Improve code structure, naming, and modularization.
  - Pay down technical debt in a planned manner.

- **Documentation**
  - Update inline documentation and design docs as needed.
  - Write ADRs for significant technical decisions.

- **Collaboration**
  - Pair programming or mob programming where useful.
  - Continuous communication with PM, design, and QA about edge cases and clarifications.


### Inputs

- **Requirements** (PRD, user stories, acceptance criteria).
- **Architecture design** and RFCs.
- **Coding standards** and guidelines.
- **Backlog** in Jira or equivalent.


### Outputs

- **Source Code and Configurations**
  - Application code, scripts, IaC templates, etc.

- **Automated Tests**
  - Unit, component, and relevant integration tests.

- **Technical Documentation**
  - Updated design docs, ADRs, and README files.

- **Pull Requests**
  - Ready for code review and CI.


### Roles Responsible

- **Primary**
  - Software Engineers (backend, frontend, mobile, etc.)

- **Supporting**
  - Tech Leads
  - QA / Test Engineers
  - DevOps / SRE (for infrastructural aspects)
  - Security Engineers (for secure coding guidance)


### Tools Commonly Used

- Version control (Git) and hosting platforms (GitHub, GitLab, Bitbucket).
- IDEs and editors (IntelliJ, VS Code).
- Language-specific frameworks and libraries.
- Testing frameworks (JUnit, pytest, Jest, Mocha, Cypress, Playwright).
- Linters and formatters (ESLint, Prettier, Checkstyle).


### Example Scenario

In **digital SME lending**, a backend engineer:

- Implements the `POST /applications` endpoint for submitting applications.
- Adds validation rules (e.g., required fields, document references).
- Integrates with the KYC service to initiate identity checks.
- Writes unit tests for validation logic and integration tests for KYC interactions.
- Updates the application service documentation and publishes API changes.

Meanwhile, a frontend engineer:

- Builds a multi-step application form.
- Connects it to the backend APIs.
- Implements client-side validation and user-friendly error messages.


### Best Practices

- **Follow trunk-based development or well-managed branching**: Keep integration frequent.
- **Write tests as part of development**, not as an afterthought.
- **Use feature flags** to decouple deployment from release.
- **Adhere to secure coding guidelines** and language/framework best practices.
- **Keep functions and modules small and focused**: Single responsibility principle.
- **Make code readable**: Prefer clarity over cleverness.
- **Collaborate early on API contracts**: Avoid late integration surprises.


### Common Mistakes

- **Building features in large, long-lived branches** leading to painful merges.
- **Skipping tests** to “move faster”, which slows you later.
- **Not following agreed architecture patterns**, causing fragmentation.
- **Hardcoding configuration** instead of using environment-specific configuration.
- **Insufficient logging and observability** making bugs hard to diagnose.

Effective development produces **high-quality, testable code** that integrates smoothly with the rest of the system.