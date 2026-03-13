## 04 – Frameworks for Problem Definition

Frameworks are **thinking tools** that make it easier to frame problems clearly and consistently.

In this file we cover:

- A. 5 Whys
- B. Current vs Desired State
- C. Problem Statement Templates
- D. Jobs‑To‑Be‑Done in Problem Framing
- E. Hypothesis / Problem Trees

You don’t need to use all of them every time. Start with **1–2** and add more as needed.

---

### A. 5 Whys

**Purpose:** Move from **surface symptoms** to **deeper causes**.

Basic idea:

- Start with a problem statement.
- Ask “**Why?**” repeatedly (often 3–5 times) to dig deeper.

Example (SME onboarding):

1. Problem: “Many SMEs abandon online onboarding.”
2. **Why?** – “Because they get stuck at document upload.”
3. **Why?** – “Because they don’t understand which documents are required.”
4. **Why?** – “Because our UI lists internal document names, not customer‑friendly ones.”
5. **Why?** – “Because requirements were copied directly from policy docs without UX review.”

How it helps:

- Reveals that:
  - root cause is not just “customers are lazy”,
  - but **how we communicate requirements**.

Use in Problem Definition:

- After mapping symptoms, run 5 Whys with:
  - stakeholders,
  - data,
  - customer insights,
to identify the **level of problem** you want to define (symptom vs root).

---

### B. Current vs Desired State

**Purpose:** Clearly describe the **gap** between today and the future you want.

Structure:

- **Current state**
  - How things work today.
  - Metrics and qualitative descriptions.
- **Desired state**
  - What would be true if the problem were solved.
  - Target metrics and experience.

Example:

- Current state:
  - “On average, SME onboarding takes 3 days, requires 2 branch visits, and 30% of applications are abandoned.”
- Desired state:
  - “Onboarding takes under 30 minutes, zero branch visits for most SMEs, and abandonment is under 10%.”

How it helps:

- Makes the **problem and goal concrete**.
- Helps align on **ambition level** (target state).

Use:

- Include a short “current vs desired state” section in every problem statement.

---

### C. Problem Statement Templates

**Purpose:** Ensure all key elements (who, what, why, context) are covered.

Simple template 1 (persona‑style):

> “As a **[who]**, I struggle with **[what]** when **[when/where]**, which causes **[impact on me]** and **[impact on organization]**. We will know this is solved when **[measurable outcomes]**.”

Simple template 2 (organization‑oriented):

> “Our **[segment]** customers and **[internal stakeholders]** experience **[current issues]** in **[context/journey]**, leading to **[business and user impacts]**. We aim to reduce **[baseline metrics]** to **[targets]** by **[timeframe]** while respecting **[key constraints].**”

Usage tips:

- Write the first draft using plain language.
- Refine with stakeholders until they agree:
  - “Yes, this describes our situation.”

---

### D. Jobs‑To‑Be‑Done (JTBD) in Problem Framing

**Purpose:** Focus on the **underlying job** users are trying to accomplish, not just process steps.

JTBD statement:

> “When **[situation]**, I want to **[job]**, so I can **[desired outcome].**”

Example:

- When:
  - “I have to pay suppliers and salaries at month end,”
- I want to:
  - “know whether I will have enough cash,”
- So I can:
  - “avoid bounced payments and keep my relationships intact.”

Use in Problem Definition:

- Combine JTBD with current vs desired state:
  - define what job is **not well supported** today,
  - which part of that job your problem will address.

Example problem framing:

- “SME owners cannot easily see if they will have enough cash for upcoming obligations, forcing them to guess or manually build spreadsheets, which leads to mistakes and stress.”

---

### E. Hypothesis / Problem Trees

**Purpose:** Break a complex problem area into **sub‑problems and hypotheses** in a visual way.

Structure:

- Top node: **primary problem**.
- Branches: contributing factors or sub‑problems.
- Leaves: specific hypotheses about causes or constraints.

Example (textual version):

- Root problem:
  - “SME loan conversion is low.”
  - Branches:
    - “Few applications started.”
    - “Many applications abandoned.”
    - “Many applications rejected.”
  - Under “abandoned”:
    - “Document requirements unclear.”
    - “Process too slow.”
    - “Digital channels broken for some segments.”

Use:

- In workshops to:
  - decompose a broad opportunity into **manageable problem candidates**,
  - choose **which branch** to focus on for this Problem Definition cycle.

---

### How to Choose Frameworks (Beginner Guidance)

For most problems:

- Start with:
  - **Problem statement template**,
  - **Current vs desired state**,
  - **5 Whys** on key symptoms.
- Add:
  - **JTBD** when user context is unclear,
  - **Hypothesis trees** when the problem space is broad and complex.

---

### Connections to Other Files

- `03-workflow.md` – shows when in the process to use each framework.
- `05-research-methods.md` – provides methods to gather the inputs these frameworks need.
- `16-anti-patterns-vs-good-problems.md` – shows examples of strong vs weak problem statements, often framed with these tools.

