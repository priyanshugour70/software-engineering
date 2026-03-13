## 13 – Roles and Positions in Product Strategy & Roadmapping

This file explains **who is involved** in Product Strategy & Roadmap work, what they do, and how they collaborate.

We focus on:

- core product roles,
- key partners in engineering, business, and risk,
- how responsibilities differ in startups vs enterprises/banks.

---

### 1. Core Product Roles

#### 1.1 Product Manager (PM)

Typical responsibilities:

- own **problem and outcome space** for a product or area,
- synthesize:
  - market and user insights,
  - business cases,
  - feasibility findings,
  - into strategy proposals.
- maintain:
  - product roadmap at product/team level,
  - initiative/epic backlog.
- run:
  - discovery and prioritization sessions,
  - stakeholder alignment conversations.

In strategy & roadmap phase, PMs:

- connect:
  - company strategy,
  - opportunities and constraints,
  - into **specific initiatives and epics**.

#### 1.2 Senior / Lead Product Manager

Responsibilities:

- same as PM, but:
  - for **larger scope** (e.g., multiple squads or sub‑domains),
  - with more emphasis on **cross‑team alignment**.
- co‑create:
  - product strategy with Heads of Product,
  - portfolio views with other leads.

They often:

- facilitate:
  - roadmap and strategy workshops,
  - theme and OKR creation sessions.

#### 1.3 Head of Product / Director of Product

Responsibilities:

- own:
  - strategy and roadmap **for a domain or segment**,
  - e.g., SME banking, consumer cards.
- align:
  - product strategy with company/segment strategy,
  - capacities and funding with portfolio priorities.
- make:
  - trade‑off decisions between products,
  - final calls on what is in/out of a horizon.

They work heavily with:

- business leadership,
- technology leadership,
- risk/compliance leadership.

---

### 2. Engineering & Architecture Roles

#### 2.1 Engineering Manager / Tech Lead

Responsibilities:

- represent **technical feasibility and constraints** in strategy discussions,
- estimate:
  - effort,
  - complexity,
  - dependencies,
  - risks for initiatives and epics.
- co‑design:
  - technical slices and sequencing (e.g., MVP vs v2).

In roadmapping:

- ensure:
  - technical enablers and platform work are visible in the roadmap,
  - capacity allocations include non‑feature work.

#### 2.2 Solution / Domain Architect

Responsibilities:

- design:
  - target state architectures,
  - integration patterns,
  - platform and data strategies.
- assess:
  - scalability,
  - performance,
  - resilience,
  - integration impacts of strategic options.

They help answer:

- “Can we achieve this strategy on our current stack?”
- “What enabling changes must come first?”

#### 2.3 Platform / Infrastructure Leads

Responsibilities:

- own:
  - cross‑cutting platforms (e.g., risk engine, data platform, identity),
  - infrastructure capabilities (e.g., cloud, observability).

In strategy & roadmapping:

- ensure:
  - platform roadmaps are aligned with product needs,
  - capacity and sequencing are realistic for shared services.

---

### 3. Business & Operations Roles

#### 3.1 Business Owners / P&L Owners

Responsibilities:

- accountable for:
  - revenue,
  - cost,
  - risk outcomes of a product or segment.
- provide:
  - strategic context,
  - commercial targets,
  - regulatory and competitive pressures.

They:

- co‑own:
  - big bets and outcome targets,
  - prioritization criteria.

#### 3.2 Operations / Service Managers

Responsibilities:

- run:
  - day‑to‑day operations and servicing,
  - e.g., loan processing, call centers, back office.
- bring:
  - real‑world constraints,
  - process pain points and ideas,
  - capacity limits.

They ensure:

- strategy and roadmaps:
  - are **operationally feasible**,
  - contain enough work to reduce manual pain and risk.

---

### 4. Risk, Compliance & Legal Roles

#### 4.1 Risk Managers (Credit, Operational, Market, etc.)

Responsibilities:

