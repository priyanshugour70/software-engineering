## 08 – Traceability & Documentation

This file explains **traceability** in Requirements Engineering and how to document requirements so they remain understandable and auditable over time.

---

### 1. What Is Traceability?

**Traceability** means you can:

- follow a **chain of links** between:
  - business objectives or regulatory requirements,
  - product strategy and roadmap items,
  - PRD sections and requirements,
  - user stories and implementation tasks,
  - test cases and test results,
- and go **both ways**:
  - from “Why are we doing this?” to “What exactly was built and tested?”,
  - and from “We changed this component” to “Which objectives and risks does this impact?”

In regulated domains, traceability is often **required** by:

- internal policies,
- external regulators,
- audit and risk functions.

---

### 2. Why Traceability Matters

Benefits:

- **Impact analysis**:
  - when requirements or regulations change, you can quickly find:
    - affected features,
    - services,
    - and tests.
- **Audit readiness**:
  - you can show:
    - which requirements map to which controls and tests,
    - and provide evidence of execution.
- **Clarity and accountability**:
  - avoid orphan requirements with no clear purpose,
  - avoid undocumented behaviours in code.

Even in non‑regulated environments:

- traceability improves maintainability and decision‑making.

---

### 3. Levels of Traceability

You can think in layers:

1. **Objectives / OKRs / Regulatory Requirements**
2. **Roadmap Initiatives & Epics**
3. **PRD Requirements (FRs and NFRs)**
4. **User Stories / Tasks**
5. **Test Cases / Automated Tests / Monitoring**

Aim for:

- at least a **lightweight link** between each adjacent layer.

---

### 4. Practical Traceability Techniques

You do **not** have to implement heavy tooling on day one.

Common, practical techniques:

- **ID Systems**:
  - assign IDs:
    - OBJ‑1, OBJ‑2 for objectives,
    - EPIC‑123, INIT‑001 for epics/initiatives,
    - FR‑1, FR‑2, NFR‑1 for requirements,
    - TEST‑001 for tests.
- **Cross‑Referencing in Docs**:
  - in PRDs, note:
    - “Supports OBJ‑3, EPIC‑12,” etc.
- **Fields in Issue Trackers**:
  - in `Jira`/`Azure DevOps`:
    - custom fields for:
      - Objective/Theme,
      - PRD ID,
      - NFR category.
- **Simple Traceability Tables**:
  - spreadsheets or tables with columns:
    - Objective/Regulation → Requirement ID → Story/Epic ID → Test ID.

Start small:

- focus traceability on:
  - the **most critical** objectives and regulatory items.

---

### 5. Documentation Practices

Good documentation in Requirements Engineering:

- is:
  - **discoverable** (people can find it),
  - **current enough** (not years out of date),
  - **linked** (no isolated islands).

Key practices:

- **Single sign‑posted space**:
  - e.g., one `Confluence` or `Notion` space per product/domain,
  - with:
    - strategy,
    - roadmap views,
    - PRDs,
    - NFRs,
    - traceability tables.
- **Versioning and Status**:
  - mark docs as:
    - Draft,
    - In Review,
    - Baseline for Release X,
    - Superseded.
- **Link, Don’t Copy**:
  - reference:
    - research,
    - business cases,
    - feasibility studies,
  - rather than duplicating content.
- **Lightweight Decision Logs**:
  - track:
    - important requirement changes,
    - reasons and approvers (`25-templates.md`).

---

### 6. Example: Traceability for a Regulatory Requirement

Regulatory requirement:

- “For SME loans of type X, credit decisions must be logged with sufficient detail for later review for at least Y years.”

Traceability chain:

- OBJ‑R1:
  - Regulatory requirement R1.
- EPIC‑45:
  - “Audit‑ready credit decision logging.”
- PRD:
  - NFR‑LOG‑1:
    - defines logging fields, retention, and access control.
- Stories:
  - STORY‑123:
    - implement logging of decisions,
  - STORY‑124:
    - implement secure access to logs.
- Tests:
  - TEST‑LOG‑01:
    - verifies logs are produced correctly,
  - TEST‑RET‑01:
    - verifies retention configuration,
  - plus monitoring checks.

Auditor question:

- “Show me how you comply with R1.”

You can:

- walk through:
  - OBJ‑R1 → EPIC‑45 → NFR‑LOG‑1 → STORY‑123/124 → TEST‑LOG‑01/RET‑01,
  - and show evidence of passing tests and live logs.

---

### 7. Keeping Documentation Healthy Over Time

Common problems:

- docs drift from reality,
- too many duplicate or conflicting pages,
- nobody knows which is the “real” PRD.

Mitigations:

- ownership:
  - each major document has an owner,
  - who is responsible for keeping it reasonably current.
- archiving:
  - clearly mark superseded versions,
  - move old content to archives, not deletion (for audit/history).
- regular clean‑ups:
  - at release or quarterly boundaries,
  - check:
    - links,
    - statuses,
    - missing docs.

---

### 8. Beginner Checklist

- [ ] Can we:
  - [ ] trace major objectives to specific requirements and stories?
  - [ ] trace critical stories back to objectives or regulatory needs?
  - [ ] trace requirements to tests or monitoring where relevant?
- [ ] Are PRDs and NFR docs:
  - [ ] findable in one obvious place?
  - [ ] clearly versioned and labelled?
- [ ] Do we:
  - [ ] record important requirement changes and decisions?

If not, start with a **small traceability table** for your most important objective or regulation and grow from there.

---

### Connections to Other Files

- `05-prd-structure-and-authoring.md` – where and how to embed IDs and references in PRDs.
- `06-user-stories-and-acceptance-criteria.md` – stories and criteria that link to PRD IDs.
- `24-governance-and-change-control.md` – forums and processes for handling requirement changes.
- `25-templates.md` – templates for decision logs and traceability tables.

