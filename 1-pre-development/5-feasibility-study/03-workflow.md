## 03 – Workflow: Step‑by‑Step Feasibility Study

This file describes a **practical workflow** to go from a funded idea to a **feasibility report and risk register**.

We cover:

- A. High‑level stages
- B. Detailed steps
- C. Example timelines

---

### A. High‑Level Stages

1. **Intake & Scoping**
2. **Baseline Understanding**
3. **Option Exploration**
4. **Deep‑Dive Feasibility Assessment**
5. **Risk Register & Recommendations**
6. **Review & Handover**

You may loop between 3 and 4 as you explore and narrow options.

---

### B. Detailed Steps

#### Stage 1 – Intake & Scoping

**Goal:** Align on **what** needs feasibility analysis and **how deep** to go.

Inputs:

- problem statements,
- business case summary,
- initial solution concept(s),
- constraints already known (e.g., regulatory deadlines).

Activities:

1. Clarify initiative scope:
   - domains and systems impacted,
   - segments/geographies/channels in play.
2. Identify feasibility questions:
   - What are the main unknowns?
   - Where are we most worried (tech/ops/security/legal)?
3. Agree on:
   - timebox,
   - participants,
   - expected outputs (depth, format).

Output:

- a **feasibility charter**:
  - scope, objectives, team, and timeline.

---

#### Stage 2 – Baseline Understanding

**Goal:** Understand current **architecture, operations, and constraints**.

Activities:

1. Architecture baseline:
   - review:
     - system diagrams,
     - data flows,
     - integration patterns,
     - platform standards.
2. Operational baseline:
   - map:
     - current processes and roles,
     - SLAs,
     - pain points.
3. Policy & risk baseline:
   - gather:
     - security policies,
     - regulatory rules,
     - prior audit and incident reports.

Output:

- a short **current‑state summary** for tech, ops, and controls.

---

#### Stage 3 – Option Exploration

**Goal:** Identify and outline **solution options** to evaluate.

Activities:

1. Brainstorm options with:
   - architects,
   - product,
   - platform teams.
2. Typical dimensions:
   - build vs buy vs partner,
   - reuse existing platforms vs new components,
   - scope and phasing variants.
3. For each option, sketch:
   - high‑level architecture,
   - main process changes,
   - obvious pros/cons.

Output:

- a shortlist of **feasible candidate options** to investigate in depth.

---

#### Stage 4 – Deep‑Dive Feasibility Assessment

**Goal:** Evaluate each shortlisted option across all feasibility dimensions.

Activities (see dedicated files 04–09):

1. **Technical feasibility**
   - complexity of integrations,
   - data availability and quality,
   - alignment with architecture standards,
   - scalability and resilience.
2. **Operational feasibility**
   - process changes,
   - new operational capabilities,
   - support and incident models,
   - impact on existing workloads.
3. **Security & privacy**
   - new attack surfaces,
   - data classification and flows,
   - control requirements.
4. **Legal & regulatory**
   - licensing and approvals,
   - compliance with laws and policies.
5. **Organizational feasibility**
   - skills and capacity,
   - change appetite,
   - dependencies on other programs.

For each option:

- capture:
  - feasibility rating,
  - key risks and mitigations,
  - constraints and required enablers.

Output:

- an **option comparison matrix** and detailed feasibility notes.

---

#### Stage 5 – Risk Register & Recommendations

**Goal:** Consolidate **risks, constraints, and recommendations**.

Activities:

1. Build or update the **risk register** (`22-risk-register-and-mitigation.md`):
   - risk description,
   - likelihood and impact,
   - owner,
   - mitigation strategy,
   - required decisions or enablers.
2. Summarize:
   - preferred solution option,
   - “non‑negotiable” constraints,
   - recommended phasing or scope adjustments.

Output:

- a **feasibility report** bundle:
  - summary,
  - option comparison,
  - risk register,
  - recommendations.

---

#### Stage 6 – Review & Handover

**Goal:** Align stakeholders and hand over into **architecture/design and delivery**.

Activities:

1. Run review sessions with:
   - product & business owners,
   - architecture board / design authority,
   - security & risk,
   - operations and support leaders.
2. Capture:
   - decisions on solution direction,
   - accepted risks and mitigations,
   - required follow‑up studies (if any).
3. Handover:
   - to:
     - architecture/design teams (for HLD/RFC),
     - delivery planning (for roadmap and team planning),
     - business/risk governance.

Output:

- agreed **solution direction and feasibility statement**,
- updated artefacts in architecture and delivery docs.

---

### C. Example Timelines

#### 1. Lightweight 1–2 Week Feasibility Check

Use when:

- scope is modest,
- technology and domain are familiar,
- risk is low.

Outline:

- Days 1–2:
  - intake, scoping, baseline review.
- Days 3–5:
  - rapid option exploration,
  - quick assessment with:
    - architecture,
    - ops,
    - security.
- Days 6–8:
  - summarize risks and constraints,
  - recommend direction,
  - brief governance touchpoints.

---

#### 2. Full 4–6 Week Feasibility Study (Enterprise / Bank)

Use when:

- initiative is large,
- touches critical systems,
- has significant regulatory or security impact.

Outline:

- Weeks 1–2:
  - intake and baseline,
  - gather current‑state info,
  - initial option set.
- Weeks 3–4:
  - deep‑dive feasibility per dimension,
  - workshops with:
    - security,
    - risk,
    - legal,
    - ops,
    - platform.
- Weeks 5–6:
  - consolidate findings,
  - build risk register and feasibility report,
  - review cycles with governance bodies.

---

### Connections to Other Files

- `02-objectives.md` – defines the outcomes this workflow must achieve.
- `04-feasibility-dimensions.md` – structure for assessments in Stage 4.
- `22-risk-register-and-mitigation.md` – outputs for Stage 5.
- `26-checklists.md` – lightweight checks to use at each stage.

