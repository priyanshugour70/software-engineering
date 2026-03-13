## 18 – Collaboration with Design & Architecture

This file explains how Requirements Engineering **interacts with UX/Service Design and Architecture**.

Good collaboration here:

- avoids rework,
- improves user experience,
- and ensures technical feasibility.

---

### 1. Why Collaboration Matters

Requirements, design, and architecture are:

- different views of the **same problem and solution**:
  - requirements:
    - what needs to happen,
  - design:
    - how users experience it,
  - architecture:
    - how systems and data implement it.

If they are done in silos:

- designs may not reflect real constraints,
- architecture may not support user flows,
- requirements may be unrealistic or incomplete.

---

### 2. Working with UX / UI / Service Design

#### 2.1 Early Joint Exploration

Good practice:

- bring designers into:
  - scope and PRD outlining,
  - journey and persona discussions.

Designers help to:

- visualize:
  - current and future journeys,
  - pain points,
  - edge cases.
- reveal:
  - missing requirements,
  - hidden complexity.

#### 2.2 Co‑evolving Requirements and Designs

Rather than:

- writing all requirements first and handing them “over to design,”

prefer:

- iterative collaboration:
  - draft requirements,
  - draft flows and wireframes,
  - refine both together.

Example:

- a single functional requirement may:
  - lead to multiple design options,
  - which reveal:
    - extra states,
    - errors,
    - or NFR implications,
  - that refine requirements further.

#### 2.3 Documenting the Right Level of Design in PRDs

PRDs should:

- link to:
  - wireframes,
  - prototypes,
  - design system components,
  - not duplicate them.

But PRDs can:

- include:
  - key acceptance criteria related to UX,
  - important content rules and messages.

---

### 3. Working with Architecture

#### 3.1 Feasibility & Options

Architecture partners:

- assess:
  - feasibility of proposed behaviours and NFRs,
  - different implementation options.

Patterns:

- early architecture involvement helps:
  - adjust requirements and NFRs,
  - split work into meaningful slices,
  - identify dependencies and enablers.

#### 3.2 NFRs & Platform Alignment

Architects work with:

- tech leads,
- security,
- operations,

to ensure:

- NFRs are:
  - realistic,
  - aligned with platform capabilities,
  - not in conflict with other systems.

They may propose:

- shared NFR baselines,
- platform enhancements that serve multiple products.

#### 3.3 Updating Requirements from Architecture Decisions

Architecture decisions:

- can change:
  - how requirements are implemented,
  - sometimes the requirements themselves.

Keep requirements:

- updated when:
  - architecture changes affect behaviour or qualities (e.g., latency, failure modes).

Use:

- architecture decision records (ADRs),
- and link them to PRD/NFR sections where relevant.

---

### 4. Collaboration Rituals

Examples of collaboration rituals:

- **Joint Discovery / Inception Workshops**:
  - bring product, BA, design, architecture together at the start of an initiative.
- **Design–Requirements Reviews**:
  - review UX flows against PRD requirements,
  - refine both.
- **Architecture–Requirements Alignment Sessions**:
  - check NFRs and dependencies,
  - align slices with system design.

These can:

- be part of:
  - existing sprint planning,
  - refinement meetings,
  - or separate workshops for large initiatives.

---

### 5. Beginner Checklist

- [ ] Are designers:
  - [ ] involved early in defining requirements?
  - [ ] helping uncover edge cases and usability NFRs?
- [ ] Are architects:
  - [ ] reviewing NFRs and major functional requirements?
  - [ ] providing input on dependencies and enablers?
- [ ] Do you have:
  - [ ] at least one regular forum where product/BA, design, and architecture discuss requirements together?

If not, start by inviting design and architecture to PRD reviews and key refinement sessions.

---

### Connections to Other Files

- `11-roles-and-positions.md` – roles of designers and architects.
- `05-prd-structure-and-authoring.md` – where links to design and architecture go in PRDs.
- `07-non-functional-requirements.md` – architecture’s major role in NFRs.
- `19-collaboration-with-testing-and-qa.md` – complementary collaboration with QA/testing.

