## 03 – When & When Not to Use an RFC

This file helps you decide **when an RFC is appropriate**, and when lighter‑weight approaches are enough.

---

### 1. Why This Matters

If you **over‑use** RFCs:

- people feel buried in process,
- decision‑making slows down,
- small changes become bureaucratic.

If you **under‑use** RFCs:

- important architectural decisions:
  - are taken informally,
  - are poorly documented,
  - are hard to defend in audits or incidents.

The goal is a **clear, agreed threshold** for when an RFC is required.

---

### 2. Typical Criteria for Requiring an RFC

Use criteria like these (adapt them to your org):

- **Impact scope**
  - affects **multiple teams or services**,
  - or a **core platform** or shared component.
- **Risk level**
  - introduces new:
    - security or privacy risks,
    - reliability or data integrity risks,
    - regulatory or legal exposure.
- **Irreversibility / Cost of Change**
  - decisions that will:
    - be hard or expensive to reverse later,
    - lock in technology or architecture choices.
- **Novelty**
  - new technologies or patterns for your organization,
  - major changes in data models or integration patterns.
- **Regulatory / Audit Visibility**
  - changes that:
    - must be explained to regulators,
    - or that materially change controls.

If **several** of these are true, you almost certainly need an RFC.

---

### 3. Examples That Usually Need an RFC

- designing a new core domain service (e.g., SME lending platform),
- replacing or modernizing a major legacy system,
- introducing a new data platform or event streaming backbone,
- changing critical risk models or rules engines,
- large cross‑cutting changes (e.g., new identity provider, encryption strategy),
- significant changes to data retention or logging for compliance.

---

### 4. Changes That Often Don’t Need a Full RFC

You can usually skip a full RFC for:

- **local, low‑risk refactors**:
  - internal code clean‑ups within a single service,
  - no change in external behaviours or NFRs.
- **small feature additions**:
  - that fit well within existing architecture,
  - and don’t materially change risk or compliance profile.
- **configurations**:
  - e.g., feature flags, simple rule tweaks, minor parameter changes,
  - as long as they follow existing patterns and controls.

These may still:

- require:
  - issue tracking,
  - code review,
  - test updates,
- but not a full RFC cycle.

---

### 5. Lightweight Alternatives to a Full RFC

For smaller or medium‑sized decisions, you might use:

- **Design notes or mini‑RFCs**:
  - short docs (1–3 pages) for:
    - small architectural choices,
    - significant but low‑risk refactors.
- **Architecture Decision Records (ADRs)**:
  - concise decision entries:
    - context, decision, consequences,
    - often stored in version control next to code.
- **Whiteboard / Miro Sessions with Notes**:
  - for non‑controversial, low‑risk design tweaks.

Rule of thumb:

- if multiple teams, risk/security, or regulators will care later:
  - lean towards a **full RFC**.

---

### 6. Defining Your Organization’s Policy

Agreement is key:

- architecture, security, risk, and delivery leadership should:
  - define,
  - document,
  - and socialize:
    - when RFCs are required,
    - who must review/approve them.

Examples of simple policy statements:

- “Any change that affects more than one product team or platform **must** go through an RFC.”
- “Any change that introduces a new external data processor **must** have an RFC including security and privacy review.”
- “New platform or data store introductions require RFC approval by the Architecture Board.”

---

### 7. Beginner Checklist

- [ ] Does this change:
  - [ ] affect multiple teams or systems?
  - [ ] introduce or significantly change NFRs (performance, security, availability)?
  - [ ] impact regulatory or audit requirements?
  - [ ] involve new technology or patterns for your org?
  - [ ] have high cost of reversal?
- [ ] If “yes” to several:
  - [ ] have you initiated an RFC with a clear scope and objectives?

If unsure, start a **short RFC outline** and review with an architect or senior engineer.

---

### Connections to Other Files

- `01-concepts.md` – explains RFCs and their role.
- `04-workflow.md` – what happens once you decide to create an RFC.
- `24-governance-review-and-lifecycle.md` – governance structures that enforce RFC policies.

