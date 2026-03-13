## 11 – Roles and Positions in Problem Definition

This file explains **who is involved** in Problem Definition and how they collaborate.

We cover:

- A. Core roles
- B. Supporting roles
- C. Example team setups
- D. RACI-style overview

---

### A. Core Roles

#### 1. Product Manager (PM) / Product Owner

Responsibilities:

- Lead the **Problem Definition process** for a domain.
- Translate opportunities into **problem statements and scopes**.
- Facilitate workshops and reviews.
- Ensure outputs are:
  - documented,
  - linked to strategy,
  - handed over to downstream teams.

They are usually the **default owner** of problem documents.

---

#### 2. Business Owner / Sponsor

Titles:

- Business Head, Segment Owner, P&L Owner, Tribe Lead.

Responsibilities:

- Provide ** business context and goals**.
- Confirm **strategic importance** of the problem.
- Approve scope and **ambition level** (targets).

They are accountable for:

- making sure the problem, once solved, **contributes to business outcomes**.

---

### B. Supporting Roles

#### 1. UX / Researcher

Responsibilities:

- Provide **user perspective**:
  - interviews,
  - journey maps,
  - pain point identification.
- Challenge internal assumptions about user behavior.

Contribution:

- Ensures that problem statements reflect **real user experiences**, not just internal views.

---

#### 2. Engineering Lead / Architect

Responsibilities:

- Highlight **technical realities and constraints**.
- Explain:
  - system dependencies,
  - data availability,
  - legacy limitations.

Contribution:

- Prevents problems from being scoped or framed in ways that are **technically impossible or highly inefficient**.

---

#### 3. Operations / Process Owners

Responsibilities:

- Describe how processes **actually run today**:
  - manual steps,
  - hand‑offs,
  - bottlenecks.
- Provide insight into:
  - operational capacity,
  - typical failure modes.

Contribution:

- Helps ground the problem in **real processes and workload**.

---

#### 4. Risk / Compliance / Legal (Critical in Banking)

Responsibilities:

- Identify **regulatory and policy constraints**.
- Highlight:
  - where problems create **risk exposure**,
  - where solving them could **reduce risk**.

Contribution:

- Ensures problem statements **respect non‑negotiable constraints**.
- Surfaces **regulation‑driven urgency**.

---

#### 5. Data Analyst / BI Specialist

Responsibilities:

- Pull and interpret **metrics and reports** relevant to the problem.
- Help establish:
  - baselines,
  - segmentation,
  - correlations.

Contribution:

- Turns vague statements (“it’s slow”) into **measured realities** (“P95 is 3 days, target is 2 hours”).

---

### C. Example Team Setups

#### 1. Small Team / Startup

- PM:
  - leads problem definition and writes documents.
- Engineer / Tech Lead:
  - provides data access and technical constraints.
- Designer / UX:
  - talks to users, maps journeys.

Others (ops, support) are brought into:

- short, focused sessions.

---

#### 2. Product Team in Mid-Size Org

Cross‑functional problem‑definition squad:

- 1 Product Manager (lead),
- 1 UX/Researcher,
- 1 Data Analyst (shared),
- 1 Engineering Lead,
- 1 Ops/Support representative,
- 1 Risk/Compliance contact (for regulated journeys).

They run a **timeboxed Problem Definition sprint** and present outputs to:

- Business Owner / Sponsor.

---

#### 3. Large Enterprise / Bank

Pattern:

- **Domain PM** leads Problem Definition for their area (e.g., SME onboarding).
- **Business Sponsor** (Head of SME) owns strategic outcome.
- **Shared services** (research, data, risk, ops) support multiple domains.

There may be:

- formal **sign‑off steps** with:
  - risk committees,
  - architecture boards,
  - portfolio councils.

---

### D. RACI-Style Overview (Simplified)

RACI = Responsible, Accountable, Consulted, Informed.

| Activity                                      | PM | Business Sponsor | UX/Research | Eng Lead | Ops/Process | Risk/Compliance | Data/BI |
|-----------------------------------------------|----|------------------|-------------|----------|-------------|-----------------|--------|
| Define Problem Definition scope & goals       | R  | A                | C           | C        | C           | C               | C      |
| Collect stakeholder perspectives              | R  | C                | C           | C        | C           | C               | C      |
| Map current state & processes                 | R  | C                | C           | C        | R           | C               | C      |
| Pull and analyze metrics                      | C  | C                | C           | C        | C           | C               | R      |
| Draft problem statement & scope               | R  | C                | C           | C        | C           | C               | C      |
| Validate with users                           | C  | C                | R           | C        | C           | C               | C      |
| Document constraints & assumptions            | R  | C                | C           | C        | C           | R               | C      |
| Finalize and approve Problem Definition       | R  | A                | C           | C        | C           | C (or A in some orgs) | C |

- **R** – Responsible (does the work),
- **A** – Accountable (owns the decision),
- **C** – Consulted (gives input).

Adapt this table for your organization’s specifics.

---

### Connections to Other Files

- `12-skills.md` – capabilities these roles need to perform well.
- `03-workflow.md` – activities each role participates in.
- `18-case-studies.md` – shows these roles in action in concrete scenarios.

