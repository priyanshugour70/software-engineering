## 23 – Templates for Problem Definition

This file provides **markdown templates** you can copy into your own docs or tools.

We include:

- A. Problem Definition Scope & Plan
- B. Problem Statement Document
- C. Constraints & Assumptions Register
- D. Problem Backlog Table

---

### A. Problem Definition Scope & Plan Template

```markdown
# Problem Definition – Scope & Plan – <Domain / Journey>

## 1. Context
- Opportunity / theme:
  - <Reference to opportunity from phase 1>
- Why now:
  - <Strategic / operational / regulatory drivers>

## 2. Objectives
- Clarify the core problem(s) in:
  - <domain / journey>
- Deliver:
  - <#> high-quality problem statements
  - Baseline and target metrics
  - Documented constraints and scope

## 3. Scope
- In scope:
  - <Segments / products / geographies / channels>
- Out of scope (for now):
  - <Items left for future phases>

## 4. Timebox & Milestones
- Start date:
- End date:
- Milestones:
  - Week 1:
  - Week 2:
  - Week 3:

## 5. Team & Stakeholders
- Core team:
  - Product:
  - Business owner:
  - UX/Research:
  - Engineering:
  - Data/BI:
  - Ops/Process:
  - Risk/Compliance:
- Stakeholders to consult:
  - <Names / roles>

## 6. Deliverables
- Problem Statement Document(s)
- Scope & Constraints Register
- Current State & Metrics summary
- Handover summary to research / design / delivery
```

---

### B. Problem Statement Document Template

```markdown
# Problem Statement – <ID> <Short Title>

## 1. Summary
<2–3 sentence summary of the problem, in plain language.>

## 2. Context & Background
- Opportunity / theme:
  - <Link / short description>
- Relevant strategies / OKRs:
  - <List>

## 3. Target Users & Stakeholders
- External users:
  - <Segments, examples>
- Internal stakeholders:
  - <Teams / roles affected>

## 4. Current State & Symptoms
- Description:
  - <How things work today, step by step>
- Metrics (baseline):
  - Volume:
  - Completion / conversion:
  - Time / latency:
  - Errors / rework:
  - Support / operational load:
- Qualitative evidence:
  - <Key quotes or themes from interviews / tickets>

## 5. Problem Statement (Core)
> “<Concise statement capturing who, what, why it matters, and context.>”

## 6. Scope
- In scope:
  - <Segments>
  - <Products>
  - <Geographies>
  - <Channels / processes>
- Out of scope:
  - <What this problem does NOT cover>

## 7. Desired Outcomes & Metrics
- User outcomes:
  - <What improves for users?>
- Business outcomes:
  - <What improves for the organization?>
- Metrics (target ranges):
  - <Metric 1>: from <baseline> to <target>
  - <Metric 2>: from <baseline> to <target>

## 8. Constraints & Assumptions
- Constraints:
  - Regulatory / compliance:
  - Technical / systems:
  - Operational:
- Assumptions:
  - <Assumption + owner + plan to validate>

## 9. Risks
- Product / market risks:
- Execution risks:
- Regulatory risks:
- Organizational risks:

## 10. Stakeholder Alignment
- Reviewed with:
  - <Names / roles>
- Open questions / disagreements:
  - <List, with notes>

## 11. Links
- Opportunity brief:
- Data / dashboards:
- Research notes:
- Related initiatives / epics:
```

---

### C. Constraints & Assumptions Register Template

```markdown
# Constraints & Assumptions – <Problem ID / Title>

## 1. Constraints

| ID | Type        | Description                                   | Source (policy/system)       | Owner          |
|----|-------------|-----------------------------------------------|------------------------------|----------------|
| C1 | Regulatory  | <e.g., KYC rule requiring manual verification>| <Reg # / internal policy>    | <Name/Team>    |
| C2 | Technical   | <e.g., core system batch window midnight-4am> | <System / doc reference>     | <Name/Team>    |
| C3 | Operational | <e.g., call center operates 8am–8pm local>    | <Ops manual / process doc>   | <Name/Team>    |

## 2. Assumptions

| ID | Assumption                                      | Owner       | Validation Plan                 | Target Date |
|----|-------------------------------------------------|------------|---------------------------------|------------|
| A1 | <e.g., existing data is sufficient for scoring> | <Name/Team>| <e.g., data quality analysis>   | <Date>     |
| A2 | <e.g., SMEs will adopt self-service>            | <Name/Team>| <e.g., pilot + usage tracking>  | <Date>     |
```

---

### D. Problem Backlog Table Template

```markdown
| ID        | Title                             | Domain / Journey       | Stage              | Priority | Owner  | Link                                |
|-----------|-----------------------------------|------------------------|--------------------|----------|--------|-------------------------------------|
| PD-SME-01 | SME Online Onboarding Drop-offs   | SME Onboarding         | Defined            | High     | <PM>   | [Doc](./PD-SME-01-problem.md)       |
| PD-SME-02 | Loan Status Inquiry Overload      | SME Lending            | Draft              | Medium   | <PM>   | [Doc](./PD-SME-02-problem.md)       |
| PD-RET-01 | Card Dispute Journey Confusion    | Retail Card Operations | Discovery In Prog. | Low      | <PM>   | [Notes](./PD-RET-01-notes.md)       |
```

You can extend with:

- links to:
  - opportunity IDs,
  - strategic themes,
  - risk levels.

---

### Connections to Other Files

- `10-documents.md` – describes the purpose of each artifact.
- `24-checklists.md` – checklists you can apply after filling these templates.

