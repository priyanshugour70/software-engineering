## 11 – Roles and Positions in RFC Work

This file explains **who is involved** in creating, reviewing, and approving RFCs, and how they collaborate.

---

### 1. Core Technical Roles

#### 1.1 Senior Engineer / Tech Lead

Responsibilities:

- often **own and author** RFCs for their domain,
- translate requirements into:
  - technical options,
  - architectures,
  - and implementation impacts.
- facilitate:
  - discussions between product, engineering, and architecture.

They are usually:

- the primary driver of an RFC from:
  - idea → draft → accepted decision.

#### 1.2 Solution / Domain Architect

Responsibilities:

- ensure proposals:
  - align with target architectures and standards,
  - manage technical debt and long‑term complexity.
- help:
  - shape options and trade‑offs,
  - identify reuse opportunities,
  - design boundaries and contracts.

In many orgs:

- architects:
  - co‑author the RFC,
  - or act as key reviewers and approvers.

#### 1.3 Staff / Principal Engineer (where present)

Responsibilities:

- lead RFCs:
  - that cut across many teams or platforms,
  - or that represent foundational technical bets.
- mentor others on:
  - good RFC practices,
  - option analysis,
  - long‑term thinking.

---

### 2. Product & Requirements Roles

#### 2.1 Product Manager / Product Owner

Responsibilities:

- ensure:
  - the **problem and goals** in the RFC:
    - match product strategy and requirements.
- provide:
  - business and user context,
  - success metrics and constraints.
- participate in:
  - option trade‑off discussions (value, risk, time).

They rarely author the whole RFC, but:

- should **co‑own** the alignment between RFC and product intent.

#### 2.2 Business Analyst / Requirements Engineer

Responsibilities:

- help:
  - connect RFC content to PRDs and requirements,
  - express business rules and constraints,
  - maintain traceability.

In regulated environments:

- often central in:
  - linking RFC decisions to regulatory requirements.

---

### 3. Security, Risk & Compliance Roles

#### 3.1 Security Architect / Security Engineer

Responsibilities:

- review:
  - the security section of RFCs,
  - architecture diagrams and flows.
- identify:
  - threats,
  - vulnerabilities,
  - control gaps.
- propose:
  - mitigations,
  - security patterns,
  - additional requirements (e.g., logging, encryption).

#### 3.2 Risk & Compliance Partners

Responsibilities:

- ensure:
  - proposals stay within risk appetite,
  - regulatory and policy requirements are met.
- review:
  - compliance and auditability sections,
  - impact on existing controls.

They may:

- request:
  - additional controls,
  - evidence requirements,
  - or modifications before approval.

---

### 4. Operations, SRE & Platform Roles

#### 4.1 SRE / Operations Engineers

Responsibilities:

- assess:
  - operational impact of proposals,
  - monitoring, alerting, and incident response needs.
- contribute to:
  - NFR and operational sections,
  - rollout and disaster recovery plans.

#### 4.2 Platform / Infrastructure Leads

Responsibilities:

- ensure:
  - proposals fit platform capabilities and roadmaps.
- identify:
  - shared services to reuse,
  - platform improvements needed.

They help avoid:

- one‑off solutions that bypass platform strengths.

---

### 5. Governance & Leadership Roles

#### 5.1 Architecture Board / Design Authority

Responsibilities:

- act as:
  - formal decision body for significant RFCs.
- ensure:
  - alignment with enterprise architecture,
  - cross‑domain impacts are considered.

#### 5.2 Business & Technology Leadership

Responsibilities:

- for very high‑impact RFCs:
  - may:
    - provide final approval,
    - set strategic constraints,
    - decide on funding implications.

---

### 6. Collaboration Patterns

Good patterns:

- **Co‑authoring**:
  - tech lead + architect,
  - with inputs from product, security, ops.
- **Multi‑role reviews**:
  - one RFC review that includes:
    - architecture,
    - security,
    - risk,
    - ops,
    - product.
- **Clear ownership**:
  - one person clearly responsible for:
    - driving the RFC to conclusion,
    - integrating feedback.

---

### 7. Beginner Checklist

- [ ] Is it clear:
  - [ ] who owns each RFC?
  - [ ] which architect(s) or principal engineers must review it?
  - [ ] which security, risk, and ops contacts are needed?
- [ ] Are:
  - [ ] product and requirements partners engaged for context and goals?
  - [ ] governance bodies identified for final approval (if needed)?

If not, define a simple **RACI** for RFCs in your organisation.

---

### Connections to Other Files

- `12-skills.md` – skills needed for people in these roles.
- `24-governance-review-and-lifecycle.md` – where these roles meet to review and approve RFCs.
- `22-best-practices.md` – collaboration best practices across all roles.

