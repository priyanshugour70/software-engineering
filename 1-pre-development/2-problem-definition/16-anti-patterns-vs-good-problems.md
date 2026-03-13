## 16 – Anti-Patterns vs Good Problem Statements

This file shows **side‑by‑side examples** of weak and strong problem statements.  
Use it as a **quick reference** when writing or reviewing your own.

We cover:

- A. Vague vs specific
- B. Solution‑biased vs solution‑agnostic
- C. Overly broad vs appropriately scoped
- D. Data‑free vs evidence‑based

---

### A. Vague vs Specific

**Anti‑pattern (vague)**  
> “Improve SME onboarding.”

Problems:

- Who exactly?
- Which part of onboarding?
- What’s wrong with it?

**Improved (specific)**  
> “Existing SME customers in Country X who attempt to open an additional current account via our online portal frequently abandon at the document upload step because requirements are unclear, leading to a 40% abandonment rate and 200 extra support calls per month.”

What changed:

- Clear **segment** (“existing SMEs in Country X…”),
- Clear **context** (“open an additional current account via online portal”),
- Clear **pain** (abandonment at a specific step due to unclear requirements),
- Clear **impact** (abandonment rate + support calls).

---

### B. Solution-Biased vs Solution-Agnostic

**Anti‑pattern (solution‑biased)**  
> “We need to build a mobile app for SME lending.”

Problems:

- Assumes the solution (mobile app),
- No description of:
  - current pain,
  - who is affected,
  - why now.

**Improved (solution‑agnostic)**  
> “SME owners applying for loans must visit branches multiple times and cannot track application status between visits, causing delays, uncertainty, and a 15% abandonment rate in Country X.”

What changed:

- Focuses on:
  - **delay**,
  - **lack of visibility**,
  - **abandonment**,
- Leaves room for many possible solutions (not just a mobile app).

---

### C. Overly Broad vs Appropriately Scoped

**Anti‑pattern (too broad)**  
> “Fix corporate onboarding across all markets.”

Problems:

- Impossible to tackle in one initiative.
- Different markets may have different problems and regulations.

**Improved (scoped)**  
> “For corporate customers in Country X with annual revenue between 10–100M, opening a primary operating account takes an average of 15 days and requires 5 separate document submissions, causing delays in go‑live and a 20% increase in onboarding‑related complaints.”

What changed:

- Narrowed to:
  - a specific country,
  - customer band,
  - account type.
- States clear **current‑state metrics** and **impacts**.

---

### D. Data-Free vs Evidence-Based

**Anti‑pattern (data‑free)**  
> “Customers are unhappy with our payments experience.”

Problems:

- No indication of:
  - how many customers,
  - how severe,
  - which part of the journey.

**Improved (evidence‑based)**  
> “In the last quarter, 28% of support tickets from SMEs relate to outbound payments, with 60% of those mentioning ‘unclear status’ or ‘not sure if payment went through’. Payment failure rate is 2.5%, and 40% of failed payments do not trigger a clear notification, leading to re‑tries and duplicate payments.”

What changed:

- Uses **ticket data and failure rates** to:
  - show scope and severity,
  - point to specific issues (“unclear status”, notification gaps).

---

### E. Ignoring Constraints vs Constraint-Aware

**Anti‑pattern (ignores constraints)**  
> “Allow fully automated loan approvals for all SME segments.”

Problems:

- May conflict with:
  - risk appetite,
  - regulatory restrictions,
  - data availability.

**Improved (constraint‑aware)**  
> “For low‑risk existing SME customers in Country X, current loan approvals are fully manual and take 5 days despite having rich transaction history and behavior data. This causes delays for low‑risk cases that could fall within our automated underwriting policies, subject to current regulatory limits and model capabilities.”

What changed:

- Recognizes:
  - risk segmentation,
  - existing data and models,
  - that automation must align with policies and regulations.

---

### How to Use This File

When you write or review a problem statement:

- Compare it with these patterns.
- Ask:
  - Is it **specific**?
  - Is it **solution‑agnostic**?
  - Is it **appropriately scoped**?
  - Does it use some **evidence**?
  - Does it **acknowledge constraints** where needed?

If the answer is “no” for several questions, refine before moving forward.

---

### Connections to Other Files

- `04-frameworks.md` – tools to turn anti‑patterns into strong statements.
- `07-problem-evaluation.md` – criteria you can use to systematically rate problems.

