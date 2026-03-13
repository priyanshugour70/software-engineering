## 06 – Prioritization Frameworks for Strategy & Roadmap

This file explains **how to decide what to do first** (and what not to do) when building your product strategy and roadmap.

We focus on:

- value vs effort / complexity,
- RICE,
- WSJF (Weighted Shortest Job First),
- risk‑adjusted ROI,
- practical tips for enterprises/banks.

---

### 1. Why Prioritization Frameworks Matter

Without explicit prioritization:

- the **loudest voice** wins,
- teams:
  - start too many things,
  - stop work halfway,
  - struggle to show impact.

Frameworks do **not** remove judgment, but they:

- make decision criteria **explicit**,
- allow **comparison** between initiatives,
- support **transparent trade‑offs** in front of stakeholders.

---

### 2. Value vs Effort (Simple Starting Point)

The simplest approach:

- estimate **value/impact** and **effort/size** for each initiative/epic.

Visual form:

- a 2×2 matrix:
  - high value / low effort,
  - high value / high effort,
  - low value / low effort,
  - low value / high effort.

Typical guidance:

- prioritize:
  - high value / low effort (“quick wins”),
  - high value / high effort (strategic investments).
- deprioritize:
  - low value / high effort (“avoid these”).

Pros:

- very easy to explain,
- works well as a **first pass**.

Cons:

- subjective,
- does not handle:
  - risk,
  - urgency,
  - dependencies,
  - capacity spread.

---

### 3. RICE (Reach, Impact, Confidence, Effort)

RICE is common in product teams.

Formula:

\[
\text{RICE score} = \frac{\text{Reach} \times \text{Impact} \times \text{Confidence}}{\text{Effort}}
\]

#### 3.1 Components

- **Reach** – how many customers / transactions / operations are affected, in a time window.
- **Impact** – how much each unit of reach is improved (e.g., conversion, time saved).
- **Confidence** – your certainty in reach/impact estimates (0–100%).
- **Effort** – level of work (e.g., person‑months or T‑shirt sizes mapped to numbers).

Example (digital SME lending):

- Initiative A: “Improve digital application UX”
  - Reach: 10,000 SME applications/year.
  - Impact: medium‑high on completion rate.
  - Confidence: 70%.
  - Effort: 4 person‑months.
- Initiative B: “New AI‑based risk score”
  - Reach: 5,000 applications/year (initially).
  - Impact: high on approval / loss rates.
  - Confidence: 40%.
  - Effort: 6 person‑months.

RICE helps you:

- compare initiatives **on the same scale**,
- reflect uncertainty via confidence.

---

### 4. WSJF (Weighted Shortest Job First)

WSJF is popular in scaled agile environments.

Idea:

- prioritize work with **highest value per unit of time**.

Typical formula:

\[
\text{WSJF score} = \frac{\text{Cost of Delay}}{\text{Job Size}}
\]

Where:

- **Cost of Delay (CoD)** ≈ (business value + time criticality + risk reduction / opportunity enablement).
- **Job Size** is an estimate of effort/duration.

#### 4.1 Components

- **Business Value**:
  - revenue, cost savings, customer satisfaction impact.
- **Time Criticality**:
  - does value decrease if we delay?
  - e.g., regulatory deadlines, market windows.
- **Risk Reduction / Opportunity Enablement**:
  - does this work reduce major risks?
  - does it enable valuable future options?

Teams often:

- score each dimension on a relative scale (e.g., 1–10),
- compute CoD and divide by size.

---

### 5. Risk‑Adjusted ROI (For Business Cases)

In enterprises/banks, you may already have:

- ROI, NPV, or IRR from the **business case** (see `4-business-case-roi` module).

You can:

- adjust these for **risk and uncertainty**,
- and use them alongside product prioritization frameworks.

Simple pattern:

- assign:
  - best case,
  - base case,
  - worst case,
  - probabilities (or confidence).
- compute **expected value**:

\[
\text{Expected Value} = p_{\text{best}} \times V_{\text{best}} + p_{\text{base}} \times V_{\text{base}} + p_{\text{worst}} \times V_{\text{worst}}
\]

Then:

- compare **expected value per unit effort** for initiatives.

This integrates:

- financial rigor with product thinking.

---

### 6. How to Combine Frameworks in Practice

In real organizations:

- you rarely use **only one** framework.

Common patterns:

1. Use **value vs effort** + **themed goals** for:
   - initial filtering and clustering.
2. Use **RICE or WSJF** at:
   - product/initiative level.
3. Use **risk‑adjusted ROI and portfolio constraints** for:
   - board/executive decisions.

Key is:

- consistency:
  - choose a simple approach,
  - apply it to all candidate initiatives in a cycle.

---

### 7. Example – Applying WSJF to SME Lending Initiatives

Suppose we have three initiatives:

- A: “Digital Application Experience v2”
- B: “Configurable Risk Rules Engine”
- C: “Operations Workbench Automation”

We score (1–10 scale):

| Initiative | Business Value | Time Criticality | Risk Reduction / Opportunity | CoD (sum) | Job Size | WSJF = CoD / Size |
|-----------|----------------|------------------|------------------------------|-----------|----------|-------------------|
| A         | 8              | 6                | 3                            | 17        | 5        | 3.4               |
| B         | 7              | 7                | 9                            | 23        | 8        | 2.9               |
| C         | 6              | 5                | 8                            | 19        | 4        | 4.75              |

Interpretation:

- C (Operations Workbench) has highest WSJF:
  - **large risk reduction/enablement** and small size.
- But:
  - we also consider strategic themes and regulatory commitments.

Outcome:

- we might:
  - start C and A early,
  - sequence B as a larger, medium‑term investment,
  - but still keep B high in the roadmap due to compliance risk.

---

### 8. Common Mistakes in Prioritization

- **Fake precision**:
  - assigning many decimal points to estimates that are mostly judgment.
- **Changing framework every quarter**:
  - teams cannot build intuition or trust.
- **Ignoring dependencies and enabling work**:
  - prioritizing features that cannot ship because platform work is missing.
- **Not including non‑feature work**:
  - technical debt, risk, and compliance work get squeezed out.

Mitigations:

- use **relative scoring**, not exact numeric prediction,
- keep the same basic framework for **at least a few cycles**,
- explicitly include:
  - platform work,
  - debt,
  - compliance,
  - and operational improvements in candidate lists.

---

### 9. How This Feeds the Roadmap

After scoring initiatives:

1. Create **ranked lists** per theme (see `05-strategic-themes-goals-and-okrs.md`).
2. Check **capacity and funding** (see `09-capacity-planning-and-funding-models.md`).
3. Sequence top items into:
   - near‑term committed roadmap,
   - mid‑term tentative roadmap,
   - longer‑term options.

The point is **not** to create a perfect ranking, but to:

- expose trade‑offs,
- choose a **small set of top bets**,
- and clearly show:
  - what is **in**,
  - what is **deferred**,
  - and **why**.

---

### Connections to Other Files

- `03-workflow.md` – where prioritization sits in the overall process.
- `05-strategic-themes-goals-and-okrs.md` – themes and goals used as inputs to prioritization.
- `09-capacity-planning-and-funding-models.md` – how prioritization interacts with capacity and budget.
- `22-best-practices.md` – good patterns for prioritization in large organizations.
- `23-common-mistakes.md` – anti‑patterns when using RICE, WSJF, etc.

