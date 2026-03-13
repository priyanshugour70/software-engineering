## 06 – Cost Types & Estimation

This file explains **what costs to include** in a business case and how to estimate them.

We cover:

- A. Cost categories
- B. Estimation approaches
- C. Example breakdowns

---

### A. Cost Categories

#### 1. Build / One-Time Costs

- **Product & Engineering**
  - development,
  - design,
  - QA/testing,
  - architecture and security review.
- **Integrations**
  - connecting to:
    - core systems,
    - third‑party services (KYC, credit bureaus, fraud tools),
    - channels.
- **Infrastructure Setup**
  - new environments,
  - capacity expansion,
  - new platforms (e.g., middleware).
- **Change & Training**
  - creating training materials and running sessions,
  - updating processes and SOPs,
  - internal communications.

---

#### 2. Run / Ongoing Costs

- **Technology Operations**
  - cloud or hosting fees,
  - licenses and subscriptions,
  - monitoring and observability,
  - backups and resilience testing.
- **Support & Service**
  - customer support effort,
  - operational support (back‑office, specialists),
  - incident handling and maintenance.
- **Vendor & Partner**
  - per‑transaction or monthly fees (e.g. KYC providers),
  - usage‑based pricing.
- **Compliance & Risk**
  - periodic audits,
  - additional monitoring,
  - reporting changes.

---

#### 3. Indirect / Shared Costs (Handle Carefully)

- Platform investments that benefit multiple initiatives.
- Shared services (security, compliance, infrastructure teams).

Approach:

- in some orgs:
  - these are handled centrally,
  - business cases focus on **incremental direct costs**.
- in others:
  - a portion is allocated per initiative.

Clarify with finance how to treat them.

---

### B. Estimation Approaches

#### 1. Bottom-Up Estimation (When Feasible)

Work with:

- engineering,
- operations,
- vendors,

to estimate:

- person‑months,
- story points or sprint counts,
- infrastructure capacity needs.

Convert:

- person‑months to cost using internal blended rates,
- capacity to cost using existing cloud/license pricing.

Strength:

- detail and transparency.

Limitation:

- can be time‑consuming,
- less accurate early in discovery.

---

#### 2. Top-Down Estimation (Early Stages)

Use:

- analogy to similar past initiatives,
- high‑level complexity assessments.

For example:

- “This looks like ~70–100% of the effort we spent on Digital Onboarding v1.”

Strength:

- quick and useful when detailed scoping isn’t done.

Limitation:

- more uncertainty; must be labeled accordingly.

---

#### 3. Phased Estimation

Break initiative into:

- **Phase 1 – MVP**,
- **Phase 2 – Scale Out**, etc.

Estimate:

- costs per phase,
- enabling:
  - stage‑gated funding,
  - iterative re‑evaluation.

---

### C. Example Cost Breakdown (Digital SME Lending)

Assume a 3‑year horizon; all numbers illustrative.

#### 1. Build Costs (Year 0–1)

- Product & Engineering:
  - ~12 FTE for 12 months,
  - cost per FTE/year (blended): 150k,
  - ≈ 12 × 150k = 1.8M.
- Design & Research:
  - ~3 FTE for 12 months = 0.45M.
- Integrations:
  - one‑off vendor fees, implementation = 0.3M.
- Change & Training:
  - training materials, branch sessions = 0.15M.

Total build ≈ **2.7M**.

---

#### 2. Run Costs (Annual)

- Cloud & Infra:
  - additional compute, storage, networking for new flows = 0.2M/year.
- Vendor Fees:
  - credit bureau and KYC checks (incremental volume) = 0.25M/year.
- Support & Ops:
  - small uplift in operational oversight (after automation) = 0.1M/year.

Total run ≈ **0.55M per year**.

---

#### 3. Phased Example

- **Phase 1 (Pilot in Country X)**:
  - smaller build scope,
  - lower run costs,
  - helps validate assumptions.
- **Phase 2 (Scale to additional countries/segments)**:
  - incremental costs,
  - incremental benefits.

The business case should:

- separate these,
- show:
  - option to continue or stop after Phase 1.

---

### Connections to Other Files

- `05-benefit-types-and-estimation.md` – for value side of the model.
- `09-data-sources.md` – where to get historical cost and volume info.
- `03-workflow.md` – Stage 3 relies on these concepts.

