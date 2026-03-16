## 22 – Best Practices for RFCs

This file summarises **best practices** for RFCs in architecture & governance.

---

### 1. Start from Problem & Outcomes, Not Technology

- clearly state:
  - context and problem,
  - goals and non‑goals,
  - success metrics.
- avoid:
  - starting with “we should use \<tech>” without justification.

---

### 2. Co‑Author with Key Partners

- co‑author RFCs with:
  - tech leads/architects,
  - product/requirements,
  - where relevant: security, risk, ops.

Result:

- richer proposals,
- fewer review cycles,
- higher trust.

---

### 3. Always Consider at Least One Real Alternative

- don’t pretend:
  - there was only one possible solution.
- compare:
  - at least one serious alternative,
  - even if recommended option remains the same.

---

### 4. Keep RFCs Focused, Use Appendices for Detail

- keep core RFC:
  - ~5–10 pages for most proposals,
  - longer only when absolutely necessary.
- link:
  - detailed specs,
  - POC results,
  - external documents in appendices.

---

### 5. Make NFRs, Security & Compliance First‑Class

- dedicate clear sections,
- be explicit and measurable,
- involve relevant experts early.

---

### 6. Use Clear IDs, Status, and Lifecycle

- use:
  - IDs (RFC‑001),
  - statuses (Draft, In Review, Accepted, Superseded),
  - dates and owners.
- maintain:
  - index of RFCs and their current state.

---

### 7. Align RFC Timing with Roadmap & Delivery

- schedule RFC work:
  - early enough to inform design and planning,
  - but late enough to use latest requirements and feasibility.

Avoid:

- writing RFCs long before strategy or requirements are stable.

---

### 8. Treat RFCs as Living Documents

- update when:
  - major assumptions change,
  - direction changes materially.
- clearly:
  - mark superseded RFCs,
  - link to replacements.

---

### 9. Learn from Incidents and Reviews

- after major incidents or audits:
  - revisit relevant RFCs,
  - identify gaps in:
    - option analysis,
    - NFRs,
    - security/risk considerations.
- improve:
  - templates,
  - checklists,
  - governance rules.

---

### 10. Beginner Checklist

- [ ] Does the RFC:
  - [ ] start with clear context and problem?
  - [ ] include goals and non‑goals?
  - [ ] compare at least one alternative?
  - [ ] address NFRs, security, and compliance?
  - [ ] record decisions and sign‑offs?
- [ ] Is it:
  - [ ] reasonably scoped and focused?
  - [ ] linked to requirements and implementation work?

---

### Connections to Other Files

- `03-when-to-use-an-rfc.md` and `04-workflow.md` – where best practices apply in the lifecycle.
- `06-option-analysis-and-tradeoffs.md` and `08-security-compliance-and-risk-in-rfcs.md` – critical quality areas.
- `23-common-mistakes.md` and `26-checklists.md` – anti‑patterns and checklists to complement these practices.

