## 15 – Contexts & Domains for RFCs

This file explains how RFC practices change with **domain context**:

- customer‑facing vs internal platforms,
- B2C vs B2B/enterprise,
- technical vs business‑process heavy systems.

---

### 1. Customer‑Facing vs Internal Platform RFCs

#### 1.1 Customer‑Facing Systems

Examples:

- digital banking channels,
- SME self‑service portals,
- merchant dashboards.

RFC focus:

- user experience and flows,
- responsiveness, availability,
- data privacy and consent,
- integration with product metrics.

Design and product:

- heavily involved in:
  - defining context and goals,
  - reviewing trade‑offs that affect UX and time‑to‑market.

#### 1.2 Internal Platforms & Shared Services

Examples:

- risk engines,
- data platforms,
- identity and access management,
- integration/messaging backbones.

RFC focus:

- capabilities and APIs offered to consuming systems,
- multi‑tenant concerns and isolation,
- evolving platform without breaking consumers,
- long‑term maintainability and cost.

Architecture and platform teams:

- take leading roles, with:
  - product alignment at portfolio level.

---

### 2. B2C vs B2B / Enterprise Domains

#### 2.1 B2C

Characteristics:

- large user base,
- shorter individual interactions,
- heavy emphasis on:
  - conversion,
  - engagement,
  - performance at scale.

RFC implications:

- more focus on:
  - caching, scaling, optimisation patterns,
  - experimentation support,
  - mobile/web client architecture.

#### 2.2 B2B / Enterprise

Characteristics:

- smaller number of high‑value customers,
- more complex journeys and roles,
- heavier integration with:
  - ERP/CRM systems,
  - partner ecosystems.

RFC implications:

- more emphasis on:
  - integration strategies,
  - data contracts and versioning,
  - access control and audit trails,
  - long‑term client commitments.

---

### 3. Domain Examples in Architecture & Governance

Examples:

- **SME Lending RFCs**
  - focus on:
    - decisioning flows,
    - document flows,
    - risk and compliance controls.
- **Payments RFCs**
  - focus on:
    - latency and throughput,
    - failure modes and reconciliation,
    - scheme and regulatory rules.
- **Onboarding / KYC RFCs**
  - focus on:
    - identity verification flows,
    - data privacy and retention,
    - evidence and auditability.

---

### 4. Adapting RFC Content to Your Domain

Questions to ask:

- What types of **risks** are most prominent here?
- Which **stakeholders** care most about outcomes?
- What are the key **NFRs**?
  - performance,
  - availability,
  - security,
  - auditability,
  - flexibility.

Then:

- tune:
  - depth in certain sections,
  - specific diagrams,
  - level of detail.

---

### Connections to Other Files

- `16-startup-vs-enterprise.md` – organisational context overlay.
- `17-regulated-vs-unregulated-products.md` – regulation as another big axis.
- `1-pre-development` modules – domain knowledge that feeds into RFC context sections.

