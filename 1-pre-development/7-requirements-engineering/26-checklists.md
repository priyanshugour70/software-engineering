## 26 – Checklists for Requirements Engineering

This file provides **short, actionable checklists** derived from the rest of the module.

Use them before:

- baselining requirements for an increment,
- starting development,
- or going into major reviews.

---

### 1. Scope & Context Checklist

- [ ] Have we:
  - [ ] clearly defined in‑scope epics/features for this increment?
  - [ ] listed important non‑goals / out‑of‑scope items?
- [ ] Do we understand:
  - [ ] main personas and journeys?
  - [ ] relevant domain and regulatory context?
- [ ] Are goals and success metrics:
  - [ ] written down?
  - [ ] linked to higher‑level objectives?

If not, revisit `02-objectives.md`, `04-scope-and-slicing.md`, and `05-prd-structure-and-authoring.md`.

---

### 2. Functional Requirements Checklist

- [ ] Does the PRD:
  - [ ] cover key flows from start to finish?
  - [ ] capture important edge cases and error scenarios?
- [ ] Are functional requirements:
  - [ ] specific enough to derive stories and tests?
  - [ ] free of vague phrases like “improve UX” or “handle all cases”?
- [ ] Are dependencies:
  - [ ] identified at least at a high level?

If not, refine functional sections and journeys before proceeding.

---

### 3. NFR Checklist

- [ ] Do we have explicit NFRs for:
  - [ ] performance and capacity?
  - [ ] availability and resilience?
  - [ ] security and privacy?
  - [ ] observability and operability?
  - [ ] compliance and auditability (if applicable)?
- [ ] Are NFRs:
  - [ ] measurable (metrics, targets, conditions)?
  - [ ] aligned with architecture and platform capabilities?
  - [ ] visible to security, risk, and ops?

If not, strengthen NFR sections (`07-non-functional-requirements.md`) and review with architecture and ops.

---

### 4. Stories & Acceptance Criteria Checklist

- [ ] For key stories:
  - [ ] is the persona, capability, and benefit clear?
  - [ ] do acceptance criteria cover:
    - [ ] happy path,
    - [ ] negative/error cases,
    - [ ] NFR aspects where relevant?
- [ ] Are stories:
  - [ ] small enough for 1–2 sprints?
  - [ ] linked to PRD requirements and epics?
- [ ] Has QA reviewed:
  - [ ] stories and acceptance criteria for testability?

If not, co‑refine stories with dev, QA, and design (`06-user-stories-and-acceptance-criteria.md`, `19-collaboration-with-testing-and-qa.md`).

---

### 5. Traceability & Documentation Checklist

- [ ] Do we have:
  - [ ] IDs for important objectives, requirements, and stories?
  - [ ] at least a simple mapping for high‑risk or regulatory items?
- [ ] Are PRDs and NFR docs:
  - [ ] stored in a clear, shared location?
  - [ ] labelled with status and versions?
- [ ] Are major decisions:
  - [ ] recorded in a decision log?

If not, implement minimal traceability and logs (`08-traceability-and-documentation.md`, `25-templates.md`).

---

### 6. Collaboration & Governance Checklist

- [ ] Have:
  - [ ] design,
  - [ ] engineering/architecture,
  - [ ] QA,
  - [ ] risk/compliance (if needed),
  - [ ] operations,
  - reviewed requirements for this increment?
- [ ] Do we:
  - [ ] baseline requirements at an appropriate point?
  - [ ] classify and handle requirement changes (clarification/minor/major)?
  - [ ] communicate changes and impacts?

If not, review collaboration and governance approaches (`18-collaboration-with-design-and-architecture.md`, `19-collaboration-with-testing-and-qa.md`, `24-governance-and-change-control.md`).

---

### 7. Personal Skill Checklist

- [ ] Can you:
  - [ ] clearly explain the problem and context?
  - [ ] write stories and acceptance criteria others find clear?
  - [ ] discuss NFRs at a basic level with engineers and ops?
  - [ ] work productively with QA, design, and risk?
- [ ] Do you:
  - [ ] seek feedback on your requirements documents?
  - [ ] adjust your approach based on incidents and defects?

Use `12-skills.md` as a guide for where to grow next.

---

### Connections to Other Files

- `02-objectives.md`, `03-workflow.md`, and `05-prd-structure-and-authoring.md` – core process and content behind these checklists.
- `07-non-functional-requirements.md`, `08-traceability-and-documentation.md`, and `24-governance-and-change-control.md` – deeper detail for NFRs, traceability, and governance.
- `25-templates.md` – templates that align with these checklists.

