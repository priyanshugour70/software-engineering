## 01 – Concepts: RFC / Technical Proposal

This file explains the **core concepts** behind RFCs (Requests for Comments) and technical proposals, in a beginner‑friendly way.

---

### 1. Simple Definition

An **RFC (Request for Comments)** or **Technical Proposal** is:

- a **structured document** used to:
  - explain a significant technical change,
  - explore solution options and trade‑offs,
  - and gather feedback and approval.

It is:

- the main tool for **architectural decision‑making** across teams,
- a **historical record** of why a decision was made,
- a bridge between:
  - product/requirements,
  - and architecture/design/implementation.

In many enterprises and banks:

- RFCs support:
  - audits,
  - risk assessments,
  - architecture governance.

---

### 2. Where RFCs Sit in the Overall Flow

By the time you start an RFC, you should already have:

- a **defined problem or opportunity**,
- **requirements** (at least at PRD and epic level),
- **feasibility insights** (from pre‑development),
- **strategic direction and roadmap**.

RFCs sit after Requirements Engineering and before:

- detailed architecture design,
- security review,
- compliance/risk assessment,
- implementation planning.

Think of the sequence as:

- “What we want to achieve” → **requirements**  
- “How we could do it, and which option is best” → **RFC**  
- “How we will concretely design and build it” → **architecture design & implementation**.

---

### 3. What Problems RFCs Solve

Without RFCs (or an equivalent mechanism), organizations face:

- **ad‑hoc decisions**:
  - taken in hallway conversations or chat threads,
  - poorly documented or forgotten.
- **local optimizations**:
  - each team chooses its own patterns,
  - leading to fragmentation and duplication.
- **weak audit trail**:
  - hard to answer:
    - “Why did we choose this architecture?”
    - “Who approved this risk?”
- **misaligned expectations**:
  - security, risk, ops, and product:
    - hear different versions of the proposal,
    - or see it too late.

RFCs help by:

- centralizing the **proposal and discussion**,
- making trade‑offs and approvals **explicit**,
- leaving behind a durable **decision record**.

---

### 4. What Goes into an RFC (Conceptual)

Most RFCs contain:

- **Context & Problem**:
  - why a change is needed,
  - what limitations exist today.
- **Goals & Non‑Goals**:
  - what the proposal aims to address,
  - what it explicitly does not aim to solve.
- **Proposed Solution**:
  - high‑level architecture,
  - components and interactions,
  - technology choices.
- **Alternatives & Trade‑offs**:
  - other options considered,
  - pros and cons,
  - reasons for picking (or rejecting) them.
- **Security, Compliance & Operational Considerations**:
  - threats and controls,
  - data classification and protection,
  - monitoring and SRE implications.
- **Risks & Open Questions**:
  - known risks and mitigations,
  - unresolved topics.
- **Decision & Approvals**:
  - final decision,
  - sign‑offs and conditions.

You can see a detailed template in `05-rfc-structure-and-authoring.md`.

---

### 5. RFCs vs Other Documents

RFCs are **not**:

- requirements documents (PRDs),
- low‑level design docs or specs,
- code review documents,
- project plans.

They **connect** these artifacts:

- from:
  - requirements and strategy (why we need a change),
to:
  - architecture and implementation (how we’re going to do it),
while:

- recording:
  - options,
  - decisions,
  - approvals.

In some organizations:

- a single RFC may:
  - spawn multiple detailed design documents,
  - or be one of several RFCs for a large program.

---

### 6. Why RFCs Matter More in Enterprises/Banks

In large, regulated organizations:

- systems are:
  - complex,
  - interdependent,
  - long‑lived.
- many stakeholders care about:
  - security,
  - compliance,
  - resilience,
  - data integrity,
  - and cost.

RFCs provide:

- a **shared language** for technical decision‑making,
- a way to:
  - surface and resolve conflicts early,
  - ensure compliance and risk concerns are addressed,
  - show regulators and auditors that due process was followed.

---

### 7. Connections to Other Files

- `02-objectives.md` – what “good” RFC work must achieve.
- `03-when-to-use-an-rfc.md` – deciding when an RFC is needed vs when not.
- `04-workflow.md` – end‑to‑end process for creating and managing RFCs.
- `05-rfc-structure-and-authoring.md` – detailed guidance on writing RFCs.
- `27-glossary.md` – quick reference for RFC‑related terms.

