## 23 – Templates for Business Case & ROI

This file provides **markdown templates** to structure your work.

We include:

- A. Business case brief
- B. Driver & assumption sheet
- C. Business case narrative (short form)

---

### A. Business Case Brief Template

```markdown
# Business Case Brief – <Initiative Name>

## 1. Context
- Problem(s):
  - <Link/summary>
- Research insights:
  - <Key points>
- Strategic objectives:
  - <OKRs / themes>

## 2. Initiative Definition
- Proposed solution / scope (high-level):
  - <Short description>
- In scope:
  - <Segments, products, geographies>
- Out of scope:
  - <Items left for future phases>

## 3. Value & Cost Drivers (Initial View)
- Value drivers:
  - <e.g., more SME loans, higher conversion, lower processing cost>
- Cost drivers:
  - <e.g., integrations, infra, vendor fees, change/training>

## 4. Initial Assumptions & Questions
- Key assumptions:
  - A1: ...
  - A2: ...
- Open questions:
  - Q1: ...
  - Q2: ...

## 5. Next Steps
- Data and analysis needed:
  - <What to gather>
- Stakeholders to involve:
  - <Names/roles>
- Target date for full business case:
  - <Date>
```

---

### B. Driver & Assumption Sheet Template

```markdown
# Drivers & Assumptions – <Initiative Name>

## 1. Volume & Behavior Drivers

| ID | Driver                        | Baseline | Assumption (Base) | Low | High | Source / Notes |
|----|-------------------------------|----------|--------------------|-----|------|----------------|
| D1 | # SME customers in segment    | 50,000   | 50,000             | -   | -    | CRM, 2026 Q1   |
| D2 | Adoption rate by Year 3       | -        | 30%                | 20% | 40%  | Assumption v1  |
| D3 | Conversion uplift (loan appl.)| 40%      | 45%                | 42% | 48%  | Funnel analysis|

## 2. Financial Drivers

| ID | Driver                        | Baseline | Assumption (Base) | Low | High | Source / Notes      |
|----|-------------------------------|----------|--------------------|-----|------|---------------------|
| F1 | Profit per SME loan           | 2,000    | 2,000              | -   | -    | Finance, 2025 actual|
| F2 | Processing cost per loan      | 80       | 56 (−30%)          | 60  | 50   | Ops & BI estimate   |

## 3. Cost Drivers

| ID | Driver                        | Estimate (Base) | Low  | High  | Source / Notes         |
|----|-------------------------------|-----------------|------|-------|------------------------|
| C1 | Build cost                    | 2.7M            | 2.2M | 3.3M  | Eng + PM + Finance     |
| C2 | Annual run cost               | 0.55M           | 0.5M | 0.7M  | Tech Ops + Vendors     |

## 4. Risk & External Drivers (If Applicable)

| ID | Driver                        | Description                        | Handling in Model       |
|----|-------------------------------|------------------------------------|-------------------------|
| R1 | Macro conditions              | e.g., interest rate environment    | Covered via scenario set|
| R2 | Regulatory change             | e.g., new capital requirements     | Not explicitly modeled  |
```

---

### C. Short-Form Business Case Narrative Template

```markdown
# Business Case – <Initiative Name> – Short Form

## 1. Executive Summary
- Proposal:
  - <1–2 sentences>
- Why now:
  - <Drivers and urgency>
- Key numbers (Base case):
  - ROI: <x%>
  - Payback: <~years>
  - NPV (at <r>%): <value>
- Recommendation:
  - <Proceed / Adjust / Defer / Stop> with <conditions>.

## 2. Context & Strategic Fit
- Problem(s) addressed:
  - <Summary>
- Evidence from research:
  - <Key insights>
- Strategic objectives supported:
  - <List>

## 3. Scope & Solution Overview
- High-level solution:
  - <What we are building/changing>
- Scope:
  - In:
    - <Items>
  - Out:
    - <Items>

## 4. Benefits (Base Case)
- Revenue:
  - <Narrative + table of main drivers>
- Cost:
  - <Narrative + key savings>
- Risk:
  - <Narrative + quantified where possible>
- Intangibles:
  - <Brand, CX, enablement>

## 5. Costs & Investments
- Build (one-time):
  - <Summary + numbers>
- Run (annual):
  - <Summary + numbers>

## 6. Financial Summary & Scenarios
- Metrics (Base case):
  - ROI:
  - Payback:
  - NPV / IRR (if applicable):
- Conservative scenario:
  - <Key deltas>
- Aggressive scenario:
  - <Key deltas>

## 7. Risks & Dependencies
- Main risks:
  - <Top 5–10 with qualitative impact>
- Dependencies:
  - <Other initiatives, vendors, regulatory events>

## 8. Recommendation & Next Steps
- Recommended decision:
  - <Text>
- Conditions / stage-gates:
  - <Metrics, timelines>
- Immediate next steps:
  - <Actions and owners>
```

---

### Connections to Other Files

- `10-documents-and-artifacts.md` – explains how these templates fit into the overall documentation.
- `24-checklists.md` – checklists to validate completeness and quality of filled templates.

