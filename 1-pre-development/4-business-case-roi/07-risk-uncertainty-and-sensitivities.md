## 07 – Risk, Uncertainty & Sensitivities

This file explains how to handle **uncertainty** in business cases instead of pretending forecasts are exact.

We cover:

- A. Types of uncertainty
- B. Scenario analysis
- C. Sensitivity analysis
- D. Practical examples

---

### A. Types of Uncertainty

1. **Adoption & Usage Uncertainty**
   - Will users actually adopt and use the solution at the expected rate?
2. **Conversion & Performance Uncertainty**
   - Will conversion, approval, or risk metrics improve as much as assumed?
3. **Cost & Timeline Uncertainty**
   - Will build or run costs exceed estimates?
   - Will delivery be delayed?
4. **External Environment Uncertainty**
   - Market conditions, interest rates, regulations, competition.

You cannot remove these uncertainties, but you can **explicitly model** their impact.

---

### B. Scenario Analysis

**Idea:** Build a few **plausible scenarios** with different assumptions.

Typical set:

- **Conservative** (or downside)
  - lower adoption or slower rollout,
  - smaller performance improvements,
  - higher costs.
- **Base**
  - your best judgment of “most likely”.
- **Aggressive** (or upside)
  - faster adoption,
  - stronger performance improvements,
  - on‑time/on‑budget costs.

For each scenario:

- calculate:
  - ROI,
  - payback,
  - NPV,
  - and key KPI targets.

Present:

- ranges and narratives:
  - “If adoption stalls, ROI drops to X and payback extends to Y.”

---

### C. Sensitivity Analysis

**Idea:** Vary **one driver at a time** to see which ones matter most.

Steps:

1. Identify key drivers:
   - e.g., adoption rate, conversion uplift, average revenue per unit, implementation cost.
2. For each driver:
   - vary it by a certain % (e.g., ±10%, ±20%),
   - keep others constant,
   - observe the effect on ROI/NPV/payback.
3. Summarize:
   - which drivers have the **largest impact**,
   - where additional research or mitigation would help most.

This is sometimes visualized as a **tornado chart** (largest impact at top).

---

### D. Practical Example (SME Lending)

Assume:

- baseline NPV in base case = 10M.
- key drivers:
  - A: adoption rate by year 3,
  - B: approval conversion uplift,
  - C: implementation cost.

Sensitivity results:

- A (adoption ±20%):
  - NPV range: 6M–14M.
- B (conversion uplift ±20%):
  - NPV range: 7M–13M.
- C (cost ±20%):
  - NPV range: 9M–11M.

Insights:

- adoption and conversion are much more critical to value than moderate cost overruns.
- focusing on:
  - **go‑to‑market, UX, and change management** (to ensure adoption),
  might be more important than shaving 10–15% off build cost.

---

### E. How to Present Risk & Uncertainty

- Avoid:
  - single‑point “precise” numbers without ranges.
- Use:
  - tables and simple charts,
  - narrative descriptions:
    - “Most of the upside/downside comes from X and Y assumptions.”
- Clearly list:
  - what you consider **out of scope** for modeling (e.g., macroeconomic shifts beyond a simple scenario).

This builds **trust** and helps leaders make **informed trade‑offs**.

---

### Connections to Other Files

- `05-benefit-types-and-estimation.md` / `06-cost-types-and-estimation.md` – inputs that are subject to uncertainty.
- `04-financial-metrics-and-formulas.md` – metrics you stress under scenarios.
- `21-common-mistakes.md` – includes pitfalls like ignoring uncertainty or hiding downside cases.

