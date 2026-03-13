## 01 – Concepts: What Is a Feasibility Study?

### 1. Simple Definition (For Beginners)

A **Feasibility Study** is a structured way to answer:

> “Is this solution realistically buildable, operable, and compliant in our environment, with acceptable risk?”

It turns:

- business intent and high‑level solutions  
into:
- a **clear view of what is technically and operationally possible**, under:
  - technology constraints,
  - security and regulatory rules,
  - organizational and capacity limits.

If Business Case & ROI asks “Is this worth doing?”, Feasibility asks “Can we actually do it, and how?”.

---

### 2. Why We Need Feasibility (Especially in Enterprises/Banks)

In complex organizations:

- many projects fail or stall not because:
  - the idea was bad,
  - the market didn’t exist,
but because:
  - legacy systems,
  - regulatory constraints,
  - operational realities,
  - or security requirements
made the intended solution **much harder than expected**.

Feasibility work:

- reduces the risk of:
  - discovering “this won’t work” late in delivery,
  - costly re‑architecting,
  - last‑minute regulatory or security blockers.

---

### 3. Main Feasibility Dimensions

1. **Technical Feasibility**
   - Can our technology stack and architecture support the solution?
   - Can we integrate required systems and data sources?
   - Can we meet performance, scalability, and resilience needs?

2. **Operational Feasibility**
   - Can our people and processes support this, day‑to‑day?
   - What changes to roles, procedures, and SLAs are needed?

3. **Security & Privacy Feasibility**
   - Can we protect data and systems appropriately?
   - Are there show‑stopping security, privacy, or data residency constraints?

4. **Legal & Regulatory Feasibility**
   - Is the solution allowed under:
     - laws,
     - regulations,
     - internal policies?
   - Do we need licenses or approvals?

5. **Organizational & Change Feasibility**
   - Do we have:
     - the right skills,
     - capacity,
     - and change appetite?
   - Are there competing programs that will interfere?

You don’t have to use these exact labels, but you should cover these **areas of reality**.

---

### 4. Feasibility vs Design vs Delivery Planning

- **Feasibility Study**
  - focuses on:
    - constraints,
    - risks,
    - and viable option space.
  - output: feasible solution directions, risk register, constraints doc.

- **Solution / Architecture Design**
  - specifies:
    - detailed architecture and components,
    - APIs and contracts,
    - data models, etc.

- **Delivery Planning**
  - breaks work into:
    - phases and milestones,
    - teams and sprints,
    - release plans.

Feasibility sits **before** detailed design and planning, but often overlaps and iterates with them.

---

### 5. Example: SME Digital Lending – Feasibility Questions

Given:

- business case approved for:
  - digital SME lending journey.

Feasibility asks:

- **Technical**
  - Can our core banking and credit systems:
    - support near real‑time decisions?
  - Which integration patterns are viable (APIs vs batch)?
  - Do we have scalable risk models and data pipelines?

- **Operational**
  - How will branch and relationship managers work with digital flows?
  - What happens with:
    - borderline cases,
    - exceptions,
    - and manual overrides?

- **Security & Privacy**
  - How will sensitive documents and data be stored and transmitted?
  - What new attack surfaces are introduced (e.g., online application fraud)?

- **Legal & Regulatory**
  - Are there regulations limiting:
    - fully digital approvals,
    - use of certain data sources?

- **Change**
  - Do we have:
    - the teams needed,
    - change capacity at branches and ops?

Answers to these guide:

- solution option choices,
- risk mitigation plans,
- and whether to adjust scope or phasing.

---

### 6. Mental Models for Beginners

#### 6.1 “Reality Check”

- Feasibility = **structured reality check**.
- It asks:
  - “What can go wrong?”
  - “What’s hard here?”
  - “What’s impossible given our constraints?”
  - “What do we have to change or build first?”

#### 6.2 “Constraint and Risk Mapping”

- Instead of only asking:
  - “What solution do we want?”  
Feasibility also maps:
  - constraints (hard limits),
  - risks (things that may go wrong),
  - dependencies (things we rely on).

This map becomes:

- a key tool for:
  - architects,
  - PMs,
  - risk/security,
  - and leadership.

---

### 7. Connections to Other Files

- `02-objectives.md` – defines what a good feasibility study should achieve.
- `03-workflow.md` – shows the practical steps from inputs to outputs.
- `04-feasibility-dimensions.md` – deeper dive into each dimension.
- `22-risk-register-and-mitigation.md` – structured way to capture and manage risks found.
- `27-glossary.md` – definitions for core feasibility and risk terms.