- ensure:
  - strategies and roadmaps:
    - meet risk appetite,
    - reduce critical risk exposures.
- review:
  - new product and feature proposals,
  - model or rule changes.

In strategy:

- highlight:
  - non‑negotiable requirements,
  - areas where innovation is possible with guardrails.

#### 4.2 Compliance & Regulatory Affairs

Responsibilities:

- interpret:
  - regulations,
  - internal policies,
  - guidelines from regulators.
- ensure:
  - roadmap includes items needed for compliance.

They are key stakeholders for:

- sequencing around regulatory deadlines,
- approving risk and product designs.

#### 4.3 Legal Counsel

Responsibilities:

- advise on:
  - contracts,
  - disclosures,
  - terms and conditions,
  - legal risk of product ideas.

They can:

- be involved early in:
  - new business models,
  - partnerships,
  - cross‑border expansions.

---

### 5. Data, Analytics & Finance Roles

#### 5.1 Data Analysts & Data Scientists

Responsibilities:

- provide:
  - quantitative insights for strategy,
  - impact analysis of initiatives.
- help:
  - define and track metrics,
  - design experiments (A/B tests, pilots).

In roadmapping:

- advise:
  - which metrics best represent outcomes,
  - feasibility of measurement.

#### 5.2 Finance / Controlling

Responsibilities:

- shape:
  - budget envelopes,
  - cost allocations.
- partner on:
  - business cases,
  - ROI and payback analysis,
  - tracking spend vs value.

They are crucial for:

- aligning strategy with **funding models** (see `09-capacity-planning-and-funding-models.md`).

---

### 6. How the Roles Work Together (Simplified RACI)

For **Product Strategy & Roadmap**:

- **Accountable (A)**:
  - Head of Product / Portfolio Lead (for the domain),
  - sometimes shared with Business Owner / P&L Owner.
- **Responsible (R)**:
  - Product Managers and Engineering Leaders:
    - crafting options,
    - shaping initiatives,
    - building roadmaps.
- **Consulted (C)**:
  - Risk,
  - Compliance,
  - Operations,
  - Data & Analytics,
  - Architecture.
- **Informed (I)**:
  - broader stakeholders,
  - impacted teams and functions.

This may vary by organization, but:

- someone must clearly **own** the roadmap and strategy outcome.

---

### 7. Startups vs Enterprises/Banks

#### 7.1 Startups

- small teams,
- roles are:
  - blended (e.g., PM + founder + sales),
  - less formal governance.

Strategy & roadmap work:

- happens faster,
- with less documentation,
- but still benefits from:
  - explicit themes,
  - clear bets,
  - simple roadmaps.

#### 7.2 Enterprises/Banks

- many specialized roles,
- strong governance and risk functions,
- more complex dependencies and constraints.

Strategy & roadmap work:

- must integrate:
  - multiple stakeholders early,
  - risk and compliance requirements,
  - portfolio and capacity limits.

Good collaboration patterns:

- **joint workshops** for themes and roadmaps,
- shared review forums (see `24-governance-alignment-and-cadence.md`),
- clear documentation and decision logs.

---

### 8. Beginner Checklist

- [ ] Do we know:
  - [ ] who is accountable for the product strategy and roadmap?
  - [ ] who is responsible for building and updating it?
  - [ ] which stakeholders must be consulted?
- [ ] Are:
  - [ ] risk and compliance involved early enough?
  - [ ] operations and support represented in roadmap discussions?
- [ ] Do product and engineering:
  - [ ] jointly shape initiatives and sequencing?

If not, strategy and roadmaps may:

- be fragile,
- ignore key constraints,
- or lack buy‑in from critical partners.

---

### Connections to Other Files

- `14-skills.md` – skills needed for the above roles to perform strategy & roadmap work well.
- `24-governance-alignment-and-cadence.md` – where and how these roles meet to align and decide.
- `22-best-practices.md` – collaboration patterns between roles.

