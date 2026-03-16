## 07 – Diagrams & Technical Content in RFCs

This file explains how to include **diagrams and technical content** in RFCs so they are useful and readable.

---

### 1. Why Diagrams Matter

Text alone:

- is often not enough to explain:
  - system boundaries,
  - data flows,
  - dependencies.

Diagrams:

- provide:
  - shared visual understanding,
  - faster onboarding for new readers,
  - an anchor for deeper technical and risk discussions.

But:

- overly complex diagrams can confuse more than help.

---

### 2. Common Diagram Types in RFCs

- **Context Diagram**
  - shows the system and its external actors/systems.
- **Logical Architecture Diagram**
  - components and how they interact.
- **Deployment / Topology Diagram**
  - where components run (environments, zones, regions).
- **Sequence / Flow Diagram**
  - step‑by‑step interactions for key use cases.
- **Data Flow Diagram**
  - how data moves and is transformed.

You do **not** need all types in every RFC; pick the ones that add clarity.

---

### 3. Principles for Good Diagrams

- **Keep it simple**:
  - show only what is needed for the decision.
- **Be consistent**:
  - re‑use icons, colours, and naming conventions.
- **Highlight boundaries**:
  - trust boundaries,
  - domains,
  - external vs internal systems.
- **Label clearly**:
  - arrows,
  - interfaces,
  - key protocols/data formats when relevant.

Tools:

- `PlantUML`, `Mermaid`,
- `Draw.io`, `Lucidchart`, `Miro`, `FigJam`.

---

### 4. Technical Content Do’s and Don’ts

**Do:**

- explain:
  - component responsibilities,
  - key APIs and contracts at a high level,
  - critical data models conceptually.
- specify:
  - important NFR details,
  - assumptions and constraints.

**Don’t:**

- paste:
  - full API specs or schemas (link instead),
  - giant code blocks,
  - deeply nested diagrams that require zoom gymnastics.

RFCs should:

- be **entry points** to more detailed technical documentation,
- not replacements for it.

---

### 5. Example: Minimal Diagram Set for a Typical RFC

For a new service in an existing ecosystem, you might include:

1. **Context Diagram**
   - new service, calling clients, key dependencies (e.g., auth, data stores, external APIs).
2. **Logical Architecture**
   - main internal components:
     - API layer, business logic, storage, messaging consumers, etc.
3. **Sequence Diagram for 1–2 Critical Flows**
   - e.g., “SME loan application submission,”
   - e.g., “credit decisioning request to risk engine.”

This is often enough for:

- architecture reviews,
- early security and NFR discussions.

---

### 6. Linking Diagrams to Other Artifacts

In RFCs:

- embed:
  - simplified diagrams,
  - plus links to:
    - higher‑resolution versions,
    - editable source files.

Also link:

- from diagrams to:
  - component design docs,
  - API specifications,
  - data model documentation,
  - runbooks and operational docs.

This:

- avoids duplication,
- makes it easier to keep content in sync.

---

### 7. Beginner Checklist

- [ ] Does the RFC include:
  - [ ] at least one diagram for system/context?
  - [ ] diagrams for the most critical flows or components?
- [ ] Are diagrams:
  - [ ] simple enough to understand quickly?
  - [ ] using consistent naming and symbols?
  - [ ] highlighting important boundaries (trust, domains)?
- [ ] Are detailed specs:
  - [ ] linked instead of fully copy‑pasted?

If not, add or simplify diagrams before sharing widely for review.

---

### Connections to Other Files

- `05-rfc-structure-and-authoring.md` – the section where diagrams belong.
- `08-security-compliance-and-risk-in-rfcs.md` – diagrams support threat modelling and risk discussions.
- `9-architecture-design` phase – where diagrams are expanded into more detailed designs.

