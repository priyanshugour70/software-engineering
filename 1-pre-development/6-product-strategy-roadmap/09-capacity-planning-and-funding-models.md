## 09 – Capacity Planning & Funding Models

This file explains how **people capacity** and **funding models** interact with product strategy and roadmaps.

It is especially relevant in enterprises/banks where:

- budgets are annual,
- teams are shared across products,
- and regulatory work competes with growth initiatives.

---

### 1. Basic Concepts (Beginner Friendly)

**Capacity planning**:

- estimating how much **work** teams can realistically deliver over:
  - a quarter,
  - a year,
  - or program horizon.

**Funding models**:

- how you decide:
  - **which teams or initiatives** get money and people,
  - for how long,
  - under which constraints.

Strategy and roadmaps:

- are only realistic if they match:
  - available **capacity**,
  - and the **funding model**.

---

### 2. Common Funding Models

#### 2.1 Project‑Based Funding

Characteristics:

- money is allocated to **projects**:
  - fixed scope,
  - fixed time,
  - fixed budget.
- teams may:
  - assemble for the project,
  - disband afterwards.

Pros:

- simple for **short, well‑bounded efforts**,
- familiar to traditional PMO/finance.

Cons:

- encourages:
  - “big upfront scope” thinking,
  - frequent team re‑shuffling,
  - technical debt (teams rush to “finish” project).

Impact on roadmaps:

- roadmaps often become:
  - lists of projects,
  - less focus on ongoing product outcomes.

#### 2.2 Product / Value‑Stream Funding

Characteristics:

- money is allocated to **persistent teams**:
  - aligned to products,
  - journeys,
  - or value streams.
- teams:
  - own outcomes over time,
  - take on changing initiatives and epics in their area.

Pros:

- stable teams,
- easier continuous improvement,
- better alignment with **product strategy**.

Cons:

- requires:
  - clear product/value‑stream boundaries,
  - change in how finance and governance think.

Impact on roadmaps:

- roadmaps:
  - become **flow of initiatives** through persistent teams,
  - rather than one‑off projects.

---

### 3. Translating Strategy into Capacity Needs

When you define strategy and themes (`04`–`05` files), you should ask:

- How many teams do we need per theme or area?
- What skills and seniority levels are required?
- What non‑feature work (platform, risk, operations) must be covered?

Practical steps:

1. Start from **current teams**:
   - list each team/squad,
   - their focus,
   - and average throughput (e.g., epics or story points per quarter).
2. Map teams to:
   - products,
   - platforms,
   - and themes.
3. Compare with:
   - target initiatives in the roadmap,
   - regulatory obligations,
   - and known tech debt.

Result:

- you see **gaps**:
  - where ambitions exceed realistic capacity,
  - where some areas are overstaffed or understaffed.

---

### 4. Capacity Allocation Patterns

A simple way to reason about allocation:

- decide **percentage bands** for:
  - growth / new features,
  - risk & compliance,
  - platform & tech debt,
  - experiments / innovation.

Example for a product with one squad:

- 50% – Growth & customer experience,
- 25% – Risk & compliance,
- 20% – Platform, performance, debt,
- 5%  – Experiments.

On a larger portfolio:

- you may allocate, for example:
  - 40% of all SME portfolio capacity to risk & compliance for a year,
  - due to heavy regulatory change.

These allocations should be:

- **visible in roadmaps**:
  - separate swimlanes,
  - color coding,
  - or tagging in tools like `Jira` or `Aha!`.

---

### 5. Dealing with Over‑Commitment

Common pattern:

- roadmap lists more initiatives than teams can realistically deliver,
- everything looks “top priority.”

Signs:

- frequent re‑prioritization,
- many initiatives partially done,
- teams constantly context‑switching.

Mitigations:

- use **capacity‑constrained planning**:
  - for each team, limit:
    - number of concurrent epics,
    - total effort per quarter.
- make **trade‑offs explicit**:
  - “If we add initiative X this quarter, we must delay initiative Y.”
- keep a **“parking lot”** of good ideas:
  - not rejected,
  - but clearly marked as “not in this horizon.”

---

### 6. Working with Finance & PMO

In enterprises/banks, finance and PMO care about:

- budgets vs spend,
- risk and compliance obligations,
- alignment with corporate strategy.

To make product strategy & roadmap credible:

- treat finance as a **partner**:
  - share themes and roadmaps,
  - explain outcome goals and capacity needs.
- reconcile:
  - product language (epics, capacity),
  - with finance language (budgets, cost centers).

Useful tools:

- simple mapping tables:
  - initiatives / epics → cost centers / projects.
- portfolio dashboards:
  - show:
    - spend vs value/metrics,
    - risk reduction progress.

---

### 7. Example – SME Lending Capacity Conversation

Scenario:

- Strategy says:
  - we must:
    - build digital journey v2,
    - modernize risk engine,
    - improve operations tooling,
    - comply with new regulation.
- We have:
  - 3 product squads,
  - 1 risk platform squad,
  - 1 data squad.

Discussion outcomes:

- Year 1:
  - risk & compliance and digital experience prioritized,
  - operations tooling pushed to Year 2 (with some minimal improvements),
  - additional contractor budget approved for regulation work.
- Roadmap updated:
  - operations improvements marked as:
    - “later,”
    - or split into smaller slices that fit capacity.

This is **normal**:

- strategy and roadmap are **negotiated** with capacity and funding.

---

### 8. Beginner Checklist

- [ ] Do we know:
  - [ ] how many squads/teams we have?
  - [ ] what their focus areas are?
  - [ ] their approximate throughput per quarter?
- [ ] Do we have:
  - [ ] an explicit capacity allocation (e.g., growth vs risk vs platform)?
  - [ ] shared understanding with finance/PMO?
- [ ] Does the roadmap:
  - [ ] avoid over‑committing beyond capacity?
  - [ ] show clearly what is **not** being done in this horizon?

If many answers are “no,” then strategy and roadmap are **not capacity‑aware** yet.

---

### Connections to Other Files

- `03-workflow.md` – where capacity alignment fits in the strategy & roadmap process.
- `05-strategic-themes-goals-and-okrs.md` – how themes influence capacity splits.
- `06-prioritization-frameworks.md` – how to decide what fits into limited capacity.
- `08-portfolio-and-theme-management.md` – how capacity is viewed at portfolio level.
- `24-governance-alignment-and-cadence.md` – how funding and capacity changes are reviewed over time.

