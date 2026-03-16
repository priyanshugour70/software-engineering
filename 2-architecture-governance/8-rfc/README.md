## RFC / Technical Proposal

### What This Folder Is

This folder is a **complete handbook** for the *RFC / Technical Proposal* phase.

It explains how to go from:

- high‑level requirements and roadmaps  
to:
- **clear, structured technical proposals (RFCs)** that:
  - compare solution options,
  - document trade‑offs and decisions,
  - and align architects, engineers, security, risk, and business.

If you are a **beginner**, start with `01-concepts.md` and read in order.  
If you are **experienced**, use the table of contents below to jump to specific topics.

---

### Quick Table of Contents (Click to Navigate)

- **Foundations**
  - [01 – Concepts](./01-concepts.md)
  - [02 – Objectives](./02-objectives.md)
  - [03 – When & When Not to Use an RFC](./03-when-to-use-an-rfc.md)
  - [04 – Workflow](./04-workflow.md)
  - [05 – RFC Structure & Authoring](./05-rfc-structure-and-authoring.md)
  - [06 – Option Analysis & Trade‑offs](./06-option-analysis-and-tradeoffs.md)
  - [07 – Diagrams & Technical Content](./07-diagrams-and-technical-content.md)
  - [08 – Security, Compliance & Risk in RFCs](./08-security-compliance-and-risk-in-rfcs.md)
- **Execution Enablers**
  - [09 – Tools](./09-tools.md)
  - [10 – Documents & Artifacts](./10-documents-and-artifacts.md)
- **People & Skills**
  - [11 – Roles and Positions](./11-roles-and-positions.md)
  - [12 – Skills](./12-skills.md)
  - [13 – Job Market](./13-job-market.md)
  - [14 – Salary Benchmarks](./14-salary-benchmarks.md)
- **Context & Collaboration**
  - [15 – Contexts and Domains](./15-contexts-and-domains.md)
  - [16 – Startup vs Enterprise](./16-startup-vs-enterprise.md)
  - [17 – Regulated vs Unregulated Products](./17-regulated-vs-unregulated-products.md)
  - [18 – Collaboration with Product & Requirements](./18-collaboration-with-product-and-requirements.md)
  - [19 – Collaboration with Security, Risk & Ops](./19-collaboration-with-security-risk-and-ops.md)
- **Learning from Practice**
  - [20 – Case Studies](./20-case-studies.md)
  - [21 – Real‑World Examples](./21-real-world-examples.md)
- **Quality & Governance**
  - [22 – Best Practices](./22-best-practices.md)
  - [23 – Common Mistakes](./23-common-mistakes.md)
  - [24 – Governance, Review & Lifecycle](./24-governance-review-and-lifecycle.md)
- **Assets for Execution**
  - [25 – Templates](./25-templates.md)
  - [26 – Checklists](./26-checklists.md)
  - [27 – Glossary](./27-glossary.md)

---

### Overview (Beginner Friendly)

An **RFC (Request for Comments) / Technical Proposal** is:

- a **structured, reviewable document** describing a significant technical change or new system,
- the primary mechanism for:
  - **cross‑team alignment**,
  - **architectural decision‑making**,
  - and **governance and approvals**.

In enterprises and banks, RFCs often:

- act as **official records** supporting:
  - audits,
  - risk assessments,
  - architecture reviews.

They sit between:

- **Requirements** (what we need)  
and:
- **Architecture Design & Implementation** (how we will build and run it).

---

### Objectives (Summary)

> Detailed breakdown in `02-objectives.md`.

- **Describe context and problem** from a technical and architectural perspective.
- **Propose and compare solution options**, with:
  - rationale,
  - trade‑offs,
  - and risk/impact analysis.
- **Obtain feedback and approval** from all relevant stakeholders:
  - product, engineering, architecture,
  - security, risk, compliance, operations.
- **Document decisions and alternatives** for future reference:
  - for audits,
  - for new joiners,
  - for future redesigns.
- **Provide input to detailed design and implementation**:
  - architecture design,
  - backlog planning,
  - security and compliance work.

---

### Activities (Summary)

> Step‑by‑step in `04-workflow.md`.

- **RFC Scoping**
  - decide whether a change needs an RFC (based on impact, risk, cross‑team dependencies),
  - clarify objectives, constraints, and success criteria.
- **Drafting the RFC**
  - capture:
    - context, problem, goals, non‑goals,
    - current state,
    - proposed solution(s),
    - alternatives and trade‑offs,
    - high‑level architecture and data flows,
    - security, compliance, and operational considerations.
- **Review & Feedback**
  - share with key reviewers,
  - run async reviews and live sessions,
  - capture comments, Q&A, design discussions.
- **Decision & Sign‑Off**
  - converge on a recommended option,
  - document decisions, approvals, and conditions,
  - record status (Draft → In Review → Accepted/Rejected/Superseded).
- **Post‑Decision Updates**
  - keep RFC updated when major assumptions change,
  - link to:
    - architecture design documents,
    - implementation tickets,
    - security and risk artefacts.

---

### Inputs & Outputs (Summary)

**Inputs**

- Product strategy and roadmap.
- Requirements and PRDs (including NFRs).
- Feasibility studies and technical assessments.
- Enterprise architecture principles and standards.
- Security and compliance baseline requirements.

**Outputs**

- **RFC Document(s)**:
  - unique ID, status, and ownership,
  - recorded decisions and rationale.
- **Architecture Decision Records (ADRs)** (optional but recommended):
  - compact decision summaries linked to RFCs.
- **Links to Downstream Artefacts**:
  - architecture design docs,
  - backlog items (epics/stories),
  - security/compliance tickets.

These outputs:

- feed into `9-architecture-design`,
- are referenced in `10-security-review` and `11-compliance-risk`,
- and stay as **long‑term decision evidence**.

---

### Roles Responsible (Summary)

> Detailed in `11-roles-and-positions.md`.

- **Primary**
  - Senior Engineers / Tech Leads,
  - Solution / Domain Architects,
  - sometimes Staff/Principal Engineers.
- **Supporting**
  - Product Managers / Product Owners,
  - Security Architects / Engineers,
  - Risk / Compliance partners,
  - Operations / SRE / Platform leads.

RFCs are most effective when:

- they are **owned** by a clear technical leader,
- but **co‑authored and reviewed** with all impacted roles.

---

### Example RFC Structure (At a Glance)

> Full templates and worked examples in `05-rfc-structure-and-authoring.md` and `25-templates.md`.

Typical sections:

- metadata (ID, author, status, reviewers, related documents),
- summary,
- context & problem statement,
- goals & non‑goals,
- proposed solution,
- alternatives considered,
- architecture & diagrams,
- security, compliance & privacy,
- operational considerations,
- migration / rollout plan,
- risks & open questions,
- decision & approvals,
- appendices.

---

### How This Phase Connects to Others

- Takes **direction and constraints** from:
  - `1-pre-development` (especially strategy, feasibility, and requirements).
- Feeds into:
  - `9-architecture-design` for deeper design work,
  - `10-security-review` and `11-compliance-risk` for more focused assessments.
- Produces:
  - durable records of **why a particular technical path was chosen**,  
  - which are critical in:
    - long‑lived systems,
    - regulated environments,
    - and complex enterprises.

