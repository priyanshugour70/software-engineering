## 04 – Financial Metrics & Formulas (Beginner-Friendly)

This file explains common **financial metrics** used in business cases, in simple terms.

We cover:

- A. ROI
- B. Payback period
- C. NPV
- D. IRR

> These are conceptual explanations. For exact formulas, you’ll typically use Excel/Sheets functions.

---

### A. ROI – Return on Investment

**Idea:** How much net benefit do we get relative to what we invest?

Simplified formula over a period:

- \( \text{ROI} = \frac{\text{Total Benefits} - \text{Total Costs}}{\text{Total Costs}} \)

Example:

- Over 3 years:
  - Total additional revenue + cost savings = 10M,
  - Total project + running costs = 4M.
- ROI = (10M − 4M) / 4M = 6M / 4M = **150%**.

Use:

- quick, intuitive comparison between initiatives.

Limitations:

- doesn’t show **time profile** (benefits late vs early),
- ignores **time value of money**.

---

### B. Payback Period

**Idea:** How long until cumulative benefits equal cumulative costs?

Steps:

1. List cash flows by year (or quarter).
2. Calculate cumulative net cash flow.
3. Find the point where it turns from negative to zero/positive.

Example:

- Year 0: −2M (investment),
- Year 1: +0.5M,
- Year 2: +1.0M,
- Year 3: +1.0M,
- Cumulative:
  - end Y0: −2.0M
  - end Y1: −1.5M
  - end Y2: −0.5M
  - end Y3: +0.5M
- Payback ≈ somewhere during **Year 3**.

Use:

- simple way to assess **speed of return**.

Limitations:

- ignores:
  - benefits after payback,
  - time value of money,
  - risk differences.

---

### C. NPV – Net Present Value

**Idea:** Future money is worth **less than money today**. NPV discounts future cash flows back to today.

Concept:

- Pick a **discount rate** (e.g., 8–12%) reflecting:
  - cost of capital,
  - risk.
- For each future period:
  - divide the cash flow by \( (1 + r)^t \),
    - where \( r \) = discount rate,
    - \( t \) = number of periods (years).

Simplified example:

- Discount rate \( r = 10\% \).
- Cash flows:
  - Year 0: −2M,
  - Year 1: +1M,
  - Year 2: +1.5M,
  - Year 3: +1.5M.

Present values:

- PV(Y0) = −2.0M
- PV(Y1) = 1.0M / 1.1 ≈ 0.91M
- PV(Y2) = 1.5M / 1.1² ≈ 1.24M
- PV(Y3) = 1.5M / 1.1³ ≈ 1.13M

NPV = sum of all PVs:

- ≈ −2.0 + 0.91 + 1.24 + 1.13 = **1.28M**.

If NPV > 0 at the chosen discount rate:

- project is financially attractive *under that set of assumptions*.

---

### D. IRR – Internal Rate of Return

**Idea:** IRR is the **discount rate** at which NPV = 0.

Interpretation:

- if IRR is:
  - above your organization’s **hurdle rate** (e.g., 12–15%),
  - the project is attractive.

In practice:

- you use built‑in functions (e.g., `IRR` in Excel),
- you rarely compute it by hand.

Use:

- compare:
  - the “effective return” of different projects,
  - independent of absolute scale (though scale still matters).

Limitations:

- can be misleading for:
  - non‑conventional cash flows (multiple sign changes),
  - very long horizons.
- should be considered alongside:
  - NPV,
  - payback,
  - risk profile.

---

### How to Use These Metrics Together

- For **smaller or simpler** initiatives:
  - focus on:
    - ROI,
    - payback,
    - basic scenario ranges.
- For **larger, multi‑year** investments:
  - include:
    - NPV,
    - IRR,
    - scenario and sensitivity analysis.

Always:

- pair metrics with:
  - clear assumptions,
  - scenario commentary,
  - qualitative strategic rationale.

---

### Connections to Other Files

- `03-workflow.md` – Stage 4 uses these metrics.
- `05-benefit-types-and-estimation.md` / `06-cost-types-and-estimation.md` – feed the cash‑flow inputs.
- `07-risk-uncertainty-and-sensitivities.md` – builds on these metrics under uncertainty.

