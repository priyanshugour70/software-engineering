## Security Review

### Overview

The **Security Review** phase ensures that the proposed solution **meets security standards and adequately manages threats**. In banks and large enterprises, this phase is mandatory for any system handling **sensitive data, financial transactions, or regulated workflows**.

Security review combines **threat modeling, control selection, and validation** of alignment with security policies.


### Objectives

- **Identify security threats and vulnerabilities** in the architecture and design.
- **Define required security controls** (preventive, detective, corrective).
- **Ensure compliance** with internal security policies and external regulations.
- **Influence design** to adopt secure patterns and reduce attack surface.
- **Document security posture and residual risk**.

Security review is not a one-time event; it should be revisited throughout the lifecycle.


### Activities

- **Threat Modeling**
  - Identify assets (data, services) and trust boundaries.
  - Enumerate threats (e.g., STRIDE model).
  - Assess likelihood and impact.

- **Security Control Design**
  - Authentication and authorization (e.g., SSO, RBAC, ABAC).
  - Data protection (encryption at rest and in transit).
  - Input validation and output encoding.
  - Logging and monitoring for security events.
  - Key management and secrets handling.

- **Review of Architecture & Design**
  - Validate use of secure patterns (e.g., zero trust, least privilege).
  - Evaluate third-party dependencies and supply chain risks.
  - Confirm adherence to secure coding standards.

- **Security Requirements & NFRs**
  - Document security-specific requirements for implementation and testing.
  - Define penetration testing and vulnerability scanning requirements.

- **Sign-Off & Follow-Up**
  - Provide security approval or conditional approval with remediation items.
  - Track security issues in backlogs and risk registers.


### Inputs

- **Architecture design** and diagrams.
- **Data classification** (public, internal, confidential, regulated).
- Organization’s **security policies and standards**.
- Known **threat intelligence** relevant to the domain.
- System context and trust boundaries.


### Outputs

- **Threat Model**
  - Assets, trust boundaries, threats, and mitigations.

- **Security Requirements**
  - Specific controls and test requirements.

- **Security Review Report**
  - Summary of findings, recommended actions, and residual risks.
  - Approval or conditional approval.

- **Backlog Items**
  - Security tasks and stories to be implemented.


### Roles Responsible

- **Primary**
  - Security Architect / Application Security Engineer

- **Supporting**
  - Solution Architect
  - Engineering Leads
  - Product Manager (for risk acceptance decisions)
  - Compliance / Risk (if tied closely to regulatory requirements)


### Tools Commonly Used

- Threat modeling tools (e.g., Microsoft Threat Modeling Tool, custom tools).
- Static code analysis (SAST) and dynamic testing (DAST).
- Dependency scanning tools.
- Secrets management solutions (e.g., HashiCorp Vault).
- SIEM and logging platforms for security monitoring.


### Example Scenario

For **digital SME lending**:

- Asset: personal and financial data of SME owners; high sensitivity.
- Threats:
  - Data exfiltration via compromised web app or API.
  - Unauthorized access by internal staff (insider threat).
  - Account takeover of SME portal accounts.

Mitigations:

- Strong authentication with MFA and device fingerprinting.
- Fine-grained authorization with role-based access control.
- Encryption of all sensitive data at rest and in transit.
- Strict segregation of duties and access logging for internal users.
- Web application firewall (WAF) with OWASP protections.

Security review results:

- Several required controls are documented as **security stories** in the backlog.
- Conditional approval is granted, with the requirement that a **penetration test** be completed before go-live and critical findings addressed.


### Best Practices

- **Perform security review early and often**: Start at RFC and refine at design and implementation.
- **Include multidisciplinary perspectives**: Architecture, engineering, operations, and product.
- **Use standardized checklists and patterns**: Reduce variability and missed issues.
- **Integrate security into CI/CD**: Automated checks complement manual review.
- **Capture residual risk and risk acceptance**: Ensure informed decisions.

In banking, security findings often feed into **formal risk registers** and **control libraries**.


### Common Mistakes

- **Treating security as a gate at the end**, rather than a continuous activity.
- **Underestimating insider threats** and over-focusing only on external attackers.
- **Not documenting security decisions and trade-offs**.
- **Ignoring dependency and supply chain risks**, e.g., third-party libraries and SaaS.
- **Skipping verification**: Controls defined but not validated by testing.

Security review helps ensure that **protecting customers and the organization is built into the system from the start**.