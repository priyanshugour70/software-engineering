## 04 – Workflow: Step‑by‑Step RFC Process

This file describes a **practical workflow** for creating, reviewing, and managing RFCs.

We break it into:

- A. High‑level stages
- B. Detailed steps
- C. Example cadences

---

### A. High‑Level Stages

1. **Trigger & Scoping**
2. **Drafting the RFC**
3. **Review & Discussion**
4. **Decision & Sign‑Off**
5. **Post‑Decision Linking & Updates**

This cycle may repeat for:

- large programs (multiple RFCs),
- and for major revisions (superseding older RFCs).

---

### B. Detailed Steps

#### Stage 1 – Trigger & Scoping

**Goal:** decide **whether** an RFC is needed and what it should cover.

Inputs:

- roadmap and requirements,
- feasibility and risk findings,
- architecture and platform context.

Activities:

1. Identify trigger:
   - new initiative / major feature,
   - platform change or replacement,
   - regulatory or security‑driven change.
2. Check against criteria (`03-when-to-use-an-rfc.md`):
   - impact,
   - risk,
   - cross‑team involvement.
3. Define RFC scope:
   - which systems and teams are affected,
   - what decisions the RFC must lead to,
   - rough timeline and stakeholders.

Output:

- short **RFC proposal/outline**:
  - working title,
  - sponsor,
  - expected reviewers,
  - scope bullets.

---

#### Stage 2 – Drafting the RFC

**Goal:** create a **first complete draft** of the RFC document.

Activities:

1. Fill out metadata:
   - RFC ID, author(s), status, related documents.
2. Write context & problem:
   - summarize business and technical drivers,
   - describe current state and limitations.
3. Define goals and non‑goals:
   - what this proposal addresses and does not.
4. Propose solution(s):
   - high‑level architecture,
   - key components and interactions,
   - data flows, integration points.
5. Capture alternatives:
   - at least one serious alternative,
   - pros, cons, and implications.
6. Add:
   - security, compliance, and operational sections,
   - known risks and open questions.

Output:

- **RFC draft v0.x**:
  - enough detail for meaningful review,
  - but still open to change.

---

#### Stage 3 – Review & Discussion

**Goal:** gather feedback, surface risks, and refine the proposal.

Activities:

1. Share RFC with:
   - architecture group,
   - engineering leads,
   - product leads,
   - security & risk,
   - operations/SRE (as relevant).
2. Allow time for asynchronous comments:
   - inline comments in docs,
   - or review tools / pull requests.
3. Run one or more review meetings if needed:
   - walk through context, options, and proposed solution,
   - discuss concerns, questions, and suggestions.
4. Refine:
   - clarify text,
   - update diagrams,
   - adjust solutions or options based on feedback.

Output:

- updated RFC draft(s),
- clear list of unresolved points (if any).

---

#### Stage 4 – Decision & Sign‑Off

**Goal:** converge on a **clear decision** with visible approvals.

Activities:

1. Summarize recommendation:
   - chosen option,
   - rationale,
   - major trade‑offs accepted.
2. Present for decision:
   - to:
     - architecture board,
     - design authority,
     - or equivalent forum.
3. Capture:
   - decision outcome:
     - Accepted,
     - Accepted with conditions,
     - Rejected,
     - Superseded,
   - names/roles of approvers,
   - dates.
4. Communicate:
   - decision and impacts to all stakeholders,
   - including delivery teams and risk/ops.

Output:

- RFC in **non‑draft status** (e.g., Accepted/Rejected),
- decisions and conditions clearly recorded.

---

#### Stage 5 – Post‑Decision Linking & Updates

**Goal:** connect the RFC to downstream work and keep it relevant.

Activities:

1. Link RFC to:
   - architecture design documents,
   - epics and stories in the backlog,
   - security/compliance tasks,
   - runbooks and operational artifacts (where relevant).
2. For major changes in direction:
   - either:
     - update the RFC (noting the change and date),
     - or create a new RFC that **supersedes** the old one.
3. Use RFCs as reference in:
   - future related RFCs,
   - audits,
   - incident post‑mortems.

Output:

- RFC as a **living reference**, not a one‑off file no one returns to.

---

### C. Example Cadences

#### 1. RFC for a New Platform Component

- Week 1:
  - trigger & scoping,
  - draft v0.1.
+- Weeks 2–3:
  - iterative reviews,
  - architecture and security input.
- Week 4:
  - decision meeting,
  - adjustments,
  - final acceptance with conditions.

#### 2. RFC for a Regulatory‑Driven Change

- Early:
  - involve risk/compliance to interpret regulation,
  - ensure RFC captures required controls and evidence.
- Multiple forums:
  - architecture,
  - risk,
  - sometimes legal.
- Timeline:
  - oriented around regulatory deadline,
  - with enough buffer for review and re‑work.

---

### Connections to Other Files

- `02-objectives.md` – defines what this workflow is trying to achieve.
- `05-rfc-structure-and-authoring.md` – content you fill in during Stage 2.
- `24-governance-review-and-lifecycle.md` – governance structures for review and decisions.
- `26-checklists.md` – quick checks to use at each stage.

