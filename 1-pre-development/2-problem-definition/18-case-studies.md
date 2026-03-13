## 18 – Case Studies: End‑to‑End Problem Definition

These constructed case studies show **how Problem Definition works in practice**, especially in banking/enterprise settings.

We cover:

- Case Study 1: SME Digital Onboarding
- Case Study 2: Payment Status Visibility for SMEs

Each follows the stages in `03-workflow.md`.

---

### Case Study 1 – SME Digital Onboarding

#### Context

The bank wants to **increase SME digital onboarding** and reduce dependency on branches. Market Opportunity Discovery identified:

- high potential in digital SME accounts,
- candidate opportunity: “Enable SMEs to open accounts fully online.”

#### Stage 1 – Intake & Context Review

Inputs:

- Opportunity brief,
- metrics showing:
  - 40% of SME onboarding starts online,
  - but only 20% complete online; the rest switch to branch.

PM and Business Sponsor agree:

- focus on **existing SMEs in Country X**,
- aim to clarify:
  - why abandonment is high,
  - what exact problem to solve first.

#### Stage 2 – Stakeholder Discovery

Interviews with:

- call center lead,
- branch manager,
- onboarding operations,
- risk/compliance,
- digital engineering.

Key insights:

- SMEs:
  - often start online, then call for help,
  - are confused by document requirements.
- Branch staff:
  - advise SMEs to “just come into branch” when online fails.
- Risk/compliance:
  - emphasize mandatory documents but agree wording is “internal‑ish”.

Themes:

- confusion at **document upload**,
- incomplete submissions,
- hand‑offs to branch not traced in analytics.

#### Stage 3 – Current State & Data Review

Data analyst pulls:

- funnel:
  - Step 1 (start) → Step 2 (basic info) → Step 3 (documents) → Step 4 (submit) → Step 5 (approved).
- results:
  - biggest drop between Steps 2 and 3 (documents),
  - many sessions time out at Step 3.

Ops shares:

- manual logs showing:
  - repeated “back‑and‑forth” requests for missing documents,
  - average of 2 email exchanges per case.

#### Stage 4 – Problem Framing & Drafting

Using 5 Whys and current vs desired state:

- Draft problem statement:

> “Existing SME customers in Country X who start online onboarding for additional accounts frequently abandon at the document upload step because requirements are unclear and not tailored to SME realities, leading to a 50% drop‑off at this step and increased manual follow‑ups by operations and branches.”

Scope:

- In scope:
  - document requirements and communication for existing SME customers in Country X,
  - online flow and associated email communication.
- Out of scope:
  - new‑to‑bank SMEs,
  - other countries.

Desired outcomes:

- Reduce abandonment at Step 3 from 50% → 20%.
- Reduce manual back‑and‑forth exchanges by 40%.

#### Stage 5 – Validation & Refinement

Activities:

- 8 SME interviews:
  - confirm confusion stems from:
    - unclear wording,
    - unpredictable additional document requests.
- Workshop with risk/compliance:
  - confirm minimum documents required,
  - identify optional docs that could be removed or requested later.

Updated problem statement includes:

- explicit mention of:
  - mandatory vs optional documents,
  - need to maintain regulatory compliance while reducing overload.

#### Stage 6 – Finalization & Handover

Artifacts:

- Problem Statement Document:
  - metrics, scope, constraints, outcomes.
- Links to:
  - funnel dashboard,
  - interview notes,
  - policy documents.

Handover:

- to:
  - UX/Research team,
  - design squad,
  - engineering lead.

They now work on:

- solution options (e.g., clearer doc checklists, dynamic requirements, progress indicators) **anchored to the problem**.

---

### Case Study 2 – Payment Status Visibility for SMEs

#### Context

Support tickets and NPS comments indicate that **SMEs are confused about payment status** when paying suppliers, leading to re‑tries and duplicate payments.

Opportunity from phase 1:

- “Improve SME experience and trust in outbound payments.”

#### Stage 1 – Intake & Context Review

PM reviews:

- support ticket categories:
  - many with “payment status unknown”,
  - some with “duplicate payment”.
- analytics:
  - payment failure rate ~2.5%,
  - but unclear how many duplicates occur.

Scope note:

- focus on **domestic SME payments in Country X** via online banking.

#### Stage 2 – Stakeholder Discovery

Interviews with:

- call center agents,
- payments operations,
- channel PM,
- risk/compliance.

Insights:

- System stores detailed status codes,
  - but UI shows only “processing” for many states.
- Ops:
  - see multiple re‑tries within minutes due to unclear UI.
- Risk/compliance:
  - highlight need to show statuses accurately, not over‑promise finality.

#### Stage 3 – Current State & Data Review

Data:

- ~5% of SME outbound payment sessions include at least one re‑try.
- Duplicate payments identified and reversed cost:
  - manual effort,
  - occasional customer dissatisfaction.

Current UI:

- “Processing” label covers:
  - queued,
  - awaiting batch,
  - in progress,
  - under review.

#### Stage 4 – Problem Framing & Drafting

Draft problem statement:

> “SME customers making domestic payments in Country X frequently see a generic ‘processing’ status for extended periods without clear indication of what this means or whether they should wait or retry, leading to confusion, re‑tries, and duplicate payments that require manual reversals and support intervention.”

Scope:

- In scope:
  - SME segment,
  - domestic credit transfers in Country X,
  - online banking channel,
  - status display and related notifications.

Desired outcomes:

- Reduce payment re‑try rate by 50%.
- Reduce duplicate payments by 60%.
- Cut related support tickets by 40%.

#### Stage 5 – Validation & Refinement

User interviews:

- SMEs report:
  - “If it says processing for too long, I don’t know if I should send again.”

Ops:

- confirm cost of manual reversals and customer handling.

Risk/compliance:

- highlight:
  - statuses where showing “final” confirmation is not allowed until settlement,
  - statuses where more descriptive, safe wording is possible.

Problem statement updated to:

- mention **need to respect settlement finality and fraud checks**,
- specify which statuses are realistic targets for improvement.

#### Stage 6 – Finalization & Handover

Problem Definition outputs:

- final problem statement,
- metrics and baselines,
- constraints,
- affected systems:
  - payments engine,
  - online banking UI,
  - notification system.

Handover to:

- product + design + engineering squad.

They explore:

- redesigning:
  - status labels,
  - timelines,
  - notifications,
without compromising:

- risk controls,
- compliance.

---

### Connections to Other Files

- `03-workflow.md` – stages referenced in each case.
- `10-documents.md` – describes the artifacts produced.
- `19-real-world-examples.md` – shorter scenarios focused on individual techniques.

