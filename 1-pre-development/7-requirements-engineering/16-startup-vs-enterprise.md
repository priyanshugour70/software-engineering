## 16 – Startup vs Enterprise Approaches

This file compares how Requirements Engineering typically differs between:

- startups/scaleups, and
- large enterprises/banks.

Use it to **adapt** practices, not copy them blindly.

---

### 1. Key Differences

Dimensions:

- speed vs governance,
- amount of legacy and integration,
- number of stakeholders,
- regulatory pressure,
- documentation expectations.

Startups:

- fewer constraints and stakeholders,
- smaller systems,
- faster iteration cycles.

Enterprises/banks:

- heavier governance and risk oversight,
- complex landscapes of legacy systems,
- higher regulatory/compliance expectations.

---

### 2. Requirements in Startups/Scaleups

Characteristics:

- requirements often:
  - live in:
    - lightly structured docs,
    - issue trackers,
    - design tools,
    - the founders’ heads.
- emphasis on:
  - learning and iteration,
  - shipping quickly,
  - measuring impact.

Practices:

- lightweight PRDs (sometimes replaced by:
  - brief specs,
  - “one‑pager” documents),
- heavy use of:
  - user stories and acceptance criteria,
  - design prototypes and experiments.

Risks:

- team grows and:
  - shared understanding starts to break,
  - “tribal knowledge” doesn’t scale,
  - inconsistent behaviours across areas.

Mitigations:

- introduce:
  - simple but consistent PRD/requirements templates,
  - minimal NFR and decision logging,
  - basic traceability for critical flows.

---

### 3. Requirements in Enterprises/Banks

Characteristics:

- many:
  - systems,
  - teams,
  - stakeholders.
- strong:
  - regulatory and risk requirements.

Practices:

- more formal:
  - PRDs and requirement specs,
  - review and sign‑off processes,
  - traceability and documentation.

Risks:

- requirements:
  - become bloated and unreadable,
  - are treated as static contracts,
  - are written by isolated roles without team collaboration.

Mitigations:

- apply:
  - the **good parts** of structured requirements,
  - but keep:
    - collaborative refinement,
    - focus on outcomes and tests,
    - room for controlled change.

---

### 4. What Startups Can Learn from Enterprises

Useful practices:

- explicit NFRs:
  - thinking early about performance, security, and observability.
- traceability for critical areas:
  - e.g., billing, compliance‑relevant features.
- basic governance:
  - clear decision logs,
  - simple change control for scope.

Avoid:

- copying heavy templates and approvals that slow learning unnecessarily.

---

### 5. What Enterprises Can Learn from Startups

Useful practices:

- **conversation‑first requirements**:
  - use PRDs and stories as conversation tools,
  - not just documents to send around.
- **thin slices and MVPs**:
  - avoid giant “all at once” requirements,
  - focus on incremental value and learning.
- **rapid feedback loops**:
  - release earlier versions,
  - use analytics and user feedback to refine requirements.

Avoid:

- keeping:
  - old governance expectations but just adding “agile” terminology.

---

### 6. Hybrid Environments

Many large organizations:

- have **startup‑like teams** (digital labs, ventures),
- working within enterprise constraints.

Implications:

- hybrid requirements practices:
  - lighter for exploratory work,
  - more formal when integrating with core systems,
  - careful handling of risk/compliance boundaries.

---

### 7. Beginner Checklist

- [ ] Are you primarily in:
  - [ ] a startup/scaleup,
  - [ ] a large enterprise/bank,
  - [ ] a hybrid context?
- [ ] Have you:
  - [ ] tuned the *amount and style* of documentation to fit?
  - [ ] avoided copying extremes (no docs vs huge specs)?
- [ ] Do you:
  - [ ] still preserve collaboration and feedback loops,
  - [ ] even where governance is heavier?

If not, consider incremental adjustments based on this file.

---

### Connections to Other Files

- `15-contexts-and-domains.md` – domain context beyond organisation size.
- `17-regulated-vs-unregulated-products.md` – regulation as another key axis.
- `24-governance-and-change-control.md` – governance patterns appropriate for different contexts.

