## 17 – Regulated vs Unregulated Products

This file explains how **regulation intensity** changes Requirements Engineering.

We contrast:

- heavily regulated products (e.g., banking, lending, payments, insurance),
- less regulated or unregulated products.

---

### 1. What “Regulated” Means for Requirements

In regulated domains, requirements must:

- reflect:
  - laws and regulatory guidance,
  - internal risk and compliance policies,
  - model risk and governance standards.
- enable:
  - audits,
  - supervisory reviews,
  - evidence that controls work.

This affects:

- the **content** of requirements,
- the **rigour** of documentation and traceability,
- the **review and sign‑off** processes.

---

### 2. Impact on Requirements Content

For regulated products:

- PRDs and NFRs often include:
  - specific policy references,
  - control descriptions,
  - logging and retention rules,
  - constraints on data usage and sharing.

Examples (lending):

- representing:
  - eligibility rules,
  - credit decision criteria,
  - affordability checks,
  - required disclosures to customers.

NFRs:

- include:
  - auditability requirements,
  - retention periods,
  - segregation of duties,
  - strong access controls.

---

### 3. Impact on Traceability

Regulated environments:

- often require:
  - traceability from:
    - regulations and policies → requirements → implementations → tests → operational evidence.

Implications:

- stronger need for:
  - requirement IDs,
  - traceability tables or ALM tools,
  - versioning and baselining.

Auditors may ask:

- “Show me how requirement R (from regulator/policy) is implemented and tested.”

Your Requirements Engineering approach should:

- make it straightforward to answer that.

---

### 4. Impact on Reviews & Sign‑Off

In regulated products:

- requirements (especially those tied to risks/controls) often require:
  - review and input from:
    - risk,
    - compliance,
    - legal,
    - sometimes internal audit.

Formal sign‑offs may be needed:

- for PRDs,
- for NFRs,
- for certain changes in scope or design.

Your process should:

- plan time and cadence for these,
- avoid last‑minute surprises.

---

### 5. Less Regulated / Unregulated Products

These products still:

- need to respect:
  - generic consumer protection,
  - data protection,
  - contract and IP laws.

But often:

- fewer specialized regulations,
- fewer mandated controls,
- more flexibility in how requirements and docs are structured.

You can:

- keep documentation lighter,
- still apply:
  - good NFR thinking,
  - basic traceability for critical areas (security, billing, data).

---

### 6. Beginner Checklist

- [ ] Is your product:
  - [ ] heavily regulated,
  - [ ] moderately regulated,
  - [ ] lightly regulated?
- [ ] Have you:
  - [ ] identified which specific regulations and policies impact requirements?
  - [ ] involved risk/compliance early enough?
  - [ ] ensured NFRs for auditability and controls are captured where needed?
- [ ] Do you:
  - [ ] have at least lightweight traceability for regulatory‑driven requirements?

If not, strengthen your Requirements Engineering approach along these lines.

---

### Connections to Other Files

- `07-non-functional-requirements.md` – many regulatory concerns surface as NFRs.
- `08-traceability-and-documentation.md` – mechanisms to provide audit‑ready traceability.
- `24-governance-and-change-control.md` – forums and processes where regulatory requirements are reviewed.

