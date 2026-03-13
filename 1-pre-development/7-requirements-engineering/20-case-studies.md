## 20 – Case Studies for Requirements Engineering

This file gives **longer, narrative case studies** showing Requirements Engineering in action.

They are simplified, anonymized composites aimed at learning.

We cover:

- Case 1: Digital SME Lending – New Application Journey
- Case 2: Regulatory Change Program – Lending Rules Update

---

### Case 1 – Digital SME Lending: New Application Journey

#### 1.1 Context

- Large bank with:
  - paper‑heavy SME lending,
  - long decision times,
  - fragmented systems.
- Initiative:
  - launch a new **digital SME lending application journey** for existing customers.

High‑level goals:

- reduce time to decision,
- improve customer experience,
- maintain or improve risk controls.

---

#### 1.2 Requirements Engineering Approach

**Scope & Slicing**

- First increment:
  - existing SME customers in one country,
  - working‑capital loans of limited size,
  - web channel only.
- Out of scope:
  - new‑to‑bank SMEs,
  - mobile apps,
  - secured loans.

**PRD Drafting**

- PRD included:
  - background and goals,
  - personas (SME owner, RM, credit officer),
  - current vs future journeys,
  - functional requirements:
    - application creation,
    - document upload,
    - tracking and notifications,
  - NFRs:
    - performance targets,
    - availability,
    - security,
    - logging and auditability.

**Collaboration**

- Designers:
  - helped define step‑by‑step flows,
  - revealed missing states (draft, submitted, in review, decisioned).
- Architects:
  - validated integration patterns with risk engine and KYC platforms,
  - highlighted dependencies.
- QA:
  - co‑created acceptance criteria for key stories,
  - identified additional error cases.

---

#### 1.3 NFRs & Traceability

- NFRs:
  - P95 response time ≤ 3 seconds for main pages,
  - 99.5% availability for business hours,
  - strict logging of application lifecycle events.
- Traceability:
  - regulatory requirements mapped to:
    - specific functional and NFR IDs,
    - stories and tests,
    - log fields and retention configurations.

---

#### 1.4 Outcomes & Lessons

Positive results:

- time to decision improved for target segment,
- higher digital adoption,
- lower manual errors.

Key lessons:

- early involvement of risk/compliance:
  - avoided late rewrites,
  - improved design of logging and disclosures.
- collaboration with QA:
  - reduced production defects in edge cases,
  - improved test coverage.
- incremental scope:
  - allowed learning before expanding to other segments and channels.

---

### Case 2 – Regulatory Change: Lending Rules Update

#### 2.1 Context

- New regulation required:
  - changes to affordability checks,
  - extra disclosures to SME borrowers,
  - specific data retention policies.

Impact:

- multiple systems:
  - application capture,
  - decisioning engine,
  - document generation,
  - archival.

---

#### 2.2 Requirements Engineering Approach

**Regulatory Interpretation**

- Risk and compliance:
  - interpreted regulatory text into:
    - policy rules,
    - control objectives,
    - documentation expectations.

**PRD & NFRs**

- PRD focused on:
  - which checks must be performed,
  - which disclosures must appear where,
  - what data must be stored and for how long.
- NFRs covered:
  - audit trail detail,
  - access control and segregation of duties,
  - reporting and extraction capabilities.

**Traceability**

- regulatory clauses:
  - assigned IDs (e.g., REG‑R1, R2, …),
  - mapped to:
    - PRD requirements (FR/NFR),
    - system components,
    - tests and reports.

---

#### 2.3 Multi‑Team Collaboration

- Architecture:
  - identified impacted systems and services.
- Product and BAs:
  - wrote and refined requirements per system.
- QA:
  - designed:
    - functional tests to verify new rules,
    - regression tests to ensure no unintended side effects.
- Operations:
  - prepared updated runbooks and support scripts,
  - validated reporting flows.

---

#### 2.4 Outcomes & Lessons

Positive outcomes:

- regulation implemented on time,
- clean audit trail of:
  - requirements,
  - tests,
  - approvals.

Lessons:

- traceability from regulation → requirement → test:
  - made audits significantly smoother.
- shared decision and change logs:
  - reduced confusion about why certain behaviours changed.

---

### How to Use These Case Studies

As you read:

- identify:
  - which aspects are close to your situation,
  - which practices you can reuse (scope decisions, collaboration, traceability).
- discuss:
  - how your current requirements process compares,
  - where you might adopt similar patterns.

---

### Connections to Other Files

- `03-workflow.md` – both case studies follow the workflow stages.
- `05-prd-structure-and-authoring.md` – PRD sections used in the stories.
- `07-non-functional-requirements.md` and `08-traceability-and-documentation.md` – central to both cases.
- `21-real-world-examples.md` – shorter scenarios you can relate to everyday work.

