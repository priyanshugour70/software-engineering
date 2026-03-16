## 09 – Tools for RFCs & Technical Proposals

This file explains the **tooling ecosystem** around RFCs: where to write them, how to review them, and how to integrate them with code, tickets, and governance.

---

### 1. Authoring & Collaboration Tools

Purpose:

- write and iterate on RFC documents,
- collect comments and suggestions,
- version and archive accepted RFCs.

Common choices:

- **Docs & Wikis**
  - `Confluence`, `Notion`, `Google Docs`, `SharePoint`.
- **Version‑Controlled Markdown**
  - RFCs as `*.md` files in Git repos (common in engineering‑led orgs).

Best practices:

- use:
  - a **single primary home** for RFCs per domain,
  - standard templates (`25-templates.md`).
- require:
  - clear naming and IDs (e.g., `RFC-001-digital-sme-lending-platform`),
  - status labels (Draft, In Review, Accepted, Superseded).
- enable:
  - inline comments,
  - change tracking or PR reviews.

---

### 2. Review & Commenting Workflows

Tools:

- in‑doc comments (`Confluence`/`Docs`),
- Git pull requests (if RFCs live in repos),
- dedicated RFC or design‑review boards.

Patterns:

- **Asynchronous review first**:
  - reviewers leave comments,
  - authors incorporate or respond.
- **Synchronous sessions where needed**:
  - for complex or contentious proposals,
  - with architecture, security, risk, and ops in the room.

Documentation:

- keep discussion history attached to RFC when possible,
- summarise major points in the RFC itself (e.g., in “Discussion Notes”).

---

### 3. Linking RFCs to Code & Tickets

Issue trackers:

- `Jira`, `Azure DevOps`, `Trello`, `Asana`.

Practices:

- add:
  - `RFC-ID` field or label on:
    - epics,
    - stories,
    - tasks derived from an RFC.
- in RFCs:
  - link to:
    - key epics,
    - implementation repos,
    - ADRs (Architecture Decision Records).

Benefits:

- easier to:
  - see which work items implement which RFC,
  - find relevant RFCs when reading code or tickets.

---

### 4. Architecture & Diagram Tools

For diagrams (`07-diagrams-and-technical-content.md`):

- `PlantUML`, `Mermaid` (text‑based, good in repos),
- `Draw.io`, `Lucidchart`, `Miro`, `FigJam` (visual).

Tips:

- store source files in:
  - a predictable location (e.g., `/architecture/diagrams`),
  - with naming aligned to RFC IDs.
- embed:
  - rendered diagrams in RFC,
  - link to editables.

---

### 5. Security, Risk & Compliance Tools

Depending on your org:

- threat modelling tools,
- GRC (Governance, Risk & Compliance) platforms,
- ticketing systems for:
  - security reviews,
  - privacy impact assessments,
  - model risk reviews.

Use:

- RFCs should:
  - reference IDs of:
    - security review tickets,
    - risk/compliance assessments,
    - sign‑off records,
  - so that governance artefacts are easily discoverable.

---

### 6. Repository & Lifecycle Management

If RFCs live in Git:

- treat them like code:
  - PRs for changes,
  - reviews and approvals,
  - tags/releases for baselines if helpful.

If RFCs live in wiki/doc tools:

- maintain:
  - an index page listing RFCs by:
    - ID,
    - title,
    - status,
    - domain.
- archive:
  - superseded RFCs into a clear “History” or “Superseded” section.

---

### 7. Beginner Checklist

- [ ] Do we have:
  - [ ] a standard place to store RFCs?
  - [ ] a standard template?
  - [ ] clear IDs and status labels?
- [ ] Are RFCs:
  - [ ] reviewable with comments (async and/or via PRs)?
  - [ ] linked to epics/stories and design docs?
- [ ] Are:
  - [ ] security/risk review tickets or records linked from the RFC?

If not, start by standardising **where RFCs live**, how they are **named**, and how they **link** to tickets and code.

---

### Connections to Other Files

- `04-workflow.md` – when tools are used in the RFC lifecycle.
- `10-documents-and-artifacts.md` – how RFCs fit into the broader documentation set.
- `24-governance-review-and-lifecycle.md` – governance tools and records.

