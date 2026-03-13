## 10 – Documents & Artifacts in Market Opportunity Discovery

This file explains the **key documents** you should produce during discovery and how to structure them.

We cover:

- A. Core document types
- B. Opportunity brief template (with example)
- C. Opportunity backlog / radar
- D. Discovery readout deck
- E. Storage, naming, and linking conventions

Where you see “template”, you can find concrete markdown versions in `23-templates.md`.

---

### A. Core Document Types

1. **Discovery Scope & Plan**
   - Why you are doing discovery now.
   - What segment/product/region you are focusing on.
   - Timeline and team.

2. **Opportunity Briefs**
   - One per candidate opportunity.
   - Short but structured.

3. **Opportunity Backlog / Radar**
   - A list or board showing **all opportunities** with basic metadata and priority.

4. **Evaluation & Prioritization Notes**
   - Scores, workshop outcomes, and decisions.

5. **Discovery Readout / Summary**
   - A concise artifact used in leadership and team briefings.

These documents can live in:

- Confluence / Notion / SharePoint / internal wiki.

---

### B. Opportunity Brief Template (Beginner Friendly)

An **opportunity brief** is the central artifact of this phase.

#### Suggested Sections

1. **Title & ID**
   - Short, descriptive title (e.g., “Digital SME Credit Line with Fast Decisions”).
   - Unique ID (e.g., MOD‑001).

2. **Summary (1–3 sentences)**
   - High‑level description of the opportunity.

3. **Target Segment**
   - Who is affected? (e.g., “SMEs with annual revenue 0.5–5M, in retail sector, in EU.”)

4. **Customer Problem / Job‑To‑Be‑Done**
   - What are they trying to achieve?
   - What is painful or missing today?

5. **Current Journey & Alternatives**
   - How do they solve it today?
   - What tools, competitors, or manual workarounds do they use?

6. **Opportunity Description**
   - What is the “space” where we could create value?
   - Don’t describe a specific feature yet; describe **what would be better** for the customer.

7. **Value & Impact (Qualitative + Quantitative)**
   - For customers: what improves?
   - For the business: possible revenue, cost, risk changes (even rough).

8. **Strategic Fit**
   - How does this map to company/product strategy or OKRs?

9. **Evidence & Signals**
   - Data points from:
     - analytics,
     - support,
     - interviews,
     - market/industry,
     - regulation.

10. **Risks, Unknowns, and Assumptions**
    - What must be true for this to work?
    - What do we need to validate next?

11. **Initial Evaluation Snapshot**
    - Scores from `07-opportunity-evaluation.md` (optional at early stage).

12. **Recommended Next Steps**
    - e.g., “Move to Problem Definition and run 6 customer interviews + financial sizing.”

---

#### Mini Example: SME Digital Credit Line Brief (Condensed)

- **ID**: MOD‑001  
- **Title**: Digital SME Credit Line with Near Real‑Time Approvals  
- **Summary**: Enable SME customers to obtain a revolving credit facility fully online with fast, data‑driven approvals, reducing friction and increasing lending volume.

- **Target Segment**:  
  SMEs with 0.5–5M annual revenue, operating retail and e‑commerce businesses in Country X, with active transaction accounts at our bank.

- **Customer Problem / JTBD**:  
  When cash‑flow is tight (e.g., before payroll or supplier payments), SMEs need quick access to short‑term funds without visiting a branch or waiting days for a decision.

- **Current Journey & Alternatives**:  
  - Visit branch, provide many paper documents, wait days or weeks.  
  - Use credit cards with high interest or informal lenders.  
  - Delay payments to suppliers (damaging relationships).

- **Opportunity Description**:  
  Leverage our existing SME transaction data and risk models to offer a digital credit line application and approval process within hours (or minutes), with transparent limits and pricing.

- **Value & Impact**:  
  - Customers: less stress, faster decisions, better cash‑flow management.  
  - Business: increased lending volume, higher share of wallet, stronger SME relationships.

