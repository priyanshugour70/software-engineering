## 20 – Case Studies: End‑to‑End Feasibility Studies

These constructed case studies show how Feasibility is performed from **intake to recommendations**.

We cover:

- Case Study 1: Digital SME Lending Feasibility
- Case Study 2: Cross‑Border Payments Platform Upgrade

---

### Case Study 1 – Digital SME Lending Feasibility

#### Context

- Business case approved for:
  - digital SME lending for existing customers in Country X.
- Goals:
  - faster decisions,
  - more volume,
  - reduced manual processing.

#### Stage 1 – Intake & Scoping

Feasibility charter:

- scope:
  - SME term loans 50k–500k in Country X,
  - existing customers only,
  - digital application with near real‑time decisions.
- timebox:
  - 6 weeks.
- working group:
  - architecture lead, PM, SME ops lead,
  - security, compliance, risk, data, platform.

#### Stage 2 – Baseline Understanding

Findings:

- core lending system:
  - batch‑oriented, approvals via back‑office queue.
- data:
  - rich transactional data in data warehouse,
  - some latency for risk models.
- operations:
  - manual underwriting for all SME loans,
  - strong dependence on relationship managers.
- regulation:
  - allows automated decisions within certain parameters,
  - specific rules for larger exposures and higher‑risk segments.

#### Stage 3 – Option Exploration

Shortlisted options:

1. **Option A** – wrap existing core with API gateway, keep underwriting mostly manual.
2. **Option B** – introduce a new decisioning engine using existing data warehouse.
3. **Option C** – use vendor credit decisioning platform integrated with core.

#### Stage 4 – Deep‑Dive Feasibility

Technical:

- Option A:
  - simpler tech, but still slow and manual for most cases.
- Option B:
  - requires:
    - near real‑time data integration,
    - new risk model development.
- Option C:
  - integration with vendor APIs,
  - data residency and secrecy concerns.

Operational:

- Option A:
  - ops largely unchanged,
  - no major run‑model change.
- Option B:
  - new split between:
    - fully automated,
    - manual exception handling.
- Option C:
  - similar to B but with vendor run‑time dependency.

Security & Privacy:

- Option B:
  - internal data and models,
  - fits existing controls.
- Option C:
  - requires secure data exchange with vendor,
  - additional due diligence and contracts.

Legal & Regulatory:

- all options:
  - must respect lending rules,
  - but B and C allow:
    - clearer differentiation between low‑risk automated decisions and manual reviews.

Organizational:

- Option B & C:
  - require:
    - new skills in risk modeling and monitoring,
    - change management for ops and relationship managers.

#### Stage 5 – Risk Register & Recommendations

Key risks:

- risk model performance (B, C),
- integration and latency issues (B, C),
- vendor lock‑in and data transfer risk (C),
- change fatigue in branches/ops.

Recommendations:

- choose a **phased Option B**:
  - internal decision engine,
  - limited to specific SME segments and exposures initially.
- prerequisites:
  - enable near real‑time data feeds,
  - build monitoring for model and process performance.

#### Stage 6 – Review & Handover

Feasibility report:

- submitted to:
  - architecture board,
  - SME steering committee,
  - risk committee.

Outcome:

- solution direction endorsed,
- enabler work streams:
  - data integration,
  - risk model development,
  - operations change design,
are added to roadmap.

---

### Case Study 2 – Cross-Border Payments Platform Upgrade

#### Context

- need:
  - faster, more transparent cross‑border payments for SMEs.
- Business case:
  - improve speed and tracking,
  - reduce errors and manual investigations.

#### Feasibility Highlights

Technical:

- existing:
  - SWIFT‑based flows,
  - limited tracking capabilities.
- options:
  - adopt SWIFT gpi,
  - integrate with regional instant payment schemes,
  - partner with fintech provider for corridors.

Operational:

- current:
  - manual investigation of delayed/failed payments,
  - limited customer self‑service.
- to‑be:
  - new dashboards for ops,
  - new customer‑facing status tracking,
  - changed workflows for exception handling.

Legal & Regulatory:

- cross‑border regulations,
- FX rules,
- sanctions screening,
must be maintained or improved.

Security & Privacy:

- cross‑border data transfers:
  - must respect data protection and banking secrecy rules.

Outcome:

- Feasibility recommends:
  - phased adoption of SWIFT gpi for main corridors,
  - internal upgrades for status tracking,
  - exploration of instant schemes where feasible.

Risks:

- vendor/scheme adoption timelines,
- differing local regulatory requirements.

Recommendations:

- treat as:
  - multi‑year program with corridor‑by‑corridor feasibility slices,
  - each with its own feasibility review.

---

### Connections to Other Files

- `03-workflow.md` – stage mapping for each case.
- `22-risk-register-and-mitigation.md` – risk register examples in these scenarios.
