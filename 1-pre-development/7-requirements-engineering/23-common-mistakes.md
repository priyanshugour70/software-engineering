## 23 – Common Mistakes in Requirements Engineering

This file lists frequent **anti‑patterns** in Requirements Engineering and how to avoid them.

Use it as a checklist of things to watch out for.

---

### 1. Vague or Ambiguous Requirements

Symptoms:

- requirements say:
  - “improve UX,”
  - “system should be fast,”
  - “support SME loans.”

Problems:

- nobody agrees what “done” means,
- QA cannot design adequate tests,
- stakeholders feel misled when outcomes differ from expectations.

Better:

- use:
  - specific personas,
  - clear behaviours,
  - measurable NFRs and acceptance criteria.

---

### 2. Writing Requirements in Isolation

Symptoms:

- one role (often BA or PM) writes specs alone,
- others only see them when “done.”

Problems:

- missing:
  - technical constraints,
  - UX realities,
  - testability considerations,
  - risk/compliance/ops needs.

Better:

- co‑create requirements with:
  - design,
  - engineering/architecture,
  - QA,
  - risk/compliance,
  - operations.

---

### 3. Ignoring Non‑Functional Requirements

Symptoms:

- PRDs and stories:
  - focus almost entirely on happy‑path functionality,
  - little or no mention of:
    - performance,
    - resilience,
    - security,
    - logging,
    - observability.

Problems:

- performance issues,
- production incidents,
- security and compliance findings.

Better:

- treat NFRs as first‑class (`07-non-functional-requirements.md`),
- involve architecture, security, and ops early.

---

### 4. Over‑Detailed Specifications Far into the Future

Symptoms:

- huge PRDs attempting to specify:
  - all details for 12–24 months of work,
  - before discovery or design.

Problems:

- waste (most of it will change),
- false sense of certainty,
- difficult to maintain.

Better:

- specify:
  - enough detail for near‑term increments,
  - less detail further out,
  - align with multi‑horizon roadmaps.

---

### 5. No Clear Scope or Non‑Goals

Symptoms:

- everyone brings their own expectations,
- scope grows silently,
- “we thought this was included” appears near release.

Problems:

- missed deadlines,
- quality compromises,
- stakeholder frustration.

Better:

- explicitly document:
  - in‑scope and out‑of‑scope items,
  - goals and non‑goals in PRD and planning docs.

---

### 6. Lack of Traceability

Symptoms:

- hard to answer:
  - “Why do we have this feature?”
  - “Where is this regulatory requirement implemented and tested?”

Problems:

- painful audits,
- accidental removal of important behaviours,
- difficulty in impact analysis.

Better:

- use IDs and simple mapping (`08-traceability-and-documentation.md`),
- focus first on high‑risk objectives and requirements.

---

### 7. Treating Requirements as a Rigid Contract

Symptoms:

- mindset:
  - “we signed off the spec, now just build it exactly.”

Problems:

- discourages:
  - learning,
  - discovery,
  - adaptation to new information.

Better:

- treat requirements as:
  - living agreements,
  - with:
    - clear baselines for increments,
    - controlled change management (`24-governance-and-change-control.md`).

---

### 8. Over‑Indexing on Tools Instead of Practices

Symptoms:

- heavy investment in:
  - requirements management or ALM tools,
  - but:
    - unclear ownership,
    - inconsistent usage,
    - weak content.

Problems:

- false comfort from tooling,
- extra overhead with limited benefit.

Better:

- first:
  - establish clear processes and expectations,
  - then configure tools to support them.

---

### 9. Excluding QA, Ops, and Risk Until Late

Symptoms:

- QA first sees requirements:
  - during test planning,
- ops and risk:
  - see them during go‑live preparations.

Problems:

- late discoveries of:
  - missing testability,
  - operability,
  - risk/compliance constraints.

Better:

- include QA, ops, and risk:
  - in earlier workflow stages,
  - especially for NFRs and critical flows.

---

### 10. Beginner Checklist

- [ ] Are our requirements:
  - [ ] specific and testable?
  - [ ] including NFRs?
  - [ ] scoped with clear non‑goals?
- [ ] Do we:
  - [ ] co‑create with key partners?
  - [ ] maintain at least basic traceability?
  - [ ] treat requirements as evolving with controlled change?

If multiple answers are “no,” prioritise improving these areas before adding more process or tooling.

---

### Connections to Other Files

- `22-best-practices.md` – positive patterns to replace these mistakes.
- `07-non-functional-requirements.md` and `08-traceability-and-documentation.md` – frequent problem areas.
- `24-governance-and-change-control.md` – how governance can prevent or correct these anti‑patterns.

