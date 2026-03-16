## 18 – Collaboration with Product & Requirements

This file explains how RFC authors **collaborate with product managers and requirements engineers** so proposals stay aligned with intent.

---

### 1. Why This Collaboration Is Critical

Risk if collaboration is weak:

- RFCs:
  - solve technical problems that are not the main business problems,
  - drift away from requirements and priorities,
  - create features that don’t map to clear outcomes.

Strong collaboration:

- ensures:
  - RFCs **implement strategy and requirements**, not replace them,
  - trade‑offs are understood in business terms.

---

### 2. Inputs from Product & Requirements

PMs/POs and BAs provide:

- problem statements and user context,
- goals, non‑goals, and metrics,
- PRDs and requirement specs,
- regulatory/business constraints,
- roadmap timings and dependencies.

RFCs should:

- reference these inputs explicitly,
- use them to structure context and goals.

---

### 3. Joint Scoping & Goal Setting

Before drafting:

- hold a short session with:
  - tech lead/architect,
  - PM/PO,
  - BA (if present).

Agree on:

- what the RFC is meant to decide,
- how success will be measured,
- scope boundaries (which parts of the PRD/roadmap it covers).

Document:

- shared understanding in the RFC’s:
  - context,
  - problem,
  - and goals sections.

---

### 4. Impact of Options on Product Outcomes

When comparing options:

- involve PM/PO:
  - to assess:
    - impact on time‑to‑market,
    - feature flexibility,
    - user experience,
    - commercial value.

Make sure:

- trade‑offs are expressed not only in:
  - technical terms,
  - but also in:
    - business and user impact.

---

### 5. Traceability Back to Requirements

RFCs should:

- reference:
  - requirement IDs (FRs/NFRs),
  - key PRD sections,
  - high‑level objectives/OKRs.

After acceptance:

- ensure:
  - requirements are updated if the RFC changes:
    - scope,
    - NFR assumptions,
    - or behaviour.

This keeps:

- **requirements and RFCs in sync**, not diverging.

---

### 6. Beginner Checklist

- [ ] Did product and requirements partners:
  - [ ] help define the RFC’s goals and scope?
  - [ ] review context/problem sections?
  - [ ] contribute to option trade‑off discussions?
- [ ] Are:
  - [ ] requirement IDs and objectives referenced in the RFC?
  - [ ] any requirement changes from the RFC reflected back in PRDs/specs?

If not, tighten the collaboration before concluding the RFC.

---

### Connections to Other Files

- `1-pre-development/6-product-strategy-roadmap` – upstream strategy and roadmap.
- `1-pre-development/7-requirements-engineering` – upstream requirements and NFRs.
- `11-roles-and-positions.md` – roles on both sides of this collaboration.

