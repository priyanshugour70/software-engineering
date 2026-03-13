## 21 – Real-World Style Examples (Micro-Scenarios)

Short scenarios illustrating specific Feasibility moves.

We cover:

- A. Discovering an integration blocker early
- B. Phasing scope due to operations constraints
- C. Adjusting solution due to regulatory limits

---

### A. Discovering an Integration Blocker Early

Context:

- plan to expose real‑time balances in a new SME mobile app.

During Feasibility:

- architecture team discovers:
  - core system only supports:
    - overnight batch updates,
    - with no real‑time API for balances.

Implication:

- full real‑time balances across all accounts **not feasible** without:
  - major core modernization.

Action:

- adjust scope to:
  - near real‑time for subset of accounts where streaming is available,
  - or cached views with clear refresh indicators.
- include:
  - core modernization as a longer‑term enabler.

Outcome:

- prevents:
  - committing to impossible SLAs,
  - late surprise during implementation.

---

### B. Phasing Scope Due to Operations Constraints

Context:

- new SME lending process will:
  - increase application volume,
  - change back‑office workflows.

Feasibility findings:

- ops team:
  - already at capacity with other transformation programs,
  - can only absorb limited change.

Action:

- propose:
  - phased rollout:
    - start with a smaller segment and loan size band,
    - gradually expand once:
      - new processes bed in,
      - staffing is adjusted.

Outcome:

- initiative proceeds with:
  - realistic ops impact,
  - lower risk of service degradation.

---

### C. Adjusting Solution Due to Regulatory Limits

Context:

- initial idea:
  - fully automated loan approvals for all SME segments.

Legal/compliance review:

- reveals:
  - for certain exposures or high‑risk segments,
  - manual review is mandated or strongly expected by regulators.

Action:

- Feasibility:
  - redefines solution:
    - automated decisions for:
      - low‑risk, existing SMEs within limits,
    - manual or augmented review for others.
- Business case:
  - updated:
    - benefits from automation reduced accordingly,
    - risk benefits clarified.

Outcome:

- feasible, compliant solution,
- with clear boundaries of automation.

---

### Connections to Other Files

- `07-legal-and-regulatory-feasibility.md` – example C relies on this.
- `06-operational-feasibility.md` – example B shows ops capacity constraints.
- `05-technical-feasibility.md` – example A is a classic integration limitation.

