## 15 – Contexts and Domains for Requirements Engineering

This file explains how Requirements Engineering **changes by context**, so you can adapt practices instead of copying them blindly.

Key dimensions:

- B2C vs B2B/enterprise,
- customer‑facing products vs internal platforms/tools,
- regulated vs less‑regulated domains.

---

### 1. B2C vs B2B / Enterprise Products

#### 1.1 B2C (Retail Banking App, Consumer Fintech, etc.)

Characteristics:

- many end users,
- shorter, simpler tasks,
- strong focus on:
  - usability,
  - behaviour and engagement metrics.

Requirements implications:

- more emphasis on:
  - UX flows,
  - microcopy and validation messages,
  - experimentation (A/B tests) and rapid iteration.
- NFRs:
  - performance and availability critical at scale,
  - security and privacy still important.

Documentation:

- may be lighter weight,
- but still requires:
  - clear flows,
  - edge‑case handling,
  - NFR expectations.

#### 1.2 B2B/Enterprise (SME Lending, Corporate Portals)

Characteristics:

- fewer users but:
  - more complex journeys,
  - multiple roles (e.g., SME owner, RM, risk officer, ops),
  - integration with external systems (ERP, accounting).

Requirements implications:

- more detailed:
  - process descriptions,
  - business rules,
  - authorization models,
  - data requirements.
- NFRs:
  - may vary strongly by customer tier or portfolio,
  - require stricter auditability.

Documentation:

- heavier PRDs and traceability are more common,
- more stakeholders involved (legal, risk, partners).

---

### 2. Customer‑Facing Products vs Internal Platforms & Tools

#### 2.1 Customer‑Facing Products

Examples:

- digital banking channels,
- SME self‑service portals,
- merchant dashboards.

Focus:

- user experience,
- business outcomes (conversion, activation, retention),
- risk and compliance considerations.

Requirements:

- detailed:
  - user flows,
  - error handling,
  - content and messaging needs.
- NFRs:
  - strict about performance and availability,
  - user‑centric usability expectations.

#### 2.2 Internal Platforms (Risk Engine, Data Platform, KYC Services)

Focus:

- serving multiple consuming products,
- configurability and re‑use,
- performance, resilience, and observability.

Requirements:

- clear:
  - APIs and capabilities,
  - configuration options,
  - support models and SLAs.
- heavy emphasis on:
  - NFRs,
  - data quality and lineage,
  - security and access control.

Documentation:

- tends to have:
  - more technical detail (APIs, schemas),
  - shared NFR baselines for all consumers.

---

### 3. Domain Examples in Financial Services

#### 3.1 SME Lending

As seen across these modules:

- Requirements Engineering must:
  - express:
    - credit policy rules,
    - document handling and verification,
    - decisioning paths and exceptions,
  - handle:
    - multiple personas,
    - regulatory constraints,
    - operational workflows.

#### 3.2 Payments

Requirements must capture:

- transaction flows and states,
- idempotency and reconciliation rules,
- fraud controls and monitoring triggers,
- scheme and regulatory compliance.

NFRs:

- high‑throughput,
- low latency,
- very high availability,
- strong auditability.

#### 3.3 Onboarding & KYC

Requirements cover:

- identity collection and verification steps,
- risk‑based flows (simplified vs enhanced due diligence),
- document types and validation rules,
- data retention and consent.

Heavy involvement of:

- compliance,
- legal,
- operations.

---

### 4. Outside Financial Services (Brief)

These patterns also apply to:

- health tech (with strict privacy & compliance),
- logistics and supply chain,
- large‑scale SaaS (CRM, ERP, HR).

Differences:

- specific regulations and workflows,
- typical NFRs and integration requirements.

But the **core idea** remains:

- understand your domain constraints,
- design requirements practices accordingly.

---

### 5. Beginner Checklist

- [ ] Have you identified:
  - [ ] your primary customer type (B2C, B2B, internal)?
  - [ ] whether your domain is heavily regulated or not?
  - [ ] whether you own customer‑facing products, internal platforms, or both?
- [ ] Have you:
  - [ ] tailored the **depth and style** of PRDs to this context?
  - [ ] adjusted NFR emphasis (e.g., performance vs auditability) accordingly?

If not, review this file together with `07-non-functional-requirements.md` and adapt your templates/processes.

---

### Connections to Other Files

- `16-startup-vs-enterprise.md` – how organization size and maturity affect requirements practices.
- `17-regulated-vs-unregulated-products.md` – regulation as a major contextual factor.
- `3-user-market-research` and `5-feasibility-study` modules – context feeding into requirements.

