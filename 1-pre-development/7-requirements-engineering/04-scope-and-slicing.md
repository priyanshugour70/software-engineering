## 04 – Scope & Slicing of Requirements

This file explains **how to define scope** for a release/increment and **slice requirements** into meaningful, deliverable chunks.

---

### 1. Why Scope & Slicing Matter

Without good scoping and slicing:

- increments:
  - become too big and vague,
  - contain half‑finished features,
  - don’t deliver usable value.
- teams:
  - struggle to estimate and plan,
  - frequently re‑negotiate and cut “at the end.”

Good scope and slicing:

- align **roadmap intentions** with **releasable increments**,
- ensure each slice:
  - is meaningful to users or stakeholders,
  - is buildable and testable.

---

### 2. Defining Scope for a Release / Increment

Start from:

- product roadmap and themes (`6-product-strategy-roadmap`),
- objectives/OKRs for the period,
- capacity and constraints (technical, regulatory, operational).

Ask:

- Which epics/features:
  - best move our objectives this period?
  - are feasible given dependencies and capacity?
  - are required by external deadlines (e.g., regulation)?

Document scope in a simple way:

- **In scope**:
  - list epics/features (and their main journeys/personas).
- **Out of scope / Non‑goals**:
  - list items that **look close** but are explicitly not part of this increment.

Example (digital SME lending increment):

- In scope:
  - new digital application flow for existing SME customers in Country A,
  - basic self‑service tracking of application status.
- Out of scope:
  - new products (e.g., SME cards),
  - international SME onboarding.

---

### 3. Principles of Good Slicing

When breaking scope into slices:

- **Value‑oriented**:
  - each slice should deliver something meaningful:
    - to a user,
    - or to a stakeholder (e.g., risk, operations).
- **Thin vertical slices**:
  - go end‑to‑end through:
    - UI (if needed),
    - backend,
    - data,
    - ops,
  - rather than large, isolated technical layers.
- **Testable**:
  - slice should be verifiable with:
    - clear acceptance criteria,
    - tests or monitoring.
- **Negotiable**:
  - not all details fixed up front;
  - scope can be refined as we learn, within guardrails.

---

### 4. Common Slicing Patterns

#### 4.1 By Persona or Segment

- Start with:
  - one persona or segment,
  - then expand.

Example:

- first increment:
  - existing SME customers with simple credit needs,
- later increments:
  - new SMEs,
  - more complex products,
  - additional geographies.

#### 4.2 By Journey Stage

- Slice by stages:
  - awareness → application → decision → disbursement → servicing.

Example:

- first increment:
  - focus on “application and decision”,
- later:
  - onboarding and servicing flows.

#### 4.3 By Risk / Complexity Levels

- Start with:
  - low‑risk, simpler flows,
  - then handle complex or high‑risk use cases.

Example:

- first increment:
  - small, unsecured loans,
- later:
  - larger loans,
  - secured loans,
  - exceptions and manual overrides.

#### 4.4 By Channel or Integration Depth

- Start:
  - with a single channel (e.g., web),
  - with minimal integration depth.
- Later:
  - add mobile, branch, APIs,
  - deeper integration with core banking and third parties.

---

### 5. From Scope to Requirements Slices

Once high‑level slices are decided:

1. For each slice:
   - identify:
     - key user journeys,
     - scenarios,
     - edge cases in scope.
2. Write:
   - functional requirements:
     - focusing on this slice only,
   - NFRs:
     - that must already hold for this slice (e.g., minimal performance, security basics).
3. Split into stories:
   - each story:
     - belongs to a slice,
     - has clear acceptance criteria.

This ensures:

- that even early increments:
  - are coherent and usable,
  - and are not just random backend tasks.

---

### 6. Anti‑Patterns in Scoping & Slicing

Common mistakes:

- **Scope creep**:
  - increment starts small,
  - but more and more subtle use cases are added,
  - without removing anything.
- **Horizontal slices only**:
  - big chunk of backend work with no user‑visible change for months.
- **“All or nothing” increments**:
  - requirement: “digital SME lending for all segments, all products, all countries” in one go.

Mitigations:

- maintain:
  - explicit in‑scope and out‑of‑scope lists,
  - change control for scope expansion.
- favour:
  - vertical slices with clear value,
  - smaller MVPs and follow‑on improvements.

---

### 7. Beginner Checklist

- [ ] Do we have:
  - [ ] a clear statement of scope for this release/increment?
  - [ ] an explicit list of non‑goals?
- [ ] Are slices:
  - [ ] meaningful to users or stakeholders?
  - [ ] testable end‑to‑end?
  - [ ] feasible given dependencies and capacity?
- [ ] Have we avoided:
  - [ ] “all or nothing” mega‑increments?
  - [ ] purely horizontal technical slices with no value story?

If several answers are “no,” revisit scope and slicing before going deeper into detailed requirements.

---

### Connections to Other Files

- `03-workflow.md` – this file expands on Stage 1 (scope) and connects to later stages.
- `05-prd-structure-and-authoring.md` – where scope and slices appear in PRDs.
- `06-user-stories-and-acceptance-criteria.md` – slicing down to story level.
- `6-product-strategy-roadmap/07-roadmap-levels-and-views.md` – how roadmap levels influence scope for each increment.

