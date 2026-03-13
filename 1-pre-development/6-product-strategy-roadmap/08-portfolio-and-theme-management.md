## 08 – Portfolio & Theme Management

This file explains how to manage:

- **multiple products and platforms** as a portfolio, and
- keep **strategic themes** consistent across them.

This is especially important in enterprises/banks where:

- many teams touch the same customer journey,
- but belong to different departments.

---

### 1. What Is a Product Portfolio?

In this context, a **portfolio** is:

- a group of related:
  - products,
  - platforms,
  - and capabilities,
- that together deliver value to:
  - a segment (e.g., SMEs),
  - or a journey (e.g., lending).

Examples:

- SME portfolio might include:
  - SME lending product,
  - SME current accounts,
  - risk engine platform,
  - onboarding KYC platform,
  - servicing and collections tools.

Portfolio management focuses on:

- **where to invest** across products and platforms,
- **how much capacity** each area receives,
- **alignment** with company strategy.

---

### 2. Managing Themes Across the Portfolio

Strategic themes (from `05-strategic-themes-goals-and-okrs.md`) often:

- apply across many products and platforms.

Example themes:

- “Frictionless Digital Experience”
- “Configurable Risk & Compliance”
- “Operational Excellence & Automation”

Each theme might require:

- front‑end work (product),
- back‑end/platform work,
- operations and process changes,
- data and analytics improvements.

Portfolio & theme management means:

- maintaining visibility of:
  - **all** initiatives under a theme,
  - across different teams and systems.

---

### 3. Theme‑Based Portfolio Views

Useful views (in tools like `Aha!`, `Productboard`, `airfocus`, `Jira Align`, or even `Excel`/`Sheets`):

- **Theme → Initiatives → Products/Platforms**
  - For each theme:
    - list initiatives,
    - show which product/platform owns them,
    - indicate value, risk, and timing.
- **Theme Investment Chart**
  - show how much:
    - capacity,
    - or budget,
  - goes to each theme.

Benefits:

- you can quickly answer:
  - “How much are we investing in risk vs growth vs operations?”
  - “Which themes are underfunded?”

---

### 4. Capacity Allocation by Theme

In large organizations, you rarely have:

- the luxury to “fund everything.”

Instead, you:

- allocate capacity (people, budget) by theme, such as:
  - 40% Growth / Experience,
  - 30% Risk & Compliance,
  - 20% Platform & Scalability,
  - 10% Experiments / Innovation.

This can be:

- at **portfolio level** (for the whole SME domain),
- and then refined for each **product or platform**.

Key is:

- to be **explicit** about trade‑offs.

Example:

- If regulatory pressure is high, you may temporarily change:
  - Risk & Compliance → 40–50%,
  - Growth investments decrease.

---

### 5. Portfolio Kanban and Health Checks

Portfolio Kanban:

- visualize initiatives in states:
  - Idea / Discovery,
  - Prioritized / Approved,
  - In Progress,
  - Done,
  - On Hold.

This helps:

- avoid starting too many things at once,
- track **flow and bottlenecks**.

Portfolio health checks:

- periodic reviews (e.g., quarterly) where you:
  - check progress per theme,
  - adjust priorities and capacity,
  - kill or pause low‑value initiatives.

Questions to ask:

- “Are we learning fast enough from big bets?”
- “Are any themes starved of investment?”
- “Do we have too many items stuck in ‘In Progress’?”

---

### 6. Dealing with Shared Platforms & Dependencies

In portfolios with shared platforms:

- the same team may serve multiple product roadmaps.

Risks:

- platform team becomes:
  - over‑committed,
  - reactive to the loudest stakeholder.

Mitigations:

- give platforms:
  - their own **roadmaps** and **themes**,
  - aligned to portfolio themes.
- agree:
  - **capacity slices** per consuming area,
  - or criteria for deciding what to pick up next.

Tools:

- use:
  - dependency fields or links in `Jira`,
  - or higher‑level portfolio tools (`Jira Align`, `Planview`, `Clarity`).

---

### 7. Governance for Portfolio Decisions

In enterprises/banks, portfolio decisions often involve:

- product leaders,
- technology leaders,
- finance,
- risk/compliance,
- sometimes operations.

Governance patterns:

- **Portfolio Review Forums** (monthly/quarterly):
  - review:
    - progress on themes,
    - key metrics,
    - proposals for new or changed initiatives.
- **RACI**:
  - define:
    - who is Responsible, Accountable, Consulted, Informed,
  - for portfolio decisions.

Aim:

- **speed with safety**:
  - decisions are not random,
  - but also not stuck for months.

---

### 8. Example – SME Lending Portfolio Snapshot

Suppose:

- Themes:
  - T1: Experience,
  - T2: Risk & Compliance,
  - T3: Operations & Efficiency.

Portfolio initiatives:

- Under T1 (Experience):
  - “Digital Application v2” (Product team),
  - “Self‑Service Loan Management Portal.”
- Under T2 (Risk & Compliance):
  - “Configurable Risk Rules Engine” (Risk Platform),
  - “Regulation XYZ Compliance Changes.”
- Under T3 (Operations):
  - “Operations Workbench Automation,”
  - “Collections Optimization.”

Portfolio view shows:

- per initiative:
  - owner team,
  - stage (Discovery / In Progress / Done),
  - expected value,
  - major dependencies.

Leaders can see:

- where to **focus attention**,
- which initiatives:
  - are stuck,
  - or need re‑scoping or cancellation.

---

### 9. Beginner‑Friendly Checklist

- [ ] Do we know:
  - [ ] which products and platforms are in this portfolio?
  - [ ] which strategic themes apply?
- [ ] For each theme:
  - [ ] do we have a list of major initiatives?
  - [ ] do we know which teams own them?
  - [ ] do we know their current status?
- [ ] Do we have:
  - [ ] a simple view of capacity/allocation by theme?
  - [ ] regular portfolio review sessions?
- [ ] Are platform teams:
  - [ ] part of the roadmap and portfolio conversation?

If many boxes are unchecked, your **portfolio view is incomplete**, and strategy will be hard to execute.

---

### Connections to Other Files

- `05-strategic-themes-goals-and-okrs.md` – defines the themes you manage across the portfolio.
- `07-roadmap-levels-and-views.md` – describes the different roadmap views used in portfolios.
- `09-capacity-planning-and-funding-models.md` – dives deeper into capacity and funding decisions.
- `24-governance-alignment-and-cadence.md` – how decisions and reviews are structured over time.

