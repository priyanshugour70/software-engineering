## 10 – Documents & Artifacts in Problem Definition

This file explains the **core documents** produced in the Problem Definition phase and how they relate.

We cover:

- A. Core artifacts
- B. Problem Statement Document (with example)
- C. Scope & Constraints Register
- D. Linking to downstream work

Templates for these artifacts are in `23-templates.md`.

---

### A. Core Artifacts

1. **Problem Statement Document**
   - Main output: a structured description of the problem.
2. **Scope Definition**
   - What is in/out of scope for this phase or initiative.
3. **Constraints & Assumptions Register**
   - Captures key limitations and assumptions.
4. **Current State Summary**
   - Process overview and baseline metrics.

Together, these form the **Problem Definition Package**.

---

### B. Problem Statement Document

The central artifact. Typically includes:

1. **Title & ID**
2. **Summary**
3. **Context & Background**
4. **Target Users & Stakeholders**
5. **Current State & Symptoms**
6. **Impact (User & Business)**
7. **Scope**
8. **Desired Outcomes & Metrics**
9. **Constraints & Assumptions**
10. **Stakeholder Alignment & Approvals (if required)**

#### Example (Condensed)

**ID:** PD‑SME‑LOAN‑001  
**Title:** Slow and Opaque SME Loan Application Process

**Summary**  
Small business owners applying for loans at our bank face a slow, opaque process requiring multiple branch visits and manual paperwork, causing frustration, abandonment, and higher support volume, and leading us to lose potential customers to faster, digital competitors.

**Context & Background**  
This problem emerges within the broader opportunity to grow SME lending through digital channels. Our current process was designed for branch‑centric workflows and has not been fully modernized.

**Target Users & Stakeholders**

- External:
  - Existing SME customers in Country X seeking loans between 50k–500k.
- Internal:
  - Branch staff, SME relationship managers, loan operations team, credit risk analysts.

**Current State & Symptoms**

- Average time from application to decision: 5 business days.
- SMEs must visit a branch 2–3 times on average.
- 15% of initiated applications are abandoned before decision.
- ~500 call center contacts/month asking about application status.

**Impact**

- For SMEs:
  - Lost time away from running their business.
  - Anxiety and uncertainty about outcomes.
- For the bank:
  - Lost deals to fintech lenders with faster decisions.
  - Higher operational costs (manual processing, calls).

**Scope**

- In scope:
  - End‑to‑end SME loan application process for existing customers in Country X.
  - Both branch‑initiated and hybrid (online + branch) journeys.
- Out of scope (for now):
  - New‑to‑bank SMEs.
  - Large corporate loans, other countries.

**Desired Outcomes & Metrics**

- Reduce time to decision from 5 days → < 2 hours for eligible segments.
- Reduce abandonment from 15% → < 5%.
- Reduce loan‑status calls by 50%.

**Constraints & Assumptions**

- Must comply with current KYC and credit risk policies.
- Core decision engine cannot be replaced in the next 12 months.
- Assumption: existing transaction and behavioral data are sufficient for automation.

**Stakeholder Alignment**

- Reviewed with:
  - Head of SME Business,
  - Credit Risk Lead,
  - Operations Manager,
  - Digital Product Lead.

---

### C. Scope & Constraints Register

In larger initiatives, it’s useful to maintain a **separate but linked** document for:

- Detailed scope breakdown:
  - processes, channels, regions, products.
- Detailed constraints:
  - regulatory clauses,
  - system limitations,
  - resource caps.
- Assumptions and their owners:
  - who is responsible for validating each assumption,
  - by when.

This can be:

- a table embedded in the problem statement document, or
- its own page referenced from the main problem doc.

---

### D. Linking to Downstream Work

Problem Definition documents should be **living references** used by:

- Research teams:
  - to design interview guides and studies.
- Designers:
  - to keep solutions anchored to the defined problem.
- Engineers:
  - to understand constraints, scope, and success measures.
- Business & risk:
  - to evaluate trade‑offs and value.

Practical linking:

- In your work tracking tool (e.g., Jira):
  - link epics and initiatives back to the problem statement’s URL.
- In the problem statement:
  - maintain a small section “Related Epics/Initiatives”.

This ensures traceability from:

- **shipped features back to the original problem** they intended to solve.

---

### Connections to Other Files

- `23-templates.md` – ready‑made markdown templates for these documents.
- `02-objectives.md` – defines what these artifacts need to achieve.
- `18-case-studies.md` – shows examples of real problem statements and packages.

