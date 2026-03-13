## 13 – Roles and Positions in Feasibility Studies

This file explains **who participates** and who is accountable in Feasibility.

We cover:

- A. Core accountable roles
- B. Supporting roles
- C. Example setups
- D. RACI-style overview

---

### A. Core Accountable Roles

#### 1. Architecture / Engineering Lead

Responsibilities:

- lead technical feasibility assessment,
- consolidate architecture options and recommendations,
- ensure alignment with standards.

Accountability:

- for **technical soundness** of the recommended direction.

---

#### 2. Product Manager

Responsibilities:

- ensure feasibility work remains tied to:
  - user problems,
  - business goals,
  - and business case.
- mediate trade‑offs between:
  - feasibility,
  - scope,
  - value.

Accountability:

- for solution direction from a **product and value** perspective.

---

#### 3. Business / Operations Owner

Responsibilities:

- provide:
  - operational context,
  - process impacts,
  - business constraints.
- own:
  - operational feasibility findings and decisions.

---

### B. Supporting Roles

#### 4. Security & Privacy

Responsibilities:

- security and privacy assessments,
- recommendations for controls and mitigations.

---

#### 5. Legal & Compliance

Responsibilities:

- legal and regulatory feasibility checks,
- identification of approval needs and constraints.

---

#### 6. Risk Management

Responsibilities:

- view initiative through risk frameworks,
- help quantify and categorize risks.

---

#### 7. Data / BI

Responsibilities:

- provide:
  - system and data inventories,
  - performance metrics,
  - incident and risk statistics.

---

#### 8. Platform & Infrastructure Leads

Responsibilities:

- infrastructure and platform feasibility,
- capacity and NFR implications.

---

### C. Example Setup (Banking)

For a large initiative (e.g., digital SME lending):

- **Architecture Lead** (core lending),
- **PM** (SME lending),
- **Business Ops Owner** (SME operations),
- **Security Architect**,
- **Data Architect / BI Lead**,
- **Compliance Officer** (lending and KYC/AML),
- **Risk Manager** (credit/operational),
- **Platform Lead** (integration/middleware).

They form a **Feasibility working group**, reporting to:

- product steering committee,
- architecture board,
- risk committee (as needed).

---

### D. RACI-Style Overview (Simplified)

| Activity                            | Arch Lead | PM  | Biz/Ops | Security | Legal/Comp | Risk | Data/BI | Platform |
|-------------------------------------|----------|-----|---------|----------|------------|------|---------|----------|
| Define feasibility scope            | R        | A   | C       | C        | C          | C    | C       | C        |
| Baseline architecture & processes   | R        | C   | R       | C        | C          | C    | R       | R        |
| Identify options                    | R        | R   | C       | C        | C          | C    | C       | C        |
| Technical assessment                | A        | C   | C       | C        | C          | C    | C       | R        |
| Operational assessment              | C        | C   | A       | C        | C          | C    | C       | C        |
| Security & privacy assessment       | C        | C   | C       | A        | C          | C    | C       | C        |
| Legal & regulatory assessment       | C        | C   | C       | C        | A          | C    | C       | C        |
| Risk register creation              | R        | C   | C       | C        | C          | A    | C       | C        |
| Feasibility report & recommendation | A        | A   | C       | C        | C          | C    | C       | C        |

R = Responsible, A = Accountable, C = Consulted.

---

### Connections to Other Files

- `14-skills.md` – skills needed in these roles.
- `03-workflow.md` – where each role contributes in the process.

