## QA / System Testing

### Overview

**QA / System Testing** validates the system **end-to-end** against functional and non-functional requirements. In enterprises and banks, QA often includes **integration testing, regression testing, performance testing, and user acceptance testing (UAT)**.

The goal is to ensure that the system is ready for production deployment and meets expected quality standards.


### Objectives

- **Verify that implemented features meet requirements** and acceptance criteria.
- **Validate integration** between services and with external systems.
- **Test non-functional aspects** such as performance, usability, and resilience.
- **Identify and prioritize defects**.
- **Provide release readiness assessment** to stakeholders.


### Activities

- **Test Planning**
  - Define test strategy and scope (system, integration, regression, UAT).
  - Identify required environments, data, and tools.
  - Align with risk and compliance requirements.

- **Test Case Design**
  - Derive test cases from requirements and user stories.
  - Include positive, negative, boundary, and edge cases.
  - For regulated industries, ensure traceability from requirements to tests.

- **Test Environment Preparation**
  - Set up or refresh test environments (staging, QA).
  - Provision test data (synthetic or anonymized production-like data).
  - Configure integration with external dependencies.

- **Execution of Tests**
  - Functional testing: system-level flows and business logic.
  - Integration testing: interactions between services and external systems.
  - Regression testing: ensure no breakage of existing functionalities.
  - Non-functional testing: performance, load, security (if not handled elsewhere), and usability.

- **Defect Management**
  - Log defects with clear steps and impact.
  - Collaborate with development to triage and fix.
  - Re-test fixed defects and update status.

- **UAT Coordination**
  - Support business users in executing UAT.
  - Collect feedback and approval.

- **Test Reporting**
  - Summarize coverage, pass/fail rates, and major findings.
  - Provide go/no-go recommendations for release.


### Inputs

- **Build artifacts** from CI.
- **Requirements and PRD**, including NFRs.
- **Test plans and test cases**.
- **Architecture and integration documentation**.


### Outputs

- **Test Execution Reports**
  - Coverage metrics, defect counts, severity distribution.

- **Defect Logs**
  - Issues tracked in Jira or similar.

- **UAT Sign-Off**
  - Business acceptance of the release.

- **Release Readiness Assessment**
  - Recommendation about proceeding with deployment.


### Roles Responsible

- **Primary**
  - QA / Test Engineers
  - QA Lead / Test Manager

- **Supporting**
  - Developers
  - Product Manager
  - Business Users (for UAT)
  - DevOps / SRE (for environment support)


### Tools Commonly Used

- Test management: TestRail, Zephyr, qTest.
- Automation frameworks: Selenium, Cypress, Playwright, JUnit, pytest.
- Performance testing: JMeter, Gatling, Locust.
- Issue tracking: Jira, Azure DevOps.
- Collaboration: Confluence, documentation tools.


### Example Scenario

For **digital SME lending**:

- QA creates system test cases covering:
  - New loan application creation.
  - Document upload and error scenarios.
  - Application status checking.
  - Underwriting decision paths (approved, declined, manual review).
  - Notifications and communications.

- Performance tests:
  - Simulate peak loads during local tax seasons when loan applications spike.
  - Validate that the system meets latency and throughput SLAs.

- UAT:
  - Relationship managers use the system in a staging environment with realistic data.
  - They provide feedback on flows and wording.

Test results show a few medium-severity issues; fixes are made, retested, and QA issues a **go** recommendation with no known critical defects.


### Best Practices

- **Align test scope with risk**: Heavier focus on high-risk areas.
- **Automate regression tests**: Reduce manual testing effort over time.
- **Use production-like data and environments** where possible (with privacy controls).
- **Collaborate closely with dev and product**: Clarify expected behavior and edge cases.
- **Ensure traceability** from requirements to test cases and defects.
- **Include NFR testing**: Performance, resilience, and usability.


### Common Mistakes

- **Leaving QA to the end**: Late discovery of issues and rushed fixes.
- **Insufficient test data** or unrealistic environments.
- **Testing only happy paths** and ignoring negative or failure scenarios.
- **No clear exit criteria**: Releasing without formal go/no-go criteria.
- **Not involving business users** in UAT, leading to misaligned expectations.

Effective QA and system testing significantly **reduce the risk of production incidents** and ensure that the solution truly meets user and business needs.