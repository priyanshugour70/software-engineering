## 10 – Documents & Artifacts for Requirements Engineering

This file lists the **key documents and artifacts** you should maintain during the Requirements Engineering phase and how they fit together.

---

### 1. Core Document Set (Overview)

At minimum, you want:

1. **Product Requirements Documents (PRDs)**
2. **NFR Specifications / Quality Guidelines**
3. **User Story Backlog (with Acceptance Criteria)**
4. **Traceability View**
5. **Decision & Change Log**

Optional but useful:

- journey and flow diagrams,
- domain and data models (lightweight),
- test plans and NFR test suites.

---

### 2. Product Requirements Documents (PRDs)

Purpose:

- provide:
  - narrative overview of what is being built and why,
  - structured list of functional requirements,
  - context for stories and tests.

Where:

- `Confluence`, `Notion`, `Google Docs`, etc.

Owner:

- PM / PO or Business Analyst.

Connections:

- link to:
  - roadmap items (epics/initiatives),
  - NFR specs,
  - key stories in issue tracker.

Structure:

- see `05-prd-structure-and-authoring.md` and `25-templates.md`.

---

### 3. NFR Specifications / Quality Guidelines

Purpose:

- document:
  - performance and capacity expectations,
  - availability and resilience targets,
  - security, privacy, observability, and compliance requirements.

Where:

- can be:
  - part of PRDs,
  - or separate NFR documents if shared across multiple PRDs.

Owner:

- jointly:
  - product,
  - architecture,
  - security/risk,
  - operations/SRE.

Connections:

- referenced in:
  - PRDs,
  - stories (for key NFRs),
  - test plans,
  - runbooks and monitoring.

---

### 4. User Story Backlog (with Acceptance Criteria)

Purpose:

- operationalize requirements into:
  - units of work for teams,
  - building blocks for sprints or iterations.

Where:

- `Jira`, `Azure DevOps`, `Trello`, `Asana`, etc.

Owner:

- PM/PO with engineering/QA input.

Connections:

- each story:
  - links to:
    - PRD requirement ID,
    - epic/initiative,
    - sometimes objective/theme.
- acceptance criteria:
  - reflect:
    - functional and key NFR expectations.

---

### 5. Traceability View

Purpose:

- show how:
  - objectives and regulatory requirements,
  - map to:
    - PRD requirements,
    - stories,
    - tests.

Where:

- simple table in:
  - `Confluence`/`Notion`/`Sheets`,
  - or part of ALM tooling.

Owner:

- BA / PM / QA (collaborative).

Contents:

- columns like:
  - Objective/Regulation ID,
  - Requirement ID (FR/NFR),
  - Story/Epic ID,
  - Test ID,
  - Status/Evidence.

---

### 6. Decision & Change Log

Purpose:

- record:
  - important requirement decisions and changes,
  - rationale and approvers,
  - affected artifacts.

Why:

- avoids:
  - losing context,
  - re‑arguing old decisions,
  - confusion during audits or reviews.

Where:

- a page or table in documentation space,
- or dedicated “decision log” per product/program.

Template:

- see `25-templates.md`.

---

### 7. Supporting Artifacts

Useful additions:

- **Journey & Flow Diagrams**
  - high‑level flows for main journeys and edge cases,
  - link to PRDs and stories.
- **Domain & Data Models (Lightweight)**
  - key entities and relationships relevant to requirements,
  - help clarify data requirements.
- **Test Plans & NFR Test Suites**
  - how you will validate requirements,
  - including performance, security, and resilience tests.

These can be:

- diagrams in `Miro`/`Lucidchart`,
- models in architecture tools,
- documents or pages in the same space as PRDs.

---

### 8. Beginner Checklist

- [ ] Do we have:
  - [ ] at least one PRD for the current major scope?
  - [ ] NFRs documented somewhere discoverable?
  - [ ] a story backlog with acceptance criteria?
  - [ ] some form of traceability view (even simple)?
  - [ ] a log for important requirement decisions/changes?
- [ ] Are:
  - [ ] these artifacts linked to each other?
  - [ ] owned and updated around each increment/release?

If not, start by:

- setting up a single documentation space,
- adding a PRD and traceability table,
- and tightening links between docs and the issue tracker.

---

### Connections to Other Files

- `05-prd-structure-and-authoring.md` – defines what goes into PRDs.
- `08-traceability-and-documentation.md` – how to link these artifacts together.
- `25-templates.md` – concrete templates for PRDs, traceability, and decision logs.
- `26-checklists.md` – quick checks that cover document completeness.

