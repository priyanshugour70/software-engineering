## 19 – Option & Risk Trade-Offs

This file focuses on comparing **solution options** from a feasibility and risk perspective.

We cover:

- A. Types of options
- B. Trade‑off dimensions
- C. Example comparison (build vs buy vs partner)

---

### A. Types of Options

Common option axes:

- **Scope**
  - minimal vs full feature set,
  - limited segments vs all segments.
- **Technology**
  - reuse vs new build,
  - on‑prem vs cloud,
  - internal platform vs vendor product.
- **Rollout**
  - pilot vs big‑bang,
  - single region vs multi‑region.

Each option changes:

- technical complexity,
- operational impact,
- regulatory exposure,
- risk profile.

---

### B. Trade-Off Dimensions

When comparing options, consider:

- **Feasibility**
  - technical and operational complexity,
  - alignment with standards and constraints.
- **Risk**
  - delivery risk,
  - operational and security risk,
  - regulatory risk.
- **Cost**
  - build and run costs,
  - vendor and licensing costs.
- **Time to value**
  - how quickly usable value can be delivered.
- **Flexibility**
  - ability to adapt or extend in future,
  - vendor lock‑in.

Use:

- option comparison tables,
- qualitative scoring (e.g., 1–5),
- clear pros/cons narratives.

---

### C. Example – Build vs Buy vs Partner

Context:

- need a fraud detection capability for digital SME lending.

**Option A – Build In-House**

- Pros:
  - full control over models and data,
  - better integration with internal systems.
- Cons:
  - high engineering and data science effort,
  - slow time‑to‑value,
  - need to maintain and update models.
- Risks:
  - model performance,
  - skills and capacity availability.

**Option B – Buy Vendor Product**

- Pros:
  - faster time‑to‑market,
  - pre‑built controls and patterns,
  - external expertise.
- Cons:
  - licensing and per‑transaction costs,
  - integration complexity,
  - vendor lock‑in.
- Risks:
  - vendor reliability and roadmap,
  - data sharing and residency.

**Option C – Partner (Hybrid)**

- Pros:
  - leverage vendor for core capabilities,
  - maintain some internal models or logic for critical areas.
- Cons:
  - integration and coordination complexity,
  - may inherit downsides of both build and buy if not well designed.

Feasibility & Risk view:

- A might be:
  - more technically flexible but:
    - high delivery risk.
- B might be:
  - most feasible short‑term but:
    - higher vendor and data risks.
- C might:
  - balance:
    - feasibility, risk, and long‑term control.

Decision approach:

- often start with:
  - B or C for early value and risk reduction,
  - while evaluating whether A becomes attractive long‑term.

---

### Connections to Other Files

- `05-technical-feasibility.md` / `06-operational-feasibility.md` – core inputs to option comparisons.
- `18-startup-vs-enterprise.md` – option preferences differ by context.

