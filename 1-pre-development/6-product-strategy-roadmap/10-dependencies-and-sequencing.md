## 10 – Dependencies & Sequencing

This file explains **how to identify and manage dependencies** between initiatives and epics, and how to **sequence** work in the roadmap.

Dependencies and sequencing are critical in:

- complex enterprises,
- regulated products,
- and environments with shared platforms.

---

### 1. What Are Dependencies?

A **dependency** exists when:

- one piece of work **cannot be completed or deliver value** until:
  - another piece of work is done,
  - or a shared component/decision is available.

Examples:

- A new SME digital lending journey depends on:
  - a risk engine feature,
  - KYC platform enhancements,
  - data integration with core banking.

Dependencies can be:

- **technical** (APIs, platforms),
- **process/operational** (new processes, training),
- **regulatory/legal** (approval, policy changes),
- **organizational** (new team or role).

---

### 2. Why Dependencies Matter for the Roadmap

If you ignore dependencies:

- teams:
  - build features that cannot go live,
  - wait idle for other teams,
  - rework solutions due to late changes.

Roadmaps become:

- **unrealistic**,
- misleading for stakeholders,
- and frustrating for teams.

Good dependency management:

- allows:
  - realistic sequencing,
  - risk identification,
  - targeted coordination.

---

### 3. Identifying Dependencies (Step by Step)

During initiative and epic shaping (`03-workflow.md`):

1. For each initiative/epic, ask:
   - “What must be true **before** this can deliver value?”
   - “Who else is impacted or needs to change?”
2. Look at:
   - systems and platforms involved (architecture diagrams),
   - processes and operations,
   - compliance and risk policies.
3. Capture:
   - dependencies explicitly in your tooling:
     - `Jira` issue links (e.g., “blocked by,” “relates to”),
     - `Aha!` or `Productboard` dependency fields,
     - visual diagram in `Miro`, `Lucidchart`, or `Mural`.

Outcome:

- each initiative/epic has a **dependency list** with:
  - owning team,
  - type (technical, process, regulatory, etc.),
  - criticality.

---

### 4. Sequencing – Turning Dependencies into a Plan

Once dependencies are known:

1. Order major initiatives:
   - place enabling platform or risk work **earlier**,
   - sequence customer‑facing features accordingly.
2. Break big initiatives into slices:
   - e.g., MVP vs later enhancements,
   - to reduce dependency depth.
3. Use:
   - simple dependency diagrams,
   - or program boards (in scaled agile).

Principles:

- avoid **long chains** of dependencies if possible,
- group work to reduce context switching,
- leave **buffer** for integration and unforeseen issues.

---

### 5. Example – SME Lending Dependency Chain

Goal:

- launch digital SME lending journey with:
  - instant eligibility check,
  - configurable risk rules,
  - automated document collection.

Possible dependency structure:

1. **Risk Engine Enhancements** (Platform team)
   - add new scoring features,
   - expose configuration UI.
2. **KYC / Onboarding Platform** (Onboarding team)
   - support new document types and flows.
3. **Data Platform Work** (Data team)
   - pipeline to unify SME financial data.
4. **Digital Journey v2** (Product team)
   - UX redesign,
   - integration with risk and onboarding,
   - self‑service management portal.
5. **Operations Workbench** (Ops team)
   - tools to handle exceptions and manual reviews.

Sequencing:

- Risk & data platform work starts early (foundations).
- Digital journey v2:
  - begins with UX and partial integration,
  - progressively integrates new engine and data.
- Operations tools follow:
  - in parallel when platform capabilities stabilize.

---

### 6. Visualizing Dependencies

Common techniques:

- **Program boards**:
  - grid with teams vs iterations,
  - lines showing dependencies between work items.
- **Swimlane roadmaps with arrows**:
  - e.g., platform lane → product lane.
- **Simple dependency maps** in `Miro` or `FigJam`:
  - boxes for initiatives,
  - arrows showing “enables” or “depends on.”

Key is:

- making dependencies **visible and discussable**, not hidden in people’s heads.

---

### 7. Managing Risk from Dependencies

Dependencies introduce:

- schedule risk,
- integration risk,
- quality risk.

Mitigations:

- **early spikes / proof‑of‑concepts**:
  - test integration approaches early.
- **interim slices**:
  - launch a simpler version not relying on all dependencies.
- **clear owners**:
  - each dependency must have:
    - a name,
    - a team,
    - and a target window.
- **regular cross‑team check‑ins**:
  - e.g., weekly or bi‑weekly syncs to review:
    - inter‑team dependencies,
    - blockers,
    - adjustments.

---

### 8. Special Case – Regulatory and Policy Dependencies

In regulated environments:

- changes may depend on:
  - policy approvals,
  - risk committee decisions,
  - regulator feedback.

Patterns:

- create:
  - explicit “risk/compliance” epics,
  - with clear milestones (e.g., policy approved by X date).
- reflect these in the roadmap:
  - as milestones,
  - or separate swimlanes.
- involve:
  - risk/compliance partners early in:
    - strategy,
    - design,
    - testing.

---

### 9. Beginner Checklist

- [ ] For each initiative/epic:
  - [ ] have we listed key dependencies?
  - [ ] do we know which team owns each dependency?
  - [ ] do we know by when we need each dependency?
- [ ] In the roadmap:
  - [ ] are enabling platform and risk/compliance items placed **before** dependent features?
  - [ ] are we avoiding long chains of dependencies where possible?
- [ ] Are dependencies:
  - [ ] visualized in tools (roadmap, program boards, diagrams)?
  - [ ] discussed regularly in cross‑team forums?

If many boxes are “no,” your roadmap is likely **too optimistic**.

---

### Connections to Other Files

- `03-workflow.md` – shows where dependency identification and sequencing fit.
- `07-roadmap-levels-and-views.md` – how dependencies appear across different roadmap views.
- `08-portfolio-and-theme-management.md` – managing dependencies in a portfolio context.
- `24-governance-alignment-and-cadence.md` – cross‑team forums and governance where dependencies are addressed.

