## 10 – Documents & Artifacts around RFCs

This file lists the **key documents and artifacts** that sit around RFCs and how they relate.

---

### 1. Core RFC Document

**Purpose**

- capture:
  - context, options, decision,
  - security/compliance and operational considerations.

**Owner**

- usually a senior engineer / tech lead or architect.

**Where**

- wiki (`Confluence`, `Notion`, etc.),
- or repo (Markdown RFCs).

**Connections**

- links to:
  - PRDs / requirements,
  - feasibility studies,
  - architecture design docs,
  - backlog items,
  - security and risk artefacts.

---

### 2. Architecture Decision Records (ADRs)

**Purpose**

- short, focused records of **individual decisions**, often derived from or attached to RFCs.

Typical ADR structure:

- context,
- decision,
- consequences,
- date and authors.

Where:

- usually in code repos under `/docs/adr` or similar.

Relation to RFCs:

- RFC:
  - broader proposal & options.
- ADR:
  - precise decision snippet referencing the RFC.

---

### 3. Design & Specification Documents

After an RFC is accepted:

- more detailed docs are often produced:
  - component‑level designs,
  - API specifications,
  - data model specs.

RFC should:

- **link to** these downstream documents,
- not try to replace them.

These live:

- in architecture/design repos,
- or specific documentation spaces per system.

---

### 4. Security, Risk & Compliance Artifacts

Examples:

- threat models,
- security review reports or tickets,
- privacy impact assessments,
- risk assessment and sign‑off records.

RFCs should:

- reference:
  - IDs of these artefacts,
  - key conclusions or conditions.

Later phases (`10-security-review`, `11-compliance-risk`) deepen this work, but the RFC is often the **starting point**.

---

### 5. Implementation & Tracking Artifacts

Artifacts:

- epics and stories in the backlog,
- tasks in engineering boards,
- work breakdown structures for programs.

Best practice:

- link epics to RFC IDs,
- annotate RFCs with:
  - core epics implementing the decision,
  - status summaries for major workstreams.

This provides:

- visibility from:
  - decision → delivery,
  - and delivery → underlying decision.

---

### 6. Operational & Runbook Artifacts

Over time, RFCs should be connected to:

- runbooks for incidents and operations,
- monitoring dashboards and alerts,
- SLO/SLA definitions.

While these may not exist at RFC time:

- RFCs can:
  - define **requirements** for them (e.g., what must be monitored),
  - list them as follow‑up items in risks or action lists.

---

### 7. Indexes & Catalogues

For larger organisations:

- maintain:
  - an **RFC catalogue**:
    - ID,
    - title,
    - status,
    - domain/system,
    - link.
  - optionally a **decision catalogue**:
    - key architecture decisions with links to RFCs/ADRs.

Benefits:

- quickly find:
  - related RFCs when starting a new proposal,
  - decisions impacting a system during incidents or audits.

---

### 8. Beginner Checklist

- [ ] For each major initiative, do we have:
  - [ ] at least one RFC?
  - [ ] related ADRs for specific decisions?
- [ ] Are there:
  - [ ] links between RFCs and design docs?
  - [ ] links between RFCs and security/risk artefacts?
  - [ ] links between RFCs and implementation tickets?
- [ ] Do we:
  - [ ] maintain an index of RFCs and their status?

If not, start with a simple **RFC index page** and gradually connect documents and artefacts around each RFC.

---

### Connections to Other Files

- `05-rfc-structure-and-authoring.md` – what goes into the core RFC.
- `08-security-compliance-and-risk-in-rfcs.md` – security and risk artefacts connected to RFCs.
- `24-governance-review-and-lifecycle.md` – how governance uses and updates these artefacts over time.

