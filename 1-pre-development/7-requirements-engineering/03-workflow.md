## 03 – Workflow: Step‑by‑Step Requirements Engineering

This file describes a **practical workflow** for going from roadmap items to detailed, testable requirements.

We break it into:

- A. High‑level stages
- B. Detailed steps
- C. Example cadences

---

### A. High‑Level Stages

1. **Prepare & Scope the Increment**
2. **Draft PRD & Requirement Outline**
3. **Detail Functional Requirements**
4. **Detail Non‑Functional Requirements (NFRs)**
5. **Refine into User Stories & Acceptance Criteria**
6. **Review, Align & Baseline (for this increment)**
7. **Maintain Traceability & Handle Changes**

This cycle repeats for:

- each release,
- each increment or program phase,
- and sometimes for major epics.

---

### B. Detailed Steps

#### Stage 1 – Prepare & Scope the Increment

**Goal:** decide what slice of the roadmap this requirements cycle will cover.

Inputs:

- product roadmap (`6-product-strategy-roadmap`),
- current objectives and KPIs,
- feasibility and capacity constraints.

Activities:

1. Select epics/features for the upcoming increment (e.g., quarter, PI).
2. Clarify:
   - target users/personas,
   - journeys and scenarios in scope,
   - important out‑of‑scope items (non‑goals).
3. Note:
   - known technical, risk, or operational constraints.

Output:

- **Scope brief** for this requirements cycle.

---

#### Stage 2 – Draft PRD & Requirement Outline

**Goal:** create a **skeleton PRD** and requirement list before diving into details.

Activities:

1. Create or update PRD shell (`05-prd-structure-and-authoring.md`):
   - context and goals,
   - personas and journeys,
   - initial list of high‑level functional areas,
   - placeholders for NFRs and dependencies.
2. List:
   - major functional capabilities (FR‑1, FR‑2, …),
   - initial guesses at NFR topics.

Output:

- PRD v0.x with **outline complete**, details to follow.

---

#### Stage 3 – Detail Functional Requirements

**Goal:** define the behaviour of the system in enough detail to be built and tested.

Activities:

1. For each key journey:
   - describe:
     - main flow,
     - key edge cases,
     - errors and fallbacks.
2. For each functional requirement:
   - add:
     - description,
     - inputs and outputs,
     - business rules,
     - data needs,
     - dependencies.
3. Collaborate with:
   - design (UX/service),
   - engineering,
   - operations and risk where relevant.

Output:

- PRD sections for functional requirements detailed enough to:
  - split into user stories,
  - estimate complexity.

---

#### Stage 4 – Detail Non‑Functional Requirements (NFRs)

**Goal:** capture and agree the **quality attributes** the solution must meet.

Activities (see `07-non-functional-requirements.md`):

1. Identify:
   - performance expectations (latency, throughput),
   - availability and recovery targets,
   - security and privacy needs,
   - logging, monitoring, and alerting requirements,
   - compliance and auditability needs.
2. For each NFR:
   - express it in measurable terms,
   - connect to:
     - existing standards or baselines,
     - or new targets.
3. Validate with:
   - architecture,
   - security/risk,
   - operations/SRE.

Output:

- NFR section of PRD,
- possibly separate NFR specification if needed.

---

#### Stage 5 – Refine into User Stories & Acceptance Criteria

**Goal:** turn requirements into **buildable units** with tests in mind.

Activities:

1. Break each functional area into user stories:
   - “As a \<persona>, I want \<capability>, so that \<benefit>.”
2. For each story, write acceptance criteria:
   - Given/When/Then style,
   - positive and negative paths,
   - NFR‑related checks where relevant.
3. Link:
   - stories to:
     - PRD sections,
     - epics/features in the roadmap,
     - test cases or test suites.

Tools:

- `Jira`, `Azure DevOps`, `Trello`, `Asana`, etc.

Output:

- a **backlog of well‑formed stories** ready for refinement and estimation.

---

#### Stage 6 – Review, Align & Baseline

**Goal:** ensure everyone **understands and accepts** the requirements for this increment.

Activities:

1. Run:
   - PRD walkthroughs with:
     - engineering,
     - QA/testing,
     - design,
     - risk/compliance and operations if needed.
2. Clarify:
   - questions and edge cases,
   - NFR interpretations.
3. Adjust:
   - scope (if necessary),
   - wording and details.
4. “Baseline” (for this increment):
   - agree that:
     - significant changes after this point:
       - go through lightweight change control (`24-governance-and-change-control.md`).

Output:

- shared understanding,
- a **baseline version** of requirements for the increment.

---

#### Stage 7 – Maintain Traceability & Handle Changes

**Goal:** keep requirements **in sync** with evolving reality.

Activities:

1. Track:
   - which stories and tests implement which requirements,
   - which requirements map to which objectives/risks.
2. When changes occur:
   - log:
     - why,
     - who requested/approved,
     - which requirements/stories/tests are affected.
3. Update:
   - PRDs and NFR docs,
   - user stories,
   - test plans.

This is especially important in:

- regulated environments,
- long‑running programs.

---

### C. Example Cadences

#### 1. Quarterly Increment (PI) for a Domain

- Weeks 1–2:
  - Scope definition and PRD outlining.
- Weeks 2–4:
  - Functional and NFR detailing,
  - story creation.
- Weeks 4–5:
  - cross‑team reviews,
  - baselining for the PI.

Execution:

- sprints run within the PI using these requirements as input,
- with controlled changes if needed.

#### 2. Continuous Delivery with Rolling Requirements

For teams doing continuous discovery/delivery:

- keep:
  - a living PRD or lightweight spec per major area,
  - always a few sprints ahead in detailing.
- update:
  - NFRs and traceability as work progresses.

Key is:

- staying:
  - at least 1–2 iterations ahead in requirements detail,
  - without over‑specifying far into the future.

---

### Connections to Other Files

- `02-objectives.md` – defines what this workflow must achieve.
- `05-prd-structure-and-authoring.md` – deep dive into PRD creation.
- `06-user-stories-and-acceptance-criteria.md` – details of Stage 5.
- `08-traceability-and-documentation.md` – techniques for Stage 7.
- `24-governance-and-change-control.md` – how reviews and changes are governed.

