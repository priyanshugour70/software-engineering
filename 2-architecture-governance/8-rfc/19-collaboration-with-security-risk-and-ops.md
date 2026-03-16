## 19 – Collaboration with Security, Risk & Ops

This file explains how RFC authors collaborate with **security, risk/compliance, and operations/SRE** throughout the RFC process.

---

### 1. Security Collaboration

Involve security:

- when scoping:
  - identify assets and likely threats,
  - flag high‑risk features or data flows.
- during drafting:
  - review:
    - authentication and authorization approaches,
    - encryption and key management,
    - input validation and protection mechanisms.
- in review:
  - security signs off on:
    - threat model coverage,
    - proposed controls,
    - residual risk.

Outcome:

- fewer late security surprises,
- stronger, more defensible designs.

---

### 2. Risk & Compliance Collaboration

Risk and compliance help:

- interpret regulations and policies into:
  - requirements for logging, approvals, segregation of duties, etc.
- assess:
  - whether the proposal changes risk profile,
  - whether new controls are needed.

Practices:

- invite them to:
  - early context walkthroughs,
  - review cycles for compliance sections.
- document:
  - their concerns and conditions directly in the RFC.

---

### 3. Operations & SRE Collaboration

Ops/SRE teams:

- know:
  - on‑the‑ground realities of running systems,
  - incident patterns,
  - operational constraints.

In RFCs:

- they contribute to:
  - NFRs (availability, latency, error budgets),
  - monitoring/alerting design,
  - rollout and rollback strategies,
  - disaster recovery and backup considerations.

Early involvement:

- prevents “throw over the wall” designs,
- improves day‑2 reliability.

---

### 4. Joint Review Sessions

For high‑impact RFCs:

- run joint sessions with:
  - architecture,
  - security,
  - risk/compliance,
  - ops/SRE,
  - product/engineering leads.

Agenda:

- walk through:
  - context and goals,
  - proposed solution and options,
  - security/compliance and operational sections.
- capture:
  - concerns,
  - decisions,
  - follow‑ups.

Record outcomes:

- in RFC:
  - “Discussion notes”,
  - “Conditions & follow‑ups”.

---

### 5. Beginner Checklist

- [ ] Has security:
  - [ ] reviewed and commented on the RFC?
  - [ ] agreed on main controls and assumptions?
- [ ] Has risk/compliance:
  - [ ] confirmed regulatory and policy coverage?
  - [ ] noted any conditions or required evidence?
- [ ] Has ops/SRE:
  - [ ] reviewed NFRs and operational considerations?
  - [ ] signed off on rollout and DR approaches?

If not, bring these roles into the process *before* final decisions are made.

---

### Connections to Other Files

- `08-security-compliance-and-risk-in-rfcs.md` – content of security/risk sections.
- `11-roles-and-positions.md` – roles on security, risk, and ops sides.
- `24-governance-review-and-lifecycle.md` – forums where these stakeholders participate.

