## 25 – Templates for Requirements Engineering

This file provides **practical templates and outlines** you can copy into your own tools for PRDs, NFRs, traceability, decision logs, and refinement.

They are intentionally simple and can be adapted.

---

### 1. PRD Template (Short Form)

**Title:** Product Requirements Document – \<Product / Feature / Increment>

**1. Document Metadata**

- Owner: \<Name, Role>  
- Contributors: \<Names>  
- Version: \<X.Y>  
- Status: Draft / In Review / Baseline for \<Release X>  
- Last Updated: \<Date>  
- Related Epics/Initiatives: \<IDs>  

**2. Executive Summary**

- 2–5 bullet points:
  - what problem we’re solving,
  - for whom,
  - key outcomes and constraints.

**3. Background & Context**

- Brief description of:
  - current situation and pain points,
  - links to opportunity, research, business case, feasibility docs.

**4. Goals & Non‑Goals**

- Goals:
  - G‑1: \<Goal statement + metric if possible>
  - G‑2: \<…>
- Non‑Goals:
  - NG‑1: \<Explicitly out of scope item>
  - NG‑2: \<…>

**5. Personas & Journeys**

- Personas:
  - \<Persona 1>: short description.
  - \<Persona 2>: short description.
- Journeys:
  - current vs future (high level, link to detailed diagrams).

**6. Functional Requirements (FRs)**

- FR‑1 \<Name>  
  - Description  
  - Triggers and flows  
  - Business rules  
  - Data needs / fields  
  - Edge cases / errors  
- FR‑2 \<Name>  
  - …

**7. Non‑Functional Requirements (NFRs)**

- NFR‑P1 \<Performance requirement>  
- NFR‑A1 \<Availability/resilience requirement>  
- NFR‑S1 \<Security/privacy requirement>  
- NFR‑O1 \<Observability/operability requirement>  
- NFR‑C1 \<Compliance/audit requirement>  

**8. Dependencies & Assumptions**

- Dependencies:
  - \<System / Team / Platform> – \<what is needed>
- Assumptions:
  - \<Assumption> – \<risk if wrong>

**9. Analytics & Success Metrics**

- Metrics:
  - \<Metric name> – \<definition, target, measurement source>
- Events / Data:
  - \<Main events to track, fields needed>

**10. Risks & Open Questions**

- Risks:
  - \<Risk> – \<impact, likelihood, mitigation>
- Open Questions:
  - \<Question> – \<owner, due date>

**11. Appendices**

- Links:
  - designs, research, architecture docs,
  - feasibility, business cases.

---

### 2. NFR Summary Template

**Title:** NFR Summary – \<System / Product / Increment>

**1. Performance & Capacity**

- Scenario:
  - \<description>
- Metric and target:
  - \<e.g., P95 latency ≤ 3s under \<X> concurrent users>

**2. Availability & Resilience**

- Availability target:
  - \<e.g., 99.5% monthly>
- Recovery expectations:
  - \<RTO/RPO, failover approach>

**3. Security & Privacy**

- Authentication & authorization:
  - \<requirements>
- Data protection:
  - \<encryption, masking, retention>
- Logging & monitoring:
  - \<what and how>

**4. Observability & Operability**

- Metrics:
  - \<list of key metrics>
- Logs:
  - \<key events and fields>
- Alerts:
  - \<conditions that require intervention>
- Runbooks:
  - \<links or references>

**5. Compliance & Auditability**

- Regulatory/policy references:
  - \<IDs or names>
- Required evidence:
  - \<reports, logs, approvals>

---

### 3. Traceability Table Template

Can be a table in `Confluence`/`Sheets`/`Notion`.

**Columns:**

- Objective / Regulation ID
- Objective / Regulation Description
- Requirement ID(s) (FR/NFR)
- Epic / Story ID(s)
- Test Case / Suite ID(s)
- Status (Planned / Implemented / Tested / Verified)
- Notes

Use this first:

- for **most critical** objectives or regulatory requirements,
- then expand gradually.

---

### 4. Decision & Change Log Template

**Columns:**

- Date
- Decision / Change Summary
- Alternatives Considered
- Rationale (including risks and assumptions)
- Affected Requirements / PRDs / Stories
- Decision Makers (names/roles)
- Follow‑Up Actions

Use:

- for major scope or requirement changes,
- for regulatory or risk‑significant decisions.

---

### 5. Refinement Session Agenda Template

**Meeting:** Requirements Refinement – \<Scope / Epic>  
**Duration:** 60–90 minutes  
**Participants:** PM/PO, BA, Tech Lead, QA, Designer, others as needed

**1. Objective of Session (5 min)**

- E.g., “Refine acceptance criteria for stories in Epic X,”  
  “Validate NFRs for new flow Y.”

**2. Walk Through Context & Scope (10–15 min)**

- recap goals, personas, and flows,
- show relevant designs or diagrams.

**3. Story‑by‑Story Review (30–50 min)**

- for each story:
  - review:
    - statement,
    - acceptance criteria,
    - dependencies,
  - capture:
    - clarifications,
    - edge cases,
    - NFR implications,
  - adjust as needed.

**4. Summarise Changes & Actions (10–15 min)**

- list:
  - stories ready for estimation,
  - follow‑ups (design, tech spike, risk input).

---

### 6. Beginner Tips for Using Templates

- start with:
  - the **short PRD template**,
  - NFR summary,
  - and traceability table for critical areas.
- avoid:
  - over‑filling templates with unnecessary detail,
  - letting them grow into unreadable documents.
- continuously:
  - adjust templates to your domain and team needs.

---

### Connections to Other Files

- `05-prd-structure-and-authoring.md` – conceptual basis for the PRD template.
- `07-non-functional-requirements.md` – informs the NFR summary structure.
- `08-traceability-and-documentation.md` and `24-governance-and-change-control.md` – where traceability and decision logs fit in the process.
- `26-checklists.md` – checklists that align with these templates.

