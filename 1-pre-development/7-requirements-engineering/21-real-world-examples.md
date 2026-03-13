## 21 – Real‑World Examples & Scenarios

This file provides **short, focused scenarios** to show Requirements Engineering decisions in day‑to‑day situations.

---

### Example 1 – Clarifying a Vague Stakeholder Request

Scenario:

- stakeholder says:
  - “We need a better SME dashboard.”

Problem:

- vague,
- no clear persona, goals, or acceptance criteria.

Requirements Engineering response:

1. Ask clarifying questions:
   - who uses it?
   - what do they do today?
   - what problems do they face?
   - what decisions/actions should the dashboard enable?
2. Turn into:
   - clear goals and non‑goals,
   - user stories with acceptance criteria,
   - updated PRD section.

Outcome:

- reduces risk of building a visually nice but useless dashboard.

---

### Example 2 – Handling Conflicting Requests from Two Stakeholders

Scenario:

- sales wants:
  - minimal data entry before showing loan offers,
- risk wants:
  - more data collected upfront for better decisions.

Requirements Engineering response:

1. Make trade‑offs explicit:
   - capture both perspectives in PRD,
   - quantify:
     - drop‑off risk vs decision quality.
2. Propose sliced solution:
   - minimal data for:
     - indicative offers,
   - additional data required for:
     - final binding decisions.
3. Document decision in:
   - decision log,
   - requirements and NFRs.

Outcome:

- both sides understand:
  - compromise and rationale,
  - reducing friction later.

---

### Example 3 – Late Discovery of a Critical Edge Case

Scenario:

- during testing,
- QA finds:
  - SME customers with multiple legal entities and complex ownership trees break certain flows.

Requirements Engineering response:

1. Treat as:
   - requirement gap, not just “bug.”
2. Update:
   - PRD:
     - describe multi‑entity scenarios,
   - stories:
     - add specific use‑case stories,
   - test cases:
     - include new edge‑case scenarios.
3. Analyse impact:
   - on timeline and scope,
   - communicate change via governance (if necessary).

Outcome:

- requirements and tests now cover reality more fully,
- traceability updated for similar future changes.

---

### Example 4 – Making NFRs Explicit After an Incident

Scenario:

- production incident due to:
  - under‑specified availability or performance expectations.

Requirements Engineering response:

1. After incident review:
   - identify which NFRs were missing or unclear.
2. Update:
   - NFR baseline,
   - PRDs for impacted systems,
   - runbooks and monitoring requirements.
3. Add:
   - checklist items:
     - to prevent similar omissions in future requirements work.

Outcome:

- the incident leads to:
  - **improved requirements practices**, not just a one‑off fix.

---

### Example 5 – Introducing a Simple Traceability Table

Scenario:

- team struggles to answer:
  - “Which requirements correspond to this regulatory change?”

Requirements Engineering response:

1. Start a traceability table for:
   - the highest‑risk regulatory area.
2. Add rows:
   - Regulation ID → PRD requirement IDs → Story IDs → Test IDs.
3. Update:
   - as new requirements or tests are added.

Outcome:

- quick wins in:
  - answering regulator/audit questions,
  - impact analysis for changes.

---

### How to Use These Examples

- Practice:
  - how you would respond in similar situations,
  - which documents and artifacts you would update.
- Discuss:
  - with your team:
    - where your current process does something similar,
    - where you might adopt better patterns.

---

### Connections to Other Files

- `05-prd-structure-and-authoring.md` – how PRDs reflect these scenarios.
- `06-user-stories-and-acceptance-criteria.md` – turning vague asks into concrete stories.
- `07-non-functional-requirements.md` – expressing NFRs more explicitly.
- `08-traceability-and-documentation.md` – example 5 maps directly to traceability practices.

