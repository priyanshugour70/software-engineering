## 17 – RFCs for Regulated vs Unregulated Products

This file explains how regulation level affects **what you must capture in RFCs**.

---

### 1. Regulated Products

Examples:

- lending, deposits, payments,
- insurance and wealth products,
- KYC/AML and onboarding systems.

RFC implications:

- must explicitly address:
  - applicable regulations and policies,
  - control requirements,
  - auditability (logging, retention, evidence).
- more scrutiny from:
  - risk and compliance,
  - regulators (indirectly).

Sections most impacted:

- context & problem (including regulatory drivers),
- security, compliance & privacy,
- operational and risk considerations,
- decision and approvals.

---

### 2. Less Regulated / Unregulated Products

Still subject to:

- generic legal and data‑protection laws,
- contractual obligations with customers.

RFCs can:

- focus more on:
  - user experience,
  - performance and cost,
  - business model impacts.

But:

- security and privacy still matter,
- good logging and auditability are still useful.

---

### 3. Additional Expectations in Regulated Contexts

RFCs may need to:

- reference:
  - specific regulations (IDs, articles),
  - internal policies and standards.
- ensure:
  - changes do not weaken existing controls,
  - or they clearly define compensating controls.
- define:
  - what **evidence** will show compliance:
    - reports,
    - dashboards,
    - audit logs.

Link RFCs to:

- formal security reviews,
- compliance/risk assessments,
- model risk reviews (if using models).

---

### 4. Beginner Checklist

- [ ] Is your RFC:
  - [ ] for a regulated product or critical control?
  - [ ] clearly stating relevant regulations/policies?
  - [ ] specifying required controls and evidence?
- [ ] Have:
  - [ ] risk/compliance reviewed the RFC?
  - [ ] their concerns been captured in text (not just meetings)?

If not, strengthen those aspects before seeking final approval.

---

### Connections to Other Files

- `08-security-compliance-and-risk-in-rfcs.md` – detailed guidance on security and risk content.
- `10-security-review` and `11-compliance-risk` phases – later, more detailed reviews.
- `1-pre-development/5-feasibility-study` – where regulatory feasibility was first analysed.

