## 11 – Roles and Positions in Requirements Engineering

This file explains **who is involved** in Requirements Engineering, what they do, and how they collaborate.

We focus on:

- product and analysis roles,
- engineering, QA, and design,
- risk, compliance, and operations partners.

---

### 1. Product & Analysis Roles

#### 1.1 Product Manager / Product Owner

Responsibilities:

- own:
  - problem and outcome definition,
  - scope decisions for increments.
- ensure:
  - requirements reflect product strategy and user needs,
  - trade‑offs are visible and agreed.
- maintain:
  - PRDs (with help),
  - backlog of epics and stories (with acceptance criteria).

In Requirements Engineering:

- lead:
  - scoping,
  - initial PRD drafting,
  - story creation and refinement,
  - stakeholder alignment.

#### 1.2 Business Analyst / Requirements Engineer (where present)

Responsibilities:

- specialize in:
  - capturing and structuring requirements,
  - modelling processes and data,
  - managing traceability.
- work closely with:
  - PM/PO,
  - engineering,
  - operations,
  - risk/compliance.

In regulated enterprises/banks:

- often:
  - play a key role linking:
    - regulatory requirements,
    - to system behaviours and tests.

---

### 2. Engineering & Architecture Roles

#### 2.1 Tech Lead / Engineering Lead

Responsibilities:

- represent:
  - technical feasibility,
  - constraints and opportunities.
- shape:
  - NFRs (performance, resilience, security),
  - technical slicing of requirements into implementable chunks.
- review:
  - PRDs and stories,
  - suggest improvements or simplifications.

#### 2.2 Architects (Solution / Domain / Enterprise)

Responsibilities:

- ensure:
  - requirements align with target architecture and standards.
- highlight:
  - cross‑system impacts,
  - integration constraints,
  - platform and data considerations.
- collaborate on:
  - NFRs,
  - feasibility,
  - mitigation of technical risk.

---

### 3. QA / Testing Roles

#### 3.1 QA Engineers / Testers

Responsibilities:

- derive:
  - test cases and suites from requirements and stories.
- validate:
  - functional behaviour,
  - NFRs (where feasible: performance, security, usability).
- help:
  - refine acceptance criteria,
  - identify missing edge cases.

In Requirements Engineering:

- act as:
  - “quality advocates,” checking:
    - clarity,
    - testability,
    - completeness.

#### 3.2 Test Automation Engineers

Responsibilities:

- implement:
  - automated tests aligned with:
    - acceptance criteria,
    - regression needs.
- provide:
  - feedback on:
    - which scenarios are automation candidates,
    - which need clearer requirements.

---

### 4. Design Roles

#### 4.1 UX / UI Designers

Responsibilities:

- create:
  - interaction designs,
  - visual designs,
  - prototypes.
- ensure:
  - usability,
  - accessibility,
  - consistency across journeys.

In Requirements Engineering:

- help:
  - define personas and journeys,
  - identify missing cases,
  - bridge:
    - user goals,
    - functional requirements,
    - and NFRs (especially usability).

#### 4.2 Service Designers (where present)

Responsibilities:

- map:
  - end‑to‑end services,
  - front‑stage and back‑stage interactions,
  - handoffs between teams and systems.

They:

- uncover:
  - operational and process requirements,
  - not just UI behaviour.

---

### 5. Risk, Compliance & Operations Roles

#### 5.1 Risk & Compliance

Responsibilities:

- interpret:
  - regulatory requirements into product and system implications.
- validate:
  - that requirements and designs:
    - meet policy and regulatory expectations.

In Requirements Engineering:

- review:
  - specific sections of PRDs and NFRs,
  - controls and logging requirements,
  - traceability to regulations.

#### 5.2 Operations / Support / SRE

Responsibilities:

- run:
  - live service,
  - incident response,
  - support processes.
- advise on:
  - operability requirements,
  - monitoring and alerting,
  - runbooks.

In Requirements Engineering:

- ensure:
  - operability NFRs are defined,
  - support and back‑office use cases are captured.

---

### 6. Collaboration Patterns

Good patterns:

- **Joint refinement sessions**:
  - PM/PO, BA, tech lead, QA, and design together.
- **Early risk/compliance involvement**:
  - in PRD reviews,
  - not just final sign‑off.
- **Ops/SRE input on NFRs**:
  - especially for:
    - monitoring,
    - logging,
    - incident response.

Aim:

- reduce hand‑offs where people receive a “finished spec” with no chance to shape it.

---

### 7. Beginner Checklist

- [ ] Do we know:
  - [ ] who owns PRDs and requirements?
  - [ ] who is responsible for NFR definitions?
  - [ ] who must review requirements before baselining?
- [ ] Are:
  - [ ] QA and design actively involved in story refinement?
  - [ ] risk/compliance and ops consulted for relevant areas?
- [ ] Is there:
  - [ ] at least one forum where all of these roles discuss requirements together?

If not, consider adjusting your process and meetings to bring these roles together earlier.

---

### Connections to Other Files

- `12-skills.md` – skills these roles need to work well in Requirements Engineering.
- `24-governance-and-change-control.md` – governance structures where these roles participate.
- `22-best-practices.md` – collaboration practices for high‑quality requirements work.

