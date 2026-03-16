## 06 – Option Analysis & Trade‑offs in RFCs

This file explains how to **compare solution options** and document trade‑offs in RFCs.

---

### 1. Why Option Analysis Matters

Without explicit option analysis:

- RFCs become:
  - “here’s my preferred solution” documents,
  - with weak justification.
- stakeholders:
  - struggle to trust the decision,
  - may feel their concerns weren’t considered.

Good option analysis:

- shows:
  - you explored realistic alternatives,
  - you understand trade‑offs,
  - you are transparent about risks.

---

### 2. Defining Options

An “option” should be:

- a **distinct architectural or technical approach**, e.g.:
  - build vs buy vs reuse,
  - central service vs embedded logic in each product,
  - relational DB vs event‑sourced store,
  - monolith vs microservices vs modular monolith.

Bad options:

- strawman options nobody would realistically choose,
- tiny variations of the same idea.

Aim for:

- 2–3 serious options for significant decisions.

---

### 3. Comparison Dimensions

Common dimensions to compare:

- **Business / User Value**
  - time to value,
  - support for required features,
  - impact on customer or internal users.
- **Cost & Effort**
  - build cost (engineering time),
  - run cost (infrastructure, licenses),
  - change cost (future evolution).
- **Risk & Compliance**
  - security risk,
  - regulatory risk,
  - vendor or lock‑in risk.
- **Technical Fit & Complexity**
  - fit with existing stack and patterns,
  - complexity of integration and migration.
- **Operational Impact**
  - reliability and performance,
  - support and maintenance overhead,
  - monitoring and incident management.

You don’t need exact numbers, but:

- relative ratings and qualitative reasoning.

---

### 4. Simple Comparison Table

Example structure in the RFC:

| Dimension           | Option A – Reuse Existing Platform | Option B – Build New Service | Option C – Buy Vendor Solution |
|---------------------|-------------------------------------|------------------------------|--------------------------------|
| Business Value      | High (faster extensions)           | High (tailored)              | Medium‑High (depends on fit)  |
| Time to Value       | Medium                             | Low (slow)                   | High (if vendor fit is good)  |
| Build Effort        | Medium                              | High                         | Medium (integration)          |
| Run Cost            | Low‑Medium                         | Medium                       | High (licensing)              |
| Security/Compliance | Known, but legacy gaps             | Can design to standards      | Depends on vendor controls    |
| Tech Fit            | High (existing stack)              | High (modern stack)          | Medium                        |
| Operational Impact  | Minimal change, but legacy limits  | New overhead but more control| Shared support with vendor    |

Under the table:

- summarise:
  - key trade‑offs and rationale.

---

### 5. Qualitative Trade‑off Discussion

After tables, add narrative:

- what you are optimising for:
  - speed vs flexibility,
  - cost vs quality,
  - risk reduction vs innovation.
- which risks you accept or avoid:
  - e.g., accepting higher short‑term build effort for long‑term platform benefits.

This discussion:

- helps decision‑makers see:
  - the “shape” of the decision,
  - not just a raw score.

---

### 6. Example – Option Analysis for SME Lending Platform

Options:

- A: extend existing monolithic lending system,
- B: build new modular lending platform,
- C: buy and integrate vendor solution.

Key considerations:

- A:
  - fastest to ship,
  - but deepens legacy,
  - limited on NFRs and regulatory agility.
- B:
  - highest build effort,
  - best long‑term fit,
  - may need phased rollout to manage risk.
- C:
  - medium time to value,
  - vendor risk and ongoing licensing,
  - depends on vendor flexibility for local regulations.

RFC recommendation:

- choose B:
  - with explicit acknowledgement of higher near‑term investment,
  - justified by long‑term strategy and regulatory agility.

---

### 7. Beginner Checklist

- [ ] Have we defined at least **two serious options**?
- [ ] Have we compared options on:
  - [ ] value,
  - [ ] effort/cost,
  - [ ] risk/compliance,
  - [ ] technical fit,
  - [ ] operational impact?
- [ ] Have we clearly explained:
  - [ ] why the chosen option is recommended?
  - [ ] what trade‑offs we are accepting?

If not, strengthen the options section before seeking approval.

---

### Connections to Other Files

- `02-objectives.md` – requirement for explicit options and trade‑offs.
- `05-rfc-structure-and-authoring.md` – where this content lives in the RFC.
- `22-best-practices.md` and `23-common-mistakes.md` – patterns and anti‑patterns for option analysis.

