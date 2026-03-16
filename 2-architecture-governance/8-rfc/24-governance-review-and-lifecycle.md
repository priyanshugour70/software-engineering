## 24 – Governance, Review & Lifecycle of RFCs

This file explains how RFCs are **governed over time**: who reviews them, how decisions are made, and how their lifecycle is managed.

---

### 1. RFC Lifecycle States

Common states:

- **Draft** – being written; open to major change.
- **In Review** – shared with reviewers; under active discussion.
- **Accepted** – decision made to adopt the proposal (maybe with conditions).
- **Rejected** – decision not to adopt the proposal.
- **Superseded** – replaced by a newer RFC.

RFCs should:

- clearly display their current state and transitions,
- note:
  - when state changed,
  - by whom.

---

### 2. Review & Decision Forums

Forums depend on organisation size and risk profile, e.g.:

- **Team/Domain Tech Reviews**
  - for local or medium‑impact RFCs.
- **Architecture Board / Design Authority**
  - for cross‑domain or high‑impact changes.
- **Security & Risk Committees**
  - for proposals affecting security posture or regulatory exposure.

Each forum should define:

- which RFCs it sees (criteria),
- who decides,
- how decisions are recorded.

---

### 3. Integrating RFCs with Portfolio & Roadmap Governance

Significant RFCs:

- may influence:
  - scope,
  - timelines,
  - capacity,
  - and risk posture of initiatives.

Ensure:

- accepted RFCs:
  - are reflected in:
    - roadmap updates,
    - capacity and funding decisions,
    - risk registers.

Coordinate with:

- portfolio and roadmap forums from `6-product-strategy-roadmap`.

---

### 4. Change Management for Accepted RFCs

After acceptance:

- changes may still occur:
  - due to new constraints,
  - experiments,
  - incidents,
  - regulatory shifts.

Options:

- **Minor changes**:
  - update existing RFC with:
    - “Change Log” section,
    - date, description, approver.
- **Major changes**:
  - create a new RFC that:
    - references the old one,
    - marks it as Superseded,
    - explains why direction changed.

Governance:

- for big shifts:
  - take new RFC through the same review/decision forums.

---

### 5. Archiving & Discoverability

- maintain:
  - an index of all RFCs:
    - ID, title, status, domain, date.
- archive:
  - Rejected and Superseded RFCs in a clear section,
  - but keep them accessible for:
    - audits,
    - historical analysis,
    - avoiding repeated mistakes.

Search:

- ensure RFCs are:
  - searchable by:
    - system name,
    - key technologies,
    - domain,
    - regulatory tag.

---

### 6. Beginner Checklist

- [ ] Do RFCs:
  - [ ] have clear states and transitions?
  - [ ] show who approved them and when?
- [ ] Are there:
  - [ ] defined forums that review and decide on RFCs?
  - [ ] clear criteria for which RFCs go where?
- [ ] Are:
  - [ ] superseded and rejected RFCs archived but still findable?
  - [ ] accepted RFCs integrated into roadmap and risk views?

If not, refine governance and lifecycle rules so RFCs become a **reliable decision backbone**, not just documents.

---

### Connections to Other Files

- `04-workflow.md` – RFC stages that this governance wraps around.
- `22-best-practices.md` and `23-common-mistakes.md` – governance as an enabler for quality.
- `2-architecture-governance/README.md` – how RFC governance fits in the broader architecture & governance macro‑phase.

