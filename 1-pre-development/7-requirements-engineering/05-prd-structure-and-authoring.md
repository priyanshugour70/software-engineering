## 05 – PRD Structure & Authoring

This file shows **how to structure and write** Product Requirements Documents (PRDs) in a way that is:

- clear for beginners,
- practical for engineers and testers,
- acceptable to risk, compliance, and operations in enterprises/banks.

---

### 1. What a PRD Is (and Is Not)

**PRD is:**

- a **single, structured document** that describes:
  - context and goals,
  - scope and non‑goals,
  - personas and journeys,
  - functional and non‑functional requirements,
  - dependencies and risks.

**PRD is not:**

- a full design document (UX and technical design have their own artifacts),
- a backlog (user stories live in tools like `Jira` but link to PRD sections),
- a static contract that never changes.

Think of PRD as:

- the **narrative spine** that holds requirements together.

---

### 2. Suggested PRD Structure (Template Overview)

At high level:

1. Document Metadata
2. Executive Summary
3. Background & Context
4. Goals & Non‑Goals
5. Personas & User Journeys
6. Functional Requirements
7. Non‑Functional Requirements (NFRs)
8. Dependencies & Assumptions
9. Analytics & Success Metrics
10. Risks & Open Questions
11. Appendices

You can find a filled‑out template example in `25-templates.md`.

Below we briefly explain each section.

---

### 3. Section‑by‑Section Guide

#### 3.1 Document Metadata

Purpose:

- make ownership and status clear.

Include:

- owner (name and role),
- contributors/reviewers,
- version number and date,
- status (draft / in review / baselined / superseded),
- links to:
  - related strategies,
  - roadmaps,
  - epics.

#### 3.2 Executive Summary

Goal:

- provide a **one‑page story**:
  - what we are building,
  - why,
  - for whom,
  - by when (roughly).

Keep it:

- understandable by executives and non‑technical colleagues.

#### 3.3 Background & Context

Include:

- market or business drivers,
- user and research insights,
- technology/operations context (e.g., legacy constraints),
- link to earlier phase documents:
  - opportunity,
  - problem definition,
  - research,
  - business case,
  - feasibility.

Purpose:

- help new readers understand **why this PRD exists**.

#### 3.4 Goals & Non‑Goals

Goals:

- specific outcomes this PRD aims to achieve,
- link to:
  - objectives,
  - key results/metrics.

Non‑Goals:

- things that:
  - are **explicitly out of scope**,
  - even if related.

Example:

- Goal:
  - “Reduce SME digital application time to decision to < 2 hours for simple cases.”
- Non‑Goal:
  - “Replacing the core banking system is out of scope for this PRD.”

Non‑goals:

- reduce future confusion and scope creep.

#### 3.5 Personas & User Journeys

Summarize:

- key personas:
  - e.g., SME owner, relationship manager, risk officer, operations analyst.
- main journeys:
  - current state vs future state where relevant.

Use:

- simple diagrams or step lists,
- link to detailed journey maps in design tools.

#### 3.6 Functional Requirements

Organize by:

- feature areas or journeys,
- with IDs (FR‑1, FR‑2, …).

For each requirement:

- description,
- trigger (when/where it applies),
- behaviour,
- business rules,
- data considerations,
- edge cases and error handling,
- related personas or roles.

Aim:

- enough detail that:
  - user stories and tests can be derived,
  - but not so detailed that it becomes unreadable.

#### 3.7 Non‑Functional Requirements (NFRs)

See `07-non-functional-requirements.md` for depth.

Include:

- performance and capacity,
- availability and resilience,
- security and privacy,
- observability and operability,
- compliance and auditability constraints.

Where possible:

- use measurable statements, e.g.:
  - “P95 response time ≤ 3 seconds for up to 100 concurrent SME applications.”

#### 3.8 Dependencies & Assumptions

List:

- upstream/downstream systems,
- platform capabilities,
- organizational and process dependencies,
- key assumptions (e.g., capacity, timelines).

Clarify:

- what must be ready for PRD outcomes to be realized.

#### 3.9 Analytics & Success Metrics

Define:

- events and data that must be captured,
- metrics and dashboards required to:
  - measure success,
  - detect problems.

Examples:

- application start/completion,
- drop‑off points,
- time to decision,
- error rates by step.

#### 3.10 Risks & Open Questions

List:

- known risks (technical, operational, regulatory),
- mitigation ideas,
- open questions requiring decisions or research.

Keep this section:

- actively updated during the project.

#### 3.11 Appendices

May contain:

- wireframes or mockups,
- detailed process maps,
- glossary,
- links to research reports, feasibility studies, business cases.

---

### 4. Authoring Tips (Especially for Enterprises/Banks)

- **Write for a mixed audience**:
  - some technical detail is needed,
  - but keep language accessible.
- **Be explicit about constraints**:
  - regulatory,
  - risk,
  - operational.
- **Use consistent IDs and naming**:
  - FR‑1, FR‑2, NFR‑1, etc.,
  - helps with traceability.
- **Link, don’t repeat**:
  - link to other documents instead of copying full text.
- **Iterate**:
  - start with outline,
  - refine over a few sessions with key partners.

---

### 5. Common Mistakes in PRDs

See also `23-common-mistakes.md`.

Frequent issues:

- giant documents nobody reads,
- vague requirements without acceptance conditions,
- missing NFRs,
- outdated versions with no clear status.

Mitigations:

- keep core PRD reasonably short,
- use appendices and links for detail,
- maintain version and status fields,
- align PRD updates with roadmap and governance cadences (`24-governance-and-change-control.md`).

---

### Connections to Other Files

- `03-workflow.md` – identifies where PRDs are drafted and evolved in the process.
- `06-user-stories-and-acceptance-criteria.md` – user stories should link back to PRD sections.
- `07-non-functional-requirements.md` – source for NFR content in PRDs.
- `25-templates.md` – concrete PRD templates you can copy and adapt.

