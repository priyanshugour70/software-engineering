## 21 – Real‑World RFC Examples & Scenarios

This file gives **short, focused scenarios** showing how RFCs shape day‑to‑day technical decisions.

---

### Example 1 – Deciding Whether to Introduce a New Database Technology

Scenario:

- team wants to use a new database type for a new feature.

Questions:

- is this local or cross‑cutting?
- does it affect risk/compliance or operations?

Outcome:

- if high impact:
  - an RFC:
    - compares:
      - existing DB vs new DB,
      - pros/cons on performance, cost, risk,
      - operational readiness,
    - documents decision and conditions.

---

### Example 2 – Introducing a New External Vendor Service

Scenario:

- product team wants to integrate a third‑party KYC provider.

RFC role:

- capture:
  - data flows and protection,
  - vendor risk considerations,
  - fallback scenarios,
  - regulatory implications.

Security and risk:

- use RFC as:
  - basis for their assessments,
  - record for approvals.

---

### Example 3 – Splitting a Monolith into Services

Scenario:

- engineering wants to break a monolith into services.

RFC work:

- describe:
  - current pain (deployment, scaling, ownership),
  - target domain boundaries,
  - migration phases.

Trade‑offs:

- complexity vs modularity,
- short‑term risk vs long‑term agility.

---

### Example 4 – Handling a Large Regulatory Change

Scenario:

- new regulation changes lending decision and reporting requirements.

RFCs:

- map:
  - regulatory clauses to:
    - system changes,
    - data flows,
    - logging,
    - reporting.

Used by:

- compliance and risk to:
  - verify coverage,
  - plan evidence collection.

---

### Example 5 – Clarifying Scope of a Platform Improvement

Scenario:

- platform team wants to introduce a new messaging backbone.

RFC clarifies:

- in scope:
  - new backbone for 2–3 key domains,
  - initial consumers and migration path.
- out of scope:
  - full rewrite of all event flows,
  - decommission of all legacy queues in phase 1.

Outcome:

- realistic expectations across teams,
- better planning.

---

### Connections to Other Files

- `03-when-to-use-an-rfc.md` – deciding when these scenarios need RFCs.
- `05-rfc-structure-and-authoring.md` – where to capture each scenario’s content.
- `26-checklists.md` – checklists to validate RFC quality for similar cases.

