## 01 – Concepts: Requirements Engineering (PRD / User Stories)

This file explains the **core concepts** of Requirements Engineering in a simple, beginner‑friendly way.

---

### 1. Simple Definition

**Requirements Engineering** is the work of turning:

- ideas, problems, strategy, and roadmaps  
into:
- **clear, testable descriptions** of what a system should do and how it should behave.

It answers:

- “What exactly are we building?”  
- “For whom and in which situations?”  
- “How will we know it works correctly and safely?”  
- “Under what performance, security, and operational conditions?”

It covers:

- **functional requirements** – behaviour, flows, features,
- **non‑functional requirements (NFRs)** – performance, security, availability, operability,
- **traceability** – linking requirements back to:
  - business objectives,
  - risks,
  - and tests.

---

### 2. Where It Sits in the Overall Flow

By the time you reach this phase, you should already have:

- validated **opportunities and problems** (`1` and `2`),
- **user & market insights** (`3`),
- **business cases & ROI** (`4`),
- **feasibility assessments** (`5`),
- **product strategy & roadmap** (`6`).

Requirements Engineering:

- takes this **direction and evidence**,
- and produces:
  - **PRDs**,
  - **user stories**,
  - **NFR specs**,
  - **traceability views**,
which can be consumed by:

- design,
- engineering,
- QA/testing,
- operations and support.

Think of it as:

- going from:
  - “We will solve these problems in this order”  
to:
  - “Here is exactly what each release should do, how, and how we will validate it.”

---

### 3. Functional vs Non‑Functional Requirements

#### 3.1 Functional Requirements

Describe:

- **behaviour** of the system,
- what users and other systems can **do** with it.

Examples (digital SME lending):

- “SME owners can submit loan applications online.”
- “Relationship managers can see the current status and missing documents.”
- “The system sends notifications when decisions are available.”

These are often expressed as:

- PRD bullet points (FR‑1, FR‑2, …),
- or **user stories**:
  - “As an SME owner, I want to upload documents, so that I can complete my application.”

#### 3.2 Non‑Functional Requirements (NFRs)

Describe:

- **how well** the system must behave,
- under what **constraints and conditions**.

Typical kinds:

- performance (latency, throughput),
- availability and resilience (uptime, failover),
- security and privacy (auth, encryption, logging),
- usability and accessibility,
- operability (monitoring, alerting, runbooks),
- compliance (auditability, data retention).

Example:

- “For SME application submission, 95% of requests must complete within 3 seconds during peak hours.”

NFRs are critical in enterprises/banks:

- regulators and risk functions care deeply about them,
- they often decide whether a system is **safe and viable**, not just “feature complete.”

---

### 4. PRDs, User Stories, and Acceptance Criteria

You will see three common artifacts:

1. **Product Requirements Document (PRD)**
2. **User Stories**
3. **Acceptance Criteria**

#### 4.1 PRD (Product Requirements Document)

PRD is:

- a **structured narrative document** that:
  - explains context,
  - states goals and non‑goals,
  - describes personas and journeys,
  - lists functional and non‑functional requirements,
  - records dependencies, risks, and open questions.

Use PRDs to:

- give stakeholders a **shared big picture**,
- keep key decisions and rationale in one place.

#### 4.2 User Stories

User stories are:

- **small units of work** in tools like `Jira` or `Azure DevOps`,
- written from a user perspective.

Typical format:

- “As a \<persona>, I want \<capability>, so that \<benefit>.”

They:

- help break PRD requirements into buildable slices,
- anchor discussions on user value.

#### 4.3 Acceptance Criteria

Acceptance criteria:

- specify **conditions that must be true** for a story to be considered “done.”

Often written in **Given/When/Then** form:

- Given \<starting situation>  
- When \<action happens>  
- Then \<expected outcome occurs>.

They:

- guide manual and automated tests,
- reduce ambiguity between product and engineering/QA.

---

### 5. Traceability (Why It Matters)

**Traceability** means you can:

- go from:
  - a business objective or regulatory requirement  
to:
  - the specific PRD sections, user stories, and tests that implement it,
- and back again.

In regulated environments:

- this is often **mandatory** for audits.

Benefits:

- easier impact analysis:
  - “If we change this regulation, which parts of the system and tests are affected?”
- clearer accountability:
  - “Which requirements support this OKR?”
- better risk management:
  - identifies untested or orphan requirements.

Traceability does **not** always require heavy tools:

- can start with:
  - IDs and links,
  - simple tables,
  - consistent naming.

---

### 6. Why Requirements Engineering Is Hard (and Important)

Common challenges:

- different stakeholders use different language,
- people assume “it’s obvious” until it is built incorrectly,
- teams jump straight from roadmap to development,
- NFRs are forgotten until late (performance, security, operability issues).

Good Requirements Engineering:

- surfaces misunderstandings **early**,
- saves:
  - time,
  - money,
  - risk and regulatory pain,
- makes collaboration between:
  - product,
  - design,
  - engineering,
  - QA,
  - and risk/ops
  - **much smoother**.

---

### 7. Connections to Other Files

- `02-objectives.md` – what a good Requirements Engineering phase must achieve.
- `03-workflow.md` – step‑by‑step process from scope to traceability.
- `05-prd-structure-and-authoring.md` – detailed guidance on PRDs.
- `06-user-stories-and-acceptance-criteria.md` – how to write strong stories and criteria.
- `07-non-functional-requirements.md` – deep dive on NFRs.
- `27-glossary.md` – quick reference for terminology used here.

