## 01 – Concepts: What Is Problem Definition?

### 1. Simple Definition (For Complete Beginners)

**Problem Definition** is the process of **clearly describing what is wrong and for whom** before deciding how to fix it.

In very simple terms:

- A **problem** is the gap between:
  - the **current state** (how things are today), and
  - the **desired state** (how things should be).
- Problem Definition is about **understanding and describing that gap** so everyone sees the same picture.

If you skip this, teams often:

- build features nobody really needs,
- fix symptoms instead of root causes,
- argue about scope and priorities later.


### 2. Problem vs Opportunity vs Solution

It is important to **not mix these three**:

- **Opportunity** (from phase 1):
  - “There is a potential to create value in this space.”
  - Example: “Digital SME lending is a big growth area for us.”

- **Problem** (this phase):
  - “Here is the specific pain or issue we need to address.”
  - Example: “SME loan applicants face a slow, opaque process that causes drop‑offs and complaints.”

- **Solution** (later phases):
  - “Here is one way we could address the problem.”
  - Example: “Build an online application flow with real‑time status updates.”

In Problem Definition, you stay focused on:

- **who** is struggling,
- **what** they are struggling with,
- **why** it matters,
- **how we will know we fixed it**.


### 3. Problem vs Symptom vs Root Cause

When people talk about “the problem”, they often mix:

- **Symptoms**
  - What you **see or feel**.
  - Example: “Many SME applications are abandoned halfway.”

- **Root Causes**
  - Underlying reasons **why** the symptom exists.
  - Example: “The document upload step is confusing and requires formats SMEs don’t have ready.”

- **Problem Definition**
  - Should acknowledge both:
    - key symptoms,
    - and the most important root causes (as far as you currently understand them).

Example progression:

- Symptom: “High abandonment in online onboarding.”
- First cause: “Users drop at the document step.”
- Deeper cause: “We ask for many documents that SMEs don’t understand, in a single long form.”
- Problem statement:  
  “SME owners trying to open an account online abandon the process at the document upload step because the requirements are unclear and overwhelming, leading to low completion rates and extra load on branches.”


### 4. Elements of a Good Problem Statement

A good problem statement usually includes:

1. **Who** – the target users and important stakeholders.
2. **What** – the current situation and pain.
3. **Why it matters** – consequences for users and for the business.
4. **Where and when** – the context in which the problem appears (journey, channel, segment).
5. **How we’ll know it is solved** – measurable outcomes or success criteria.

Simple template:

> “As a **[who]**, I struggle with **[what]** in **[context]**, which leads to **[impact]** for me and **[impact]** for the organization. We will know we have solved this when **[measurable outcomes]**.”


### 5. Why Problem Definition Matters in Enterprises and Banks

In large organizations and especially in **regulated sectors**:

- Many teams and systems are involved in any change.
- Regulations and risk constraints limit what is possible.
- Wrong or vague problem definitions can waste **huge budgets**.

Good Problem Definition:

- **Aligns stakeholders**
  - business, product, engineering, risk, operations see the **same problem**.
- **Avoids rework**
  - teams don’t start design or build only to be blocked later by constraints that were known but not captured.
- **Enables better trade‑offs**
  - when constraints appear, you can ask:
    - “Does this compromise still solve the problem we defined?”


### 6. Example: SME Digital Lending Problem Definition (Simplified)

Opportunity from phase 1:

- “Grow SME loan volume by offering faster, digital access to credit.”

Problem Definition might produce:

- **Who**
  - “Small business owners with existing accounts who apply for loans between 50k and 500k.”

- **What / Symptoms**
  - “They must visit branches multiple times, provide paper documents, and wait several days for updates.”
  - “They often don’t know what documents are required in advance.”

- **Why it matters**
  - For SMEs:
    - lost time away from running the business,
    - anxiety about the status of their application.
  - For the bank:
    - lost deals to faster competitors,
    - high manual processing cost,
    - high call center volume about status.

- **Context**
  - Applies to:
    - SMEs in Country X,
    - applying via branches or partially via online forms.

- **Success criteria (high‑level)**
  - “Time to decision reduced from 5 days to under 2 hours.”
  - “Application completion rate increased from 60% to 80%.”
  - “Loan‑status related calls reduced by 30%.”

This gives downstream teams a **clear target** to design and build against.


### 7. How Problem Definition Fits into the Bigger Picture

Viewed across pre‑development:

1. **Market Opportunity Discovery**
   - “We think there is value in area X.”
2. **Problem Definition**  ← *this folder*
   - “Here is the **specific problem** we must solve inside that area.”
3. **User & Market Research**
   - “Let’s deeply understand users’ context around this problem.”
4. **Business Case & ROI**
   - “Is it worth solving now, at what scale, with which approach?”
5. **Feasibility & Design**
   - “How can we solve it, and what are the trade‑offs?”

Problem Definition is the **bridge** between high‑level ideas and detailed research/design.


### 8. Mental Models for Beginners

#### 8.1 “Problem as a Contract”

Think of a problem statement as a **contract**:

- Between:
  - product,
  - business,
  - engineering,
  - risk,
  - operations.
- It says:
  - “If we solve **this**, and **these metrics** change, we will consider the work successful.”

#### 8.2 “Zoom In from the Opportunity”

- Start from the **opportunity statement**.
- Ask:
  - “Within this space, what is the **most painful or impactful thing** we could tackle first?”
- Narrow your focus until you have a problem that is:
  - meaningful,
  - but small enough to be **addressed in a realistic project**.


### 9. Connections to Other Files

- `02-objectives.md` – what “good” Problem Definition achieves.
- `03-workflow.md` – the concrete steps to go from opportunity to problem package.
- `04-frameworks.md` – thinking tools (5 Whys, current/desired, etc.) to use when framing problems.
- `16-anti-patterns-vs-good-problems.md` – many before/after comparisons of weak vs strong problem statements.
- `25-glossary.md` – definitions of key terms used here.

Start with this file if you are new, then follow the sequence `02` → `03` → `04` to gain a strong foundation.

