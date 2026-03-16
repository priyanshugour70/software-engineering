## 23 – Common Mistakes in RFCs

This file lists frequent **anti‑patterns** in RFC work and how to avoid them.

---

### 1. Solution‑First, Problem‑Light

Symptoms:

- RFC jumps straight to a favourite solution or tech,
- weak or missing problem statement and goals.

Fix:

- strengthen:
  - context and problem sections,
  - link clearly to requirements and strategy.

---

### 2. No Real Alternatives Considered

Symptoms:

- “Alternatives” section is:
  - empty, or
  - contains only strawman options.

Fix:

- require:
  - at least one serious alternative,
  - with pros/cons and rationale.

---

### 3. Ignoring NFRs, Security, and Compliance

Symptoms:

- RFC focuses only on functional behaviour,
- performance, resilience, security, and compliance under‑specified.

Fix:

- use:
  - dedicated sections and checklists,
  - involve security, risk, and ops early.

---

### 4. Overly Long, Unfocused Documents

Symptoms:

- 30+ page RFCs mixing:
  - requirements,
  - design,
  - code‑level details,
  - project plans.

Fix:

- keep RFC:
  - focused on decisions and trade‑offs,
  - move detail to appendices and linked docs.

---

### 5. RFCs That Never Reach a Clear Decision

Symptoms:

- status remains:
  - “Draft” or “In Review” for months,
- no explicit “Accepted/Rejected/Superseded” record.

Fix:

- use:
  - governance forums with clear decision owners,
  - explicit status transitions and approvals.

---

### 6. Decisions Made Outside the RFC but Not Recorded

Symptoms:

- architecture calls happen in meetings or chat,
- RFC is not updated,
- future readers see stale content.

Fix:

- after decisions:
  - immediately update RFC,
  - or add a new RFC/ADR referencing the decision.

---

### 7. Poor Collaboration with Key Stakeholders

Symptoms:

- security, risk, ops see RFCs very late,
- product context is weak,
- review cycles are painful and slow.

Fix:

- co‑author with key roles,
- invite them early in the workflow,
- capture their input in the document.

---

### 8. No Links to Implementation or Operations

Symptoms:

- RFC seems isolated:
  - no epics/stories linked,
  - no references to runbooks or monitoring.

Fix:

- link:
  - to backlog items,
  - to design docs,
  - to operational artefacts and tickets.

---

### 9. Beginner Checklist

- [ ] Does the RFC:
  - [ ] clearly state context and problem?
  - [ ] include at least one serious alternative?
  - [ ] address NFRs, security, and compliance?
  - [ ] end with an explicit decision and status?
- [ ] Are:
  - [ ] key stakeholders involved early?
  - [ ] implementation and ops linked?

If not, treat these as signals to improve the RFC before approval.

---

### Connections to Other Files

- `22-best-practices.md` – positive patterns to replace these mistakes.
- `06-option-analysis-and-tradeoffs.md` and `08-security-compliance-and-risk-in-rfcs.md` – common weak spots.
- `24-governance-review-and-lifecycle.md` – governance structures that help avoid these anti‑patterns.