- **Strategic Fit**:  
  Directly supports strategic objective “Grow SME revenue by 20% with digital engagement.”

- **Evidence & Signals**:  
  - 30% of SME NPS detractors mention lending process as slow.  
  - Competitor Y launched digital SME credit line with strong adoption.  
  - Usage data shows many SMEs frequently near zero balance before payroll.

- **Risks & Unknowns**:  
  - Credit and fraud risk models for real‑time decisions need validation.  
  - Regulatory requirements for digital-only lending need legal confirmation.

- **Recommended Next Steps**:  
  - Move to Problem Definition and Feasibility.  
  - Run SME interviews focused on lending experiences.  
  - Partner with risk and compliance to explore real‑time decisioning.

You can find a **markdown template** for this in `23-templates.md`.

---

### C. Opportunity Backlog / Radar

The **opportunity backlog** is a **single list or board** of all identified opportunities with key metadata.

#### Minimal Fields

- ID and Title
- Segment / domain (e.g., SME lending, payments)
- Stage (idea, brief drafted, evaluated, moved forward, parked)
- Priority (e.g., High/Medium/Low or rank)
- Owner (who is responsible)
- Link to opportunity brief

#### Optional Fields

- Strategic theme / OKR linked
- Expected time horizon (near / mid / long term)
- Risk level (low / medium / high)

You can represent this as:

- A **table** in Confluence/Notion.
- A **Kanban board** in Jira/Trello.
- A **radar diagram** (inner ring = now, outer ring = later).

Purpose:

- Give leaders and teams a **single view of the opportunity landscape**.

---

### D. Discovery Readout Deck

The **readout** is usually a short deck or document used to:

- Brief leadership,
- Align teams,
- Decide what moves to the next phases.

#### Suggested Structure (10–15 slides or 3–5 pages)

1. **Context & Scope**
   - Why this discovery was done.
   - What domain/segments were covered.

2. **Methods & Inputs**
   - Data sources, interviews, workshops, documents reviewed.

3. **Key Themes & Insights**
   - 3–6 major problem themes or market shifts discovered.

4. **Top Opportunities (Shortlist)**
   - 3–5 top opportunities, each in 1–2 bullets.

5. **Evaluation Summary**
   - Criteria used.
   - Visuals (2×2 matrix, scoring tables).

6. **Recommended Focus**
   - Which opportunities to move forward now vs later.

7. **Next Steps & Ownership**
   - Which team/person will pick each opportunity up.
   - Planned timelines for Problem Definition/Research.

Attach or link to:

- Full opportunity briefs.
- Opportunity backlog.
- Detailed research summaries (optional).

---

### E. Storage, Naming, and Linking

To keep discovery useful over time:

1. **Define a clear folder/page structure**
   - Example:
     - `/pre-development/1-market-opportunity-discovery/`
       - `/opportunities/` – one doc/page per opportunity (MOD‑001, MOD‑002…)
       - `/research/` – notes and data summaries
       - `/readouts/` – final and interim decks/docs

2. **Use consistent IDs and titles**
   - MOD‑001–MOD‑999 for Market Opportunity Discovery items.

3. **Link everything**
   - Each item in the opportunity backlog should link to its brief.
   - Each brief should link out to:
     - research notes,
     - metrics dashboards,
     - readout decks.

4. **Keep a change log if needed**
   - For significant updates, add a small “History” section:
     - “2026‑03 – Initial brief.”
     - “2026‑06 – Updated with new market data.”

---

### F. Connections to Other Files

- `02-objectives.md` – explains the outcomes these documents support.
- `03-workflow.md` – shows at which stages each artifact is created.
- `07-opportunity-evaluation.md` – informs the evaluation parts of briefs and readouts.
- `23-templates.md` – provides ready‑to‑use markdown structures.
- `24-checklists.md` – offers quick checks to ensure your documents are complete.

Treat documents not as bureaucracy, but as **communication tools**: their goal is to help teams and leaders **see the same picture** and **make confident decisions** about where to invest next.

