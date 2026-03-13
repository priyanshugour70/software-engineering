## 22 – Risk Register & Mitigation

This file provides a structure for capturing **risks, constraints, and mitigations** uncovered during Feasibility.

We cover:

- A. Risk register structure
- B. Constraint log structure
- C. Practical tips

---

### A. Risk Register Structure

Suggested columns:

| ID | Category | Description | Likelihood | Impact | Owner | Mitigation / Response | Status |
|----|----------|------------|------------|--------|-------|------------------------|--------|

- **Category**
  - technical, operational, security, legal/regulatory, organizational, vendor, other.
- **Likelihood**
  - low / medium / high (or numeric).
- **Impact**
  - low / medium / high (or numeric) – often consider:
    - cost,
    - delay,
    - customer impact,
    - regulatory impact.
- **Owner**
  - person or team responsible for monitoring and mitigation.
- **Mitigation / Response**
  - actions to:
    - reduce likelihood or impact,
    - or accept/transfer risk with rationale.
- **Status**
  - open, mitigated, accepted, transferred, closed.

Example entry:

| ID | Category   | Description                                      | Likelihood | Impact | Owner        | Mitigation / Response                               | Status |
|----|------------|--------------------------------------------------|------------|--------|-------------|------------------------------------------------------|--------|
| R1 | Technical  | Real-time data feed from core not yet available | Med        | High   | Arch Lead   | Deliver core data-streaming enabler before MVP; use fallback cache for some flows | Open   |

---

### B. Constraint Log Structure

Suggested columns:

| ID | Type (Hard/Soft) | Description | Source (Policy/System/Regulation) | Affected Options | Potential Remediation |
|----|------------------|------------|-----------------------------------|------------------|-----------------------|

- **Hard constraints**
  - cannot be broken (e.g., legal requirements, non‑negotiable technical limits).
- **Soft constraints**
  - can be revisited or adjusted with:
    - approvals,
    - additional work,
    - or compensating controls.

Example:

| ID | Type | Description                                           | Source           | Affected Options        | Potential Remediation                    |
|----|------|-------------------------------------------------------|------------------|-------------------------|-------------------------------------------|
| C1 | Hard | Certain high-risk SME segments must have manual review| Lending policy   | Fully automated option  | Split solution: auto for low-risk, manual for others |

---

### C. Practical Tips

- Maintain the risk register and constraint log as **living artifacts**:
  - start in Feasibility,
  - continue updating during design and delivery.
- Use them in:
  - architecture and risk committees,
  - design reviews,
  - go/no‑go discussions.
- Avoid:
  - overly long lists with no ownership,
  - or vague risks like “technical risk” with no details.

---

### Connections to Other Files

- `03-workflow.md` – Stage 5 produces/updates these artifacts.
- `23-best-practices.md` / `24-common-mistakes.md` – guidance on effective risk management.

