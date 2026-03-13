## 07 – Non‑Functional Requirements (NFRs)

This file explains **Non‑Functional Requirements (NFRs)** in depth and how to handle them in Requirements Engineering.

---

### 1. What Are NFRs (Simple View)

While **functional requirements** describe:

- *what* the system should do,

**NFRs** describe:

- *how well* it must do it,
- under which **conditions and constraints**.

They cover qualities like:

- performance,
- reliability and availability,
- security and privacy,
- usability and accessibility,
- observability and operability,
- compliance and auditability.

In enterprises/banks:

- NFRs can be the **difference between approval and rejection** by:
  - architecture boards,
  - risk and compliance,
  - production operations.

---

### 2. Main Categories of NFRs

Common categories (you can adapt names to your org standards):

1. **Performance & Capacity**
2. **Availability & Resilience**
3. **Security & Privacy**
4. **Usability & Accessibility**
5. **Observability & Operability**
6. **Compliance & Auditability**

---

### 3. Performance & Capacity

Questions:

- How fast must the system respond?
- How many users/transactions must it handle?
- Under what peak conditions?

Examples:

- “For SME application submission, 95% of requests must complete within 3 seconds during peak hours (weekday 9–18h).”
- “The system must support up to 500 concurrent logged‑in SME users per region without degradation beyond agreed thresholds.”

Where to capture:

- PRD NFR section,
- NFR specification,
- performance test plans,
- monitoring dashboards.

---

### 4. Availability & Resilience

Questions:

- When must the system be available?
- How quickly must it recover from failure?
- What are acceptable downtime windows?

Examples:

- “Service must have 99.5% availability per calendar month for SME application and status tracking.”
- “In case of a single availability zone failure, service must recover within 15 minutes without data loss beyond 5 minutes of transactions.”

Capturing:

- often aligned with:
  - enterprise SLOs/SLAs,
  - global resilience standards.

---

### 5. Security & Privacy

Questions:

- Who can access which data and functions?
- How is data protected in transit and at rest?
- How are threats like injection, XSS, brute force handled?

Examples:

- “All SME application data must be encrypted in transit (TLS 1.2+) and at rest using approved encryption standards.”
- “Access to SME credit decisions is restricted to authorized roles; all access must be logged with user ID and timestamp.”
- “Failed authentication attempts must be limited and monitored; suspicious patterns must trigger alerts.”

These intersect strongly with:

- security architecture,
- threat modelling,
- data protection policies.

---

### 6. Usability & Accessibility

Questions:

- Is the system easy to use for intended personas?
- Does it meet accessibility standards where required (e.g., WCAG)?

Examples:

- “SME application journey must be usable on common desktop and mobile browsers at 1024px+ width.”
- “Key forms and flows must meet WCAG 2.1 AA for contrast and keyboard navigation.”

Where captured:

- NFR section,
- UX guidelines,
- design system documentation,
- accessibility checklists.

---

### 7. Observability & Operability

Questions:

- Can we observe what is happening in production?
- Can operations/support respond quickly to issues?

Examples:

- “All critical user actions (application start, submission, decision) must emit structured logs with correlation IDs.”
- “Health checks and metrics (latency, error rates, queue depths) must be available to monitoring systems.”
- “On‑call teams must have runbooks for major incident scenarios (e.g., core dependency unavailable).”

These NFRs:

- reduce mean time to detect (MTTD) and mean time to recover (MTTR).

---

### 8. Compliance & Auditability

Questions:

- What needs to be logged and reported for regulatory purposes?
- What retention periods apply?
- How do we show that controls are working?

Examples:

- “All changes to risk configuration rules must be logged with user ID, before/after values, timestamp, and ticket reference.”
- “Retention period for SME application data is \<X> years as per regulation \<Y>; data older than this must be archived/deleted according to policy.”

Strongly linked to:

- risk and compliance requirements,
- data governance policies.

---

### 9. Writing Good NFRs (Measurable, Not Vague)

Avoid vague NFRs like:

- “The system should be fast,”
- “High security,”
- “User friendly.”

Instead:

- include:
  - a **metric**,
  - a **target**,
  - a **context** (when, where, for which flows).

Template:

> For \<scenario>, \<metric> must be \<operator> \<target> in \<time window / conditions>.

Example:

- “For authenticated SME users, P95 response time for viewing application status must be ≤ 2 seconds during business hours.”

---

### 10. NFRs in Requirements Engineering Workflow

In the workflow (`03-workflow.md`):

- NFRs are:
  - identified when scoping and drafting PRDs,
  - detailed in Stage 4,
  - referenced in user stories and acceptance criteria where relevant,
  - used to shape:
    - architecture and designs,
    - performance and security test plans,
    - runbooks and monitoring setups.

They should be:

- reviewed with:
  - architecture,
  - security,
  - risk/compliance,
  - operations/SRE,
- not just with product and engineering.

---

### 11. Beginner Checklist

- [ ] Have we covered:
  - [ ] performance & capacity?
  - [ ] availability & resilience?
  - [ ] security & privacy?
  - [ ] observability & operability?
  - [ ] compliance & auditability (if needed)?
- [ ] Are NFRs:
  - [ ] expressed in measurable terms?
  - [ ] aligned with enterprise standards or baselines?
  - [ ] visible to architecture, security, and ops?
- [ ] Are key NFRs:
  - [ ] reflected in acceptance criteria or test plans?

If not, strengthen NFR sections before finalising requirements.

---

### Connections to Other Files

- `05-prd-structure-and-authoring.md` – NFR section in the PRD.
- `06-user-stories-and-acceptance-criteria.md` – how to reflect NFRs in stories and criteria.
- `5-feasibility-study/09-scalability-performance-and-resilience.md` – feasibility background on technical qualities.
- `8-traceability-and-documentation.md` – how NFRs are traced to tests and monitoring.

