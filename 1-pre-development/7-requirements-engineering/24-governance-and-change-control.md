## 24 – Governance & Change Control for Requirements

This file explains how to **govern and manage changes** to requirements over time.

It focuses on:

- decision‑making forums,
- baselining and change control,
- balancing agility with risk management.

---

### 1. Why Governance & Change Control Matter

Requirements **will** change as:

- we learn from discovery,
- constraints and capacity shift,
- regulations and markets evolve.

Without governance:

- changes:
  - happen informally,
  - are poorly communicated,
  - create confusion and rework.

With good governance:

- changes:
  - are visible,
  - reasoned,
  - documented,
  - and aligned with risk appetite.

---

### 2. Baselining Requirements for an Increment

Baselining means:

- agreeing that:
  - “for this release/increment, this is our reference set of requirements.”

Steps:

1. At the end of the requirements cycle for an increment:
   - PRD and NFR docs:
     - marked as “Baseline for Release X / Increment Y.”
   - story backlog:
     - aligned with baseline requirements.
2. Communicate:
   - what is in baseline and any known open questions.

Why:

- gives teams a **stable target** for planning and execution,
- while still allowing controlled changes.

---

### 3. Types of Requirement Changes

Common change types:

1. **Clarifications**  
   - wording improvements, no behaviour change.
2. **Minor Changes**  
   - small scope adjustments with limited impact.
3. **Major Changes**  
   - significant scope or behaviour change,
   - impact on timelines, risk, or regulatory commitments.

Governance should:

- treat these differently in terms of:
  - review,
  - approval,
  - communication.

---

### 4. Change Control Process (Lightweight)

For a given increment:

1. **Identify change**:
   - which requirement/story/test is affected,
   - why the change is needed.
2. **Assess impact**:
   - on:
     - scope,
     - capacity,
     - timelines,
     - risk/compliance.
3. **Decide**:
   - who must be involved?
   - is it:
     - a PM/PO + tech lead decision (minor),
     - or needs involvement of business owners, risk, etc. (major)?
4. **Update artifacts**:
   - PRDs, NFRs, stories, tests,
   - traceability tables.
5. **Communicate**:
   - summarize:
     - what changed,
     - why,
     - impact on expectations.

Use:

- decision logs (`10-documents-and-artifacts.md`, `25-templates.md`) to record major changes.

---

### 5. Governance Forums

Depending on scale and risk, you may use:

- **Squad/Team Ceremonies**:
  - refinements, sprint planning,
  - handle clarifications and many minor changes.
- **Product/Domain Review Forums**:
  - handle:
    - bigger scope changes,
    - reprioritisation,
    - cross‑team impacts.
- **Risk/Compliance Governance Forums**:
  - review:
    - regulatory or high‑risk requirement changes.

The key:

- not the number of forums,
- but **clear understanding** of:
  - which changes go where,
  - who must be involved.

---

### 6. Integrating with Portfolio & Roadmap Governance

Changes to requirements often:

- imply changes to:
  - roadmap timing,
  - initiative scope,
  - capacity allocation.

Link:

- requirement change control with:
  - quarterly roadmap and portfolio reviews (`6-product-strategy-roadmap/24-governance-alignment-and-cadence.md`).

Example:

- if major regulatory requirements appear mid‑increment:
  - they may:
    - force reprioritisation,
    - move other work out of scope.
- governance should:
  - make these trade‑offs explicit and approved.

---

### 7. Beginner Checklist

- [ ] Do we:
  - [ ] baseline requirements for each release/increment?
  - [ ] distinguish between clarifications, minor, and major changes?
  - [ ] have a simple process to propose, assess, and approve changes?
- [ ] Are:
  - [ ] major changes documented in a decision log?
  - [ ] impacts communicated to affected teams and stakeholders?
- [ ] Are:
  - [ ] risk/compliance involved for changes that affect regulations or controls?

If not, start by:

- agreeing a lightweight change classification and recording major decisions.

---

### Connections to Other Files

- `03-workflow.md` – where baselining fits in the requirements process.
- `08-traceability-and-documentation.md` – updating links when changes occur.
- `22-best-practices.md` and `23-common-mistakes.md` – governance as a tool to reinforce good practices and avoid anti‑patterns.

