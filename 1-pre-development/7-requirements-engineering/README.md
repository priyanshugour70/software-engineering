## Requirements Engineering (PRD / User Stories)

### What This Folder Is

This folder is a **complete handbook** for the *Requirements Engineering* phase.

It explains how to turn:

- strategy, research, and product roadmaps  
into:
- **clear, testable, traceable requirements** that guide:
  - design,
  - development,
  - testing,
  - and operations.

If you are a **beginner**, start with `01-concepts.md` and read in order.  
If you are **experienced**, use the table of contents below to jump to specific topics.

---

### Quick Table of Contents (Click to Navigate)

- **Foundations**
  - [01 – Concepts](./01-concepts.md)
  - [02 – Objectives](./02-objectives.md)
  - [03 – Workflow](./03-workflow.md)
  - [04 – Scope & Slicing](./04-scope-and-slicing.md)
  - [05 – PRD Structure & Authoring](./05-prd-structure-and-authoring.md)
  - [06 – User Stories & Acceptance Criteria](./06-user-stories-and-acceptance-criteria.md)
  - [07 – Non‑Functional Requirements (NFRs)](./07-non-functional-requirements.md)
  - [08 – Traceability & Documentation](./08-traceability-and-documentation.md)
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
  - [18 – Collaboration with Design & Architecture](./18-collaboration-with-design-and-architecture.md)
  - [19 – Collaboration with Testing & QA](./19-collaboration-with-testing-and-qa.md)
- **Learning from Practice**
  - [20 – Case Studies](./20-case-studies.md)
  - [21 – Real‑World Examples](./21-real-world-examples.md)
- **Quality & Governance**
  - [22 – Best Practices](./22-best-practices.md)
  - [23 – Common Mistakes](./23-common-mistakes.md)
  - [24 – Governance & Change Control](./24-governance-and-change-control.md)
- **Assets for Execution**
  - [25 – Templates](./25-templates.md)
  - [26 – Checklists](./26-checklists.md)
  - [27 – Glossary](./27-glossary.md)

---

### Overview (Beginner Friendly)

**Requirements Engineering** turns:

- product strategy and roadmaps (`6-product-strategy-roadmap`),
- research outputs (personas, journeys, insights),
- feasibility and architecture directions,
- business cases and success metrics,

into **concrete, testable requirements**:

- **what** should be built,
- **for whom**,
- **under which conditions**,
- **how we will know** it works.

It covers:

- **functional requirements** (behaviour / features),
- **non‑functional requirements (NFRs)** (performance, security, availability, operability),
- **traceability** back to:
  - objectives,
  - risks,
  - and tests.

This phase is:

- iterative (requirements evolve as we learn),
- collaborative (product, design, engineering, QA, risk, operations),
- critical for:
  - avoiding ambiguity,
  - reducing rework,
  - and ensuring quality.

---

### Objectives (Summary)

> Detailed breakdown in `02-objectives.md`.

- **Specify functional requirements** in a user‑centric, testable way.
- **Capture non‑functional requirements** for performance, security, availability, resilience, and operability.
- **Provide a shared understanding** across product, design, engineering, QA, and stakeholders.
- **Enable traceability** from business objectives and regulatory constraints to implementation and tests.
- **Minimize ambiguity and misinterpretation**, especially across multiple teams and vendors.

---

### Activities (Summary)

> Step‑by‑step in `03-workflow.md`.

- **Define Release / Increment Scope**
  - select epics and features from the roadmap,
  - clarify which personas, journeys, and edge cases are in scope.
- **Author & Evolve PRDs**
  - background, goals, and non‑goals,
  - personas and journeys,
  - functional and non‑functional requirements,
  - dependencies, risks, and open questions.
- **Create User Stories & Acceptance Criteria**
  - “As a \<persona>, I want \<goal> so that \<benefit>,”
  - Given/When/Then acceptance criteria,
  - link stories to epics and PRD sections.
- **Define and Validate NFRs**
  - performance and capacity targets,
  - availability and resilience,
  - security, privacy, and compliance requirements,
  - operability (monitoring, alerting, runbooks).
- **Refinement / Grooming**
  - walkthroughs with engineering, QA, design, risk,
  - estimation and feasibility checks,
  - splitting and clarifying stories.
- **Traceability & Documentation**
  - link requirements to:
    - objectives and OKRs,
    - risks and controls,
    - test cases and test results,
  - maintain versioning and change history.

---

### Inputs & Outputs (Summary)

**Inputs**

- Product strategy and roadmap (`6-product-strategy-roadmap`).
- Research outputs:
  - personas,
  - journeys,
  - insights (`3-user-market-research`).
- Business case and success metrics (`4-business-case-roi`).
- Feasibility and architecture directions (`5-feasibility-study`).
- Regulatory and compliance constraints.

**Outputs**

- **Product Requirements Documents (PRDs)** – structured, narrative specs.
- **User Stories & Acceptance Criteria** – in an issue tracker (`Jira`, `Azure DevOps`, etc.).
- **Non‑Functional Requirements Specifications** – including security and operational aspects.
- **Traceability Views** – mapping requirements to objectives, risks, and tests (especially in regulated contexts).

These outputs feed directly into:

- **Architecture & Governance**,
- **Design (UX/UI, service design)**,
- **Development & Testing**,
- and **Operational Readiness**.

---

### Roles Responsible (Summary)

> Detailed in `11-roles-and-positions.md`.

- **Primary**
  - Product Managers / Product Owners,
  - Business Analysts / Requirements Engineers (where present),
  - Lead Engineers / Tech Leads (for NFRs and feasibility).
- **Supporting**
  - UX / Service Designers,
  - QA / Test Engineers,
  - Architecture and security teams,
  - Risk / Compliance (for regulated products),
  - Operations / SRE (for operability requirements).

---

### Example PRD Structure (At a Glance)

> Full template and examples in `05-prd-structure-and-authoring.md` and `25-templates.md`.

Typical sections:

- document metadata and ownership,
- executive summary and context,
- goals and non‑goals,
- personas and journeys,
- functional requirements (FR‑1, FR‑2, …),
- non‑functional requirements (performance, security, availability, etc.),
- dependencies and assumptions,
- analytics and success metrics,
- risks and open questions,
- appendices (wireframes, flows, glossary).

---

### How This Phase Connects to Others

- Takes **direction and priorities** from:
  - `6-product-strategy-roadmap`.
- Uses **insights and constraints** from:
  - `1–5` pre‑development modules.
- Produces **inputs** for:
  - architecture design,
  - UX and service design,
  - implementation planning and testing.

Together with the previous six folders, this one completes the chain from:

- opportunity → strategy → roadmap → **requirements** → delivery.

