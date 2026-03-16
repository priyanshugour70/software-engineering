## 02 – Objectives of RFC / Technical Proposal Phase

This file describes **what success looks like** for the RFC / Technical Proposal phase.

---

### 1. Primary Objective (One Sentence)

Create **clear, well‑reasoned technical proposals** that:

- explore viable options,
- make trade‑offs explicit,
- secure the right feedback and approvals,
- and provide a solid basis for detailed design and implementation.

---

### 2. Key Outcomes You Should Achieve

#### 2.1 Shared Understanding of the Problem & Context

You should have:

- a concise description of:
  - the business and technical context,
  - the current state limitations,
  - why a change is needed now.

Outcome:

- all stakeholders (product, engineering, security, risk, ops) can **articulate the problem** in similar terms.

---

#### 2.2 Well‑Explained Solution Options & Trade‑offs

You should:

- lay out:
  - at least one serious alternative (not just a strawman),
  - pros and cons of each option,
  - how they compare on:
    - value and impact,
    - complexity and cost,
    - risks (technical, security, compliance, operational).

Outcome:

- reviewers can see:
  - **why** the chosen option is recommended,
  - what was considered and rejected.

---

#### 2.3 Explicit Handling of Security, Compliance & Operational Concerns

You should:

- highlight:
  - key security threats and controls,
  - compliance implications (e.g., data protection, KYC/AML),
  - operational readiness (monitoring, deployment, reliability).

Outcome:

- security, risk, and ops stakeholders:
  - see their concerns addressed early,
  - can sign off with confidence or propose targeted conditions.

---

#### 2.4 Clear Decisions, Approvals & Next Steps

You should:

- end the RFC with:
  - an explicit decision (accepted, rejected, superseded, etc.),
  - list of approvers and their roles,
  - conditions or follow‑ups (e.g., POC required, re‑review after pilot).

Outcome:

- no ambiguity about:
  - which option was chosen,
  - who owns the decision,
  - what comes next (architecture design, implementation planning, etc.).

---

### 3. Secondary Objectives

#### 3.1 Create Durable Decision Records

RFCs should:

- remain valuable:
  - months or years later,
  - when:
    - new team members join,
    - similar decisions arise,
    - audits or post‑mortems occur.

Outcome:

- less re‑litigation of old decisions,
- faster onboarding and system understanding.

#### 3.2 Improve Architectural Consistency & Reuse

Through RFCs you should:

- surface:
  - opportunities to reuse platforms or patterns,
  - conflicts with existing architectures.

Outcome:

- fewer one‑off solutions,
- stronger alignment with enterprise architecture.

---

### 4. What “Good” vs “Bad” RFCs Look Like

#### 4.1 “Good”

- concise summary and problem statement,
- realistic options with genuine trade‑off discussion,
- explicit NFR, security, and compliance sections,
- comments and feedback threads that show engagement,
- clear decision and status updates.

#### 4.2 “Bad”

- solution jumped to immediately with little context,
- no serious alternatives considered,
- missing or hand‑wavy security/compliance sections,
- unclear status (draft forever),
- decisions made elsewhere and not reflected in the RFC.

---

### 5. Checklist: Have We Met the Objectives for This RFC?

Before marking an RFC as *Accepted* (or equivalent):

- [ ] Does it clearly describe **context and problem**?
- [ ] Does it define **goals and non‑goals**?
- [ ] Does it present at least one **considered alternative** with trade‑offs?
- [ ] Are **security, compliance, and operational** aspects addressed?
- [ ] Are **decisions and approvals** recorded, with dates and names?
- [ ] Are **next steps** and owners clear?

If several boxes are unchecked, continue iterating with reviewers before considering the RFC complete.

---

### Connections to Other Files

- `01-concepts.md` – background on what RFCs are and why they exist.
- `03-when-to-use-an-rfc.md` – deciding when an RFC is the right tool.
- `04-workflow.md` – concrete process to reach these objectives.
- `26-checklists.md` – shorter checklists derived from this file for everyday use.

