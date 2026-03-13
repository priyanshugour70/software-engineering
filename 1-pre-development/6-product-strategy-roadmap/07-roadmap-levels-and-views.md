## 07 – Roadmap Levels & Views

This file explains **how to represent the roadmap** at different levels of detail for different audiences.

We cover:

- roadmap levels (company, portfolio, product, team),
- common roadmap formats (timeline, now/next/later, swimlanes),
- examples for digital SME lending,
- tips for regulated environments.

---

### 1. Why Multiple Roadmap Views?

Different stakeholders need **different levels of detail**:

- Executives:
  - want to see major bets, timelines, and risk.
- Product & portfolio leaders:
  - want to see themes, initiatives, and capacity allocation.
- Delivery teams:
  - want to see epics, dependencies, and near‑term work.

Using **one huge roadmap** for everyone:

- confuses beginners,
- overwhelms executives,
- hides important details for teams.

Instead:

- keep **one underlying plan**, but
- present **separate views** tailored to needs.

---

### 2. Roadmap Levels

You can think in four main levels:

1. **Company / Segment Roadmap**
2. **Portfolio / Domain Roadmap**
3. **Product Roadmap**
4. **Team / Squad Roadmap**

#### 2.1 Company / Segment Roadmap

Purpose:

- communicate **big bets and directions** for 1–3 years.

Content:

- strategic themes,
- major initiatives (cross‑product),
- key regulatory or strategic milestones.

Audience:

- executives, board, senior leaders.

Time horizon:

- multi‑year (Horizon 2–3),
- **low granularity**.

#### 2.2 Portfolio / Domain Roadmap

Purpose:

- show how multiple products and platforms:
  - contribute to shared themes and goals,
  - sequence work to avoid conflicts.

Content:

- initiatives per product/platform,
- high‑level dependencies,
- capacity allocation per theme.

Audience:

- heads of product, portfolio managers, senior tech leads.

Time horizon:

- 12–24 months, updated quarterly.

#### 2.3 Product Roadmap

Purpose:

- show **initiatives and epics** for a specific product,
- connect them to:
  - themes,
  - goals,
  - and metrics.

Content:

- initiatives/epics with:
  - problem statements,
  - outcome hypotheses,
  - rough timing.

Audience:

- product managers, engineering managers, key stakeholders.

Time horizon:

- 6–18 months, with:
  - detailed near‑term,
  - fuzzy mid‑term.

#### 2.4 Team / Squad Roadmap

Purpose:

- show:
  - upcoming epics,
  - key milestones,
  - release slices.

Content:

- epic breakdown,
- dependencies with other teams,
- relation to sprints / increments.

Audience:

- delivery teams and their immediate stakeholders.

Time horizon:

- 1–3 quarters,
- strongly aligned with sprint/cadence.

---

### 3. Roadmap Formats

Common **visual formats**:

1. **Timeline‑based**
2. **Now / Next / Later**
3. **Swimlane by Theme or Product**
4. **Hybrid**

#### 3.1 Timeline‑Based

- Shows work on a calendar timeline (quarters, months).
- Useful for:
  - regulatory deadlines,
  - major launches.

Risks:

- stakeholders may:
  - interpret all dates as fixed commitments,
  - ignore uncertainty.

Mitigations:

- use:
  - **time bands** (Q1, Q2) instead of exact days,
  - labels like:
    - “committed,”
    - “tentative,”
    - “exploratory.”

#### 3.2 Now / Next / Later

- Groups initiatives into:
  - **Now** – in progress or starting soon,
  - **Next** – likely upcoming bets,
  - **Later** – options and ideas.

Pros:

- emphasizes **priority and sequence**, not exact dates,
- easier to maintain.

Cons:

- less precise for regulatory or dependency planning.

Good for:

- team and product‑level roadmaps.

#### 3.3 Swimlane by Theme or Product

- Roadmap is divided into **swimlanes**:
  - per theme,
  - product,
  - or platform.

Benefits:

- shows:
  - how capacity is allocated,
  - how each theme is progressing.

Useful in:

- portfolios with many teams and products.

#### 3.4 Hybrid Views

Many organizations use:

- timeline + swimlanes,
- or now/next/later grouped by theme.

The important part:

- **consistency of meaning**, not the specific tool:
  - `Jira`, `Aha!`, `Productboard`, `airfocus`, etc. can all express these views.

---

### 4. Example – SME Lending Roadmaps at Different Levels

#### 4.1 Company / Segment View

Shows:

- Major initiative:
  - “Digital SME Lending Transformation (3‑year program).”
- Milestones:
  - Year 1: core digital journey and decisioning engine live in Country A.
  - Year 2: expansion to Country B and new products.
  - Year 3: expanded ecosystem offerings and partner integrations.

No epic‑level details, only **big rocks**.

#### 4.2 Portfolio / Domain View

Shows lanes for:

- SME Lending Product,
- Risk Platform,
- Data Platform,
- Operations / Servicing.

For each lane:

- key initiatives and dependencies,
- e.g., Risk Platform initiative must land before new SME product launch.

#### 4.3 Product View (Digital SME Lending)

Shows:

- initiatives like:
  - “Digital Application v2,”
  - “Configurable Risk Rules,”
  - “Operations Workbench.”
- each mapped to:
  - themes (Experience, Risk, Operations),
  - and quarters or now/next/later.

#### 4.4 Team / Squad View

For the “Application Journey” squad:

- next 2–3 quarters of epics:
  - “Onboarding Flow Redesign,”
  - “Document Upload & Verification,”
  - “Eligibility Pre‑Check.”
- with:
  - dependencies,
  - release milestones,
  - links to stories in `Jira` / `Azure DevOps`.

---

### 5. Making Roadmaps Beginner‑Friendly

To help new joiners and non‑product stakeholders:

- include legends:
  - what colors and shapes mean,
  - what “committed vs tentative” means.
- avoid:
  - too many technical acronyms without explanation,
  - tiny fonts and cluttered diagrams.
- for each view, clearly label:
  - **time horizon**,
  - **audience**,
  - **update cadence**.

Tip:

- include a **short explainer** text near each roadmap view in `Confluence` or `Notion`.

---

### 6. Special Considerations for Regulated Products

For regulated products (e.g., lending, payments):

- some roadmap items are:
  - **must‑do by a certain date** (regulatory changes).

Patterns:

- separate swimlane or section for:
  - “Regulation & Compliance.”
- clearly mark:
  - **non‑negotiable** vs **discretionary** items.
- use:
  - dependency arrows or annotations to show:
    - which product or platform initiatives depend on regulatory or risk work.

Roadmaps should:

- reflect **regulator expectations** (when appropriate),
- be consistent with:
  - internal risk & compliance plans.

---

### 7. Keeping Roadmaps Up to Date

Roadmaps are **living artifacts**:

- review at least quarterly:
  - progress vs plan,
  - changes in metrics,
  - new risks or opportunities.

Good practices:

- track:
  - when a roadmap view was last updated,
  - who is the owner.
- record:
  - major changes and reasons,
  - e.g., “initiative X moved from Q3 to Q4 due to dependency Y.”

This builds:

- trust,
- and historical context.

---

### Connections to Other Files

- `03-workflow.md` – shows where roadmap construction sits in the overall flow.
- `06-prioritization-frameworks.md` – how priorities feed into roadmap items.
- `08-portfolio-and-theme-management.md` – how to manage multiple roadmaps together.
- `12-documents-and-artifacts.md` – includes roadmap templates and examples.
- `22-best-practices.md` – good patterns for roadmap communication.

