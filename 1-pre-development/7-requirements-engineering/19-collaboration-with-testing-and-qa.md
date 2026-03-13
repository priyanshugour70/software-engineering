## 19 – Collaboration with Testing & QA

This file explains how Requirements Engineering and **Testing/QA** work together.

Good collaboration here:

- makes requirements more testable,
- reduces defects,
- and improves confidence in releases.

---

### 1. Why QA Collaboration Is Essential

Testers and QA engineers:

- see systems through the lens of:
  - “What can go wrong?”
  - “How do we know it works?”

If they:

- join late,
- only see requirements at the end,

then:

- many edge cases and NFR issues will surface:
  - right before release,
  - or in production.

Early, ongoing collaboration:

- leads to:
  - better acceptance criteria,
  - better coverage,
  - more realistic expectations.

---

### 2. QA Involvement in the Workflow

Map QA into `03-workflow.md`:

- Stage 1–2 (Scope & Draft PRD):
  - QA can:
    - flag high‑risk areas,
    - suggest testability considerations.
- Stage 3–4 (Detail Functional & NFRs):
  - QA can:
    - help define:
      - edge cases,
      - negative flows,
      - NFR scenarios.
- Stage 5 (Stories & Acceptance Criteria):
  - QA:
    - co‑writes or reviews acceptance criteria,
    - plans test cases and automation strategy.
- Stage 6–7 (Review, Baseline, Traceability):
  - QA:
    - checks that tests map to requirements,
    - identifies gaps in coverage.

---

### 3. Co‑Creating Acceptance Criteria

Strong pattern:

- PM/PO, BA, dev, and QA **together** refine acceptance criteria for key stories.

QA can:

- propose:
  - Given/When/Then scenarios,
  - additional edge cases (invalid inputs, concurrency, race conditions).
- highlight:
  - what is ambiguous,
  - what is missing,
  - what is hard to test.

Outcome:

- fewer unclear stories entering sprints,
- smoother test case and automation creation.

---

### 4. Functional vs NFR Testing Considerations

#### 4.1 Functional

QA ensures:

- flows behave as described,
- error messages are clear,
- business rules are correctly enforced.

Requirements role:

- functional requirements and acceptance criteria:
  - should be precise enough for QA to derive tests.

#### 4.2 NFRs

QA and performance/security specialists:

- help:
  - design performance test scenarios,
  - identify security test needs,
  - define observability checks.

Requirements role:

- NFRs:
  - must be written in testable ways (`07-non-functional-requirements.md`),
  - with clear metrics and conditions.

---

### 5. Test Plans & Traceability

QA typically maintains:

- test plans,
- regression suites,
- test case repositories.

Requirements Engineering should support them with:

- clear IDs and mapping:
  - Requirement ID → Story ID → Test Case IDs.

This helps:

- answer questions like:
  - “Which tests cover this regulatory requirement?”
  - “Which tests are affected by this PRD change?”

---

### 6. Using Defects to Improve Requirements

Defects often reveal:

- missing or unclear requirements,
- unconsidered edge cases,
- gaps in NFRs.

Good practice:

- periodically review:
  - clusters of defects,
  - root causes,
  - update:
    - PRDs,
    - NFR specs,
    - templates and checklists.

This creates a **learning loop** between testing and requirements.

---

### 7. Beginner Checklist

- [ ] Are QA/testers:
  - [ ] involved in requirements and PRD reviews?
  - [ ] present in refinement sessions for key stories?
- [ ] Do acceptance criteria:
  - [ ] reflect both positive and negative cases?
  - [ ] cover key NFR scenarios where relevant?
- [ ] Do we:
  - [ ] map tests to requirements using IDs or links?
  - [ ] update requirements templates/checklists based on recurring defects?

If not, start by inviting QA to early stages of the workflow and co‑creating acceptance criteria for high‑risk stories.

---

### Connections to Other Files

- `06-user-stories-and-acceptance-criteria.md` – core of collaboration around story quality.
- `07-non-functional-requirements.md` – NFRs that QA helps validate.
- `08-traceability-and-documentation.md` – mapping tests to requirements.
- `22-best-practices.md` – collaboration best practices across roles.

