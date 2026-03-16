## 26 – Checklists for RFC Quality

This file provides **short checklists** you can run through before sending an RFC to review or marking it as accepted.

---

### 1. Problem & Context Checklist

- [ ] Is the **business and technical context** clearly explained?
- [ ] Is the **problem statement** specific and understandable?
- [ ] Are **goals and non‑goals** written down?
- [ ] Are links to:
  - [ ] requirements/PRDs,
  - [ ] strategy/roadmap,
  - [ ] feasibility studies,
  included?

---

### 2. Solution & Options Checklist

- [ ] Does the RFC describe:
  - [ ] a proposed solution at an appropriate level of detail?
  - [ ] at least one realistic alternative?
- [ ] Are:
  - [ ] pros and cons of each option discussed?
  - [ ] trade‑offs made explicit (value, risk, cost, NFRs)?

---

### 3. NFRs, Security & Compliance Checklist

- [ ] Are **performance and scalability** requirements captured?
- [ ] Are **availability and resilience** expectations documented?
- [ ] Are **security** aspects covered:
  - [ ] data handled,
  - [ ] access control,
  - [ ] main threats and controls?
- [ ] Are **compliance and privacy** topics addressed:
  - [ ] relevant regulations/policies,
  - [ ] logging and retention,
  - [ ] disclosures and consent (if applicable)?

---

### 4. Operational Checklist

- [ ] Are **monitoring and alerting** requirements noted?
- [ ] Is there a clear **deployment and rollback** strategy?
- [ ] Are **backup and disaster recovery** considerations present?
- [ ] Have SRE/ops stakeholders reviewed the RFC?

---

### 5. Governance & Lifecycle Checklist

- [ ] Does the RFC have:
  - [ ] a unique ID,
  - [ ] a clear status (Draft/In Review/etc.),
  - [ ] owner and date fields filled?
- [ ] Is there a plan for:
  - [ ] which forum will review and decide,
  - [ ] who must approve?
- [ ] If decisions have been made:
  - [ ] is the final status marked (Accepted/Rejected/Superseded)?
  - [ ] are approvers and dates recorded?

---

### 6. Collaboration Checklist

- [ ] Have:
  - [ ] product/requirements partners reviewed context and goals?
  - [ ] security and risk/compliance reviewed relevant sections?
  - [ ] SRE/ops reviewed operational aspects?
- [ ] Has feedback from these groups been:
  - [ ] addressed,
  - [ ] or documented with rationale if not adopted?

---

### 7. Implementation & Traceability Checklist

- [ ] Are:
  - [ ] key epics/stories linked from the RFC?
  - [ ] ADRs created for specific decisions (if used)?
- [ ] Is it clear:
  - [ ] which systems and components are impacted?
  - [ ] where to update documentation and runbooks?

---

### Connections to Other Files

- `02-objectives.md` and `04-workflow.md` – define the lifecycle these checklists support.
- `22-best-practices.md` and `23-common-mistakes.md` – background for many checklist items.
- `25-templates.md` – templates that align with these checklists.

