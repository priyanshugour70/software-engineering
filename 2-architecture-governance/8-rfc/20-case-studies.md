## 20 – Case Studies: RFCs in Practice

This file presents **longer, narrative case studies** illustrating how RFCs are used in real programmes.

---

### Case 1 – New Digital SME Lending Platform

#### Context

- Bank wants:
  - a new digital SME lending platform,
  - to replace fragmented legacy flows.
- Prior work:
  - pre‑development phases complete,
  - clear strategy, feasibility, and requirements.

#### RFC Work

- multiple RFCs:
  - core platform architecture,
  - integration with risk engine,
  - document management and storage,
  - operations and monitoring approach.

Each RFC:

- documented:
  - options (e.g., modernise legacy vs new service),
  - trade‑offs,
  - NFRs,
  - security and compliance implications.

Architecture board:

- reviewed and approved,
- set conditions (e.g., POCs, performance thresholds).

Outcome:

- coherent platform design,
- clear decisions for later audit,
- smoother security and risk reviews.

---

### Case 2 – Core Payments System Modernisation

#### Context

- high‑volume payments system:
  - performance and resilience issues,
  - regulator scrutiny after incidents.

#### RFC Work

- RFCs for:
  - event‑driven architecture introduction,
  - data replication and reconciliation strategies,
  - geo‑redundant deployment.

Key aspects:

- intensive sequence and failure‑mode diagrams,
- strong NFR articulation,
- close collaboration with:
  - SRE,
  - security,
  - compliance.

Outcomes:

- new architecture with:
  - better uptime,
  - clearer observability,
  - improved audit posture.
- RFCs used:
  - in regulator conversations,
  - as evidence of “due care”.

---

### How to Use These Case Studies

- identify similarities with your own:
  - domain,
  - system landscape,
  - governance model.
- adapt:
  - number and scope of RFCs,
  - level of detail in each,
  - stakeholder mix in reviews.

---

### Connections to Other Files

- `01-concepts.md` and `04-workflow.md` – the backbone followed in both cases.
- `06-option-analysis-and-tradeoffs.md` – heavily used in platform and modernisation decisions.
- `08-security-compliance-and-risk-in-rfcs.md` and `19-collaboration-with-security-risk-and-ops.md` – central to regulated case studies.

