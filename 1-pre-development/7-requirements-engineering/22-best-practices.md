## 22 – Best Practices for Requirements Engineering

This file summarizes **best practices** for Requirements Engineering, especially in enterprise and regulated contexts.

Use it as a pattern library of behaviours and approaches you want to encourage.

---

### 1. Start from Outcomes and Context, Not Features

- Ground requirements in:
  - clear problem statements,
  - objectives and metrics,
  - domain and regulatory context.
- Make sure PRDs:
  - start with **why** and **for whom**,  
  - before listing **what**.

Result:

- better alignment with strategy (`6-product-strategy-roadmap`),
- more meaningful requirements.

---

### 2. Co‑Create Requirements with Key Partners

- Involve:
  - PM/PO, BA,
  - design,
  - engineering/architecture,
  - QA/testing,
  - risk/compliance and ops (as needed).
- Use:
  - collaborative refinement sessions,
  - not document hand‑offs.

Result:

- fewer surprises,
- more realistic and testable requirements.

---

### 3. Make NFRs First‑Class Citizens

- Define NFRs:
  - explicitly,
  - measurably,
  - early.
- Involve:
  - architecture,
  - security,
  - ops/SRE.
- Reflect NFRs:
  - in acceptance criteria,
  - in test plans and monitoring.

Result:

- fewer production issues and re‑reviews,
- smoother approvals from risk and architecture boards.

---

### 4. Use IDs and Simple Traceability

- Assign IDs to:
  - objectives,
  - requirements (FR/NFR),
  - stories,
  - tests.
- Maintain:
  - at least lightweight mapping between them (`08-traceability-and-documentation.md`).

Result:

- easier impact analysis and audit readiness,
- fewer “orphan” requirements and tests.

---

### 5. Keep PRDs Focused and Linked

- Keep:
  - core PRD reasonably short and structured,
  - use appendices and links for detail.
- Link to:
  - research,
  - business cases,
  - designs,
  - technical docs,
  - not copy them.

Result:

- PRDs are more likely to be read and updated,
- easier onboarding for new team members.

---

### 6. Iterate – Don’t Aim for Perfect Up Front

- Start with:
  - outlines and high‑level requirements,
  - refine over time.
- Align iteration with:
  - discovery,
  - design,
  - architectural exploration.

Result:

- requirements evolve with understanding,
- lower risk of big rewrite late in the cycle.

---

### 7. Embed Requirements in Regular Cadences

- Align:
  - requirements work with:
    - roadmap planning,
    - quarterly/PI planning,
    - sprint refinements.
- Use governance forums (`24-governance-and-change-control.md`) to:
  - review and baseline requirements,
  - handle changes visibly.

Result:

- requirements stay in sync with plans and reality,
- fewer last‑minute surprises.

---

### 8. Learn from Defects and Incidents

- Use:
  - defect and incident reviews to:
    - identify requirements gaps,
    - update templates and checklists.
- Add:
  - new checklist items for:
    - missed edge cases,
    - overlooked NFRs.

Result:

- continuous improvement of requirements quality,
- fewer repeat issues.

---

### 9. Tailor Practices to Context

- Adapt:
  - amount and formality of documentation,
  - to:
    - startup vs enterprise (`16-startup-vs-enterprise.md`),
    - regulated vs less regulated (`17-regulated-vs-unregulated-products.md`),
    - B2C vs B2B vs internal (`15-contexts-and-domains.md`).

Result:

- not over‑engineering process where it’s not needed,
- but still meeting risk and compliance expectations where it is.

---

### 10. Beginner Checklist

- [ ] Do our requirements:
  - [ ] start from clear goals and context?
  - [ ] cover both functional and NFR aspects?
  - [ ] have IDs and links to stories/tests where important?
- [ ] Are key partners:
  - [ ] involved early and regularly?
  - [ ] part of review and baseline decisions?
- [ ] Do we:
  - [ ] use incidents and defects to improve our requirements process?

If several answers are “no,” pick one or two best practices from this file to start implementing first.

---

### Connections to Other Files

- `03-workflow.md` – best practices mapped across the workflow.
- `07-non-functional-requirements.md` and `08-traceability-and-documentation.md` – critical practice areas.
- `23-common-mistakes.md` – the anti‑patterns that these best practices address.

