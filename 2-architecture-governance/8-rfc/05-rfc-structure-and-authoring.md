## 05 – RFC Structure & Authoring

This file explains **how to structure and write** high‑quality RFCs / Technical Proposals.

It builds on the example structure shown in the README and adds detailed guidance.

---

### 1. Recommended RFC Structure (Overview)

A common RFC structure:

1. Metadata
2. Summary
3. Context & Problem Statement
4. Goals & Non‑Goals
5. Proposed Solution
6. Alternatives Considered
7. Architecture & Diagrams
8. Security, Compliance & Privacy
9. Operational Considerations
10. Migration / Rollout Plan
11. Risks & Open Questions
12. Decision & Approvals
13. Appendix

You can adapt this to your organization, but **keep the intent of each section**.

---

### 2. Section‑by‑Section Guidance

#### 2.1 Metadata

Purpose:

- make ownership, status, and relationships clear.

Include:

- RFC ID (e.g., RFC‑001),
- title,
- author(s) and owner,
- status (Draft, In Review, Accepted, Rejected, Superseded),
- created/updated dates,
- reviewers and approvers (names/roles),
- related documents (PRDs, feasibility, strategy, past RFCs).

Metadata enables:

- quick filtering and searching,
- governance and audit tracking.

---

#### 2.2 Summary

Purpose:

- provide a **1–3 paragraph overview**:
  - what is being proposed,
  - why,
  - and roughly how.

Audience:

- busy leaders,
- non‑technical stakeholders,
- reviewers scanning many RFCs.

Tips:

- avoid jargon where possible,
- state key value and risks clearly.

---

#### 2.3 Context & Problem Statement

Explain:

- business context:
  - drivers, goals, constraints,
  - link to strategy, roadmap, and requirements.
- technical context:
  - current architecture,
  - system and data landscape,
  - known pain points or limitations.
- problem statement:
  - why the current state is no longer sufficient,
  - what specific problems the proposal intends to solve.

This section prevents:

- jumping straight to solutions without alignment on the problem.

---

#### 2.4 Goals & Non‑Goals

Goals:

- what the proposal aims to achieve,
- tie back to:
  - business outcomes,
  - technical outcomes (e.g., resilience improvements).

Non‑Goals:

- explicitly out‑of‑scope items,
- clarifications about what **will not** be addressed by this RFC.

Examples:

- Goal:
  - “Enable SMEs to apply for loans online, with decisions available within 2 hours for simple cases.”
- Non‑Goal:
  - “This RFC does not address replacement of the core banking ledger.”

Non‑goals reduce:

- misaligned expectations,
- creep in review discussions.

---

#### 2.5 Proposed Solution

The core of the RFC:

- high‑level architecture:
  - main components and boundaries,
  - responsibilities and interactions.
- technology choices:
  - languages, frameworks, databases, messaging,
  - rationale vs alternatives.
- data model overview:
  - key entities,
  - data flows (not full schema).
- integrations:
  - which external systems are involved,
  - interfaces and data contracts.

Aim:

- enough detail to:
  - judge feasibility,
  - see trade‑offs,
  - plan design and implementation,
- but not full low‑level design (that comes later).

---

#### 2.6 Alternatives Considered

List and describe:

- at least one serious alternative (Option A, B, …),
- for each:
  - brief description,
  - pros and cons,
  - impact on:
    - cost,
    - time,
    - risk,
    - alignment with standards.

Conclude with:

- rationale for selecting the proposed solution.

This section:

- increases trust in the chosen option,
- helps future teams understand context if they revisit the decision.

---

#### 2.7 Architecture & Diagrams

Include or link to:

- logical architecture diagrams,
- deployment/topology diagrams,
- key sequence or flow diagrams.

Use:

- tools like `PlantUML`, `Draw.io`, `Miro`, `Lucidchart`.

Tips:

- keep diagrams:
  - simple enough to read,
  - focused on the aspects most relevant to the decision.
- label:
  - trust boundaries,
  - external dependencies,
  - critical paths.

---

#### 2.8 Security, Compliance & Privacy

Summarize:

- threat model:
  - key assets,
  - attacker types,
  - high‑level threats.
- data classification:
  - sensitive data involved,
  - storage and transit protections.
- compliance considerations:
  - relevant regulations and policies,
  - required controls and evidence.

Coordinate with:

- security architects,
- risk and compliance partners.

---

#### 2.9 Operational Considerations

Cover:

- scalability and performance expectations,
- availability and resilience strategies,
- monitoring and observability:
  - key metrics,
  - logs,
  - alerts.
- deployment and rollback strategies,
- backup and disaster recovery plans.

Coordinate with:

- SRE / ops teams,
- platform engineers.

---

#### 2.10 Migration / Rollout Plan

Explain:

- phasing:
  - pilot, limited rollout, full rollout,
- coexistence:
  - how new and old systems will run together (if needed),
- data migration:
  - approach, tools, risks,
- cutover:
  - big bang vs phased,
  - fallback strategies.

This section is crucial for:

- legacy modernization,
- regulatory changes,
- user‑facing migrations.

---

#### 2.11 Risks & Open Questions

List:

- known risks:
  - technical,
  - security,
  - compliance,
  - operational.
- mitigation ideas or next steps.
- open questions:
  - what remains to be decided,
  - who owns the answer.

This shows:

- honesty about uncertainties,
- plan for addressing them.

---

#### 2.12 Decision & Approvals

Include:

- decision summary:
  - accepted/rejected/superseded,
  - chosen option.
- approvers:
  - names/roles,
  - dates.
- any conditions:
  - e.g., “subject to successful POC,”
  - “requires security review of component X before production use.”

This is the **formal outcome** of the RFC.

---

#### 2.13 Appendix

Append any:

- detailed diagrams,
- PoC results and benchmarks,
- links to:
  - related ADRs,
  - external documentation,
  - standards and policies.

---

### 3. Authoring Tips (for Enterprises/Banks)

- write for:
  - mixed audience (technical and non‑technical),
  - use plain language where possible.
- be honest about:
  - trade‑offs,
  - risks,
  - unknowns.
- avoid:
  - unnecessary detail that hides the main arguments,
  - copying large chunks from other docs (link instead).
- iterate:
  - share early drafts,
  - incorporate feedback,
  - track major changes.

---

### Connections to Other Files

- `01-concepts.md` and `02-objectives.md` – why this structure exists and what it must achieve.
- `04-workflow.md` – where RFC authoring fits in the overall process.
- `06-option-analysis-and-tradeoffs.md` – deeper guidance on comparing solution options.
- `25-templates.md` – concrete RFC templates you can copy and adapt.

