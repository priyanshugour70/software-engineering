## Problem Definition

### Overview

**Problem Definition** transforms broad opportunities into **clear, structured problem statements**. It describes **who** is affected, **what** is wrong, **why** it matters, and **what success looks like**. In enterprises, this step avoids building features that solve the wrong problem or only address symptoms.

Problem Definition is solution-agnostic; it frames the problem so multiple solution options can be evaluated later.


### Objectives

- **Clarify the core problem** and differentiate it from symptoms.
- **Define scope and boundaries** of the problem to be addressed.
- **Align stakeholders** on what needs to be solved and why.
- **Identify constraints and assumptions** early.
- **Establish measurable outcomes** that will indicate success or failure.

This phase bridges market opportunity and detailed user research.


### Activities

- **Stakeholder Interviews & Workshops**
  - Discuss opportunity briefs with business, operations, engineering, and compliance.
  - Capture pain points, blockers, and desired outcomes from each group.

- **Problem Framing**
  - Use frameworks such as:
    - 5 Whys
    - Problem Statement templates (“As a [who], I struggle with [what], which causes [impact]”).
    - Current vs desired state mapping.

- **Scope Definition**
  - Identify what is **in-scope** for the next iteration and what is not.
  - Document affected business processes, geographies, and channels.
  - Define the target segment(s) for initial rollout.

- **Outcome Definition**
  - Define measurable goals (e.g., “reduce average onboarding time from 3 days to 30 minutes”).
  - Distinguish **business outcomes** (revenue, cost, risk) from **user outcomes** (time saved, satisfaction).

- **Constraint & Assumption Capture**
  - Regulatory and policy constraints.
  - Technology and integration constraints (e.g., mainframe batch windows).
  - Operational constraints (e.g., call center staffing, branch hours).
  - Assumptions about user behavior, market adoption, or internal change readiness.

- **Problem Statement Document**
  - Summarize problem, scope, outcomes, constraints, and assumptions in a shared doc.


### Inputs

- **Opportunity briefs** from Market Opportunity Discovery.
- **High-level strategy and objectives**.
- Existing **process documentation**, SLAs, and KPI dashboards.
- Feedback from **frontline teams** (sales, operations, support).
- Any early **user research** or analytics insights.


### Outputs

- **Formal Problem Statement**
  - Target users and stakeholders.
  - Current-state problems and pain points.
  - Impact of current issues (quantitative when possible).

- **Scope Definition**
  - Scope boundary (what is included/excluded).
  - Affected systems, processes, and channels.

- **Desired Outcomes**
  - Outcome metrics (e.g., SLA improvements, NPS changes, error rate reductions).

- **Constraints & Assumptions Register**
  - Documented and visible assumptions and constraints.

This package guides **User & Market Research** and **Business Case & ROI Analysis**.


### Roles Responsible

- **Primary**
  - Product Manager
  - Business Owner / Sponsor

- **Supporting**
  - UX / Researcher
  - Engineering Lead / Architect
  - Operations / Process Owners
  - Compliance / Risk (where appropriate)
  - Data Analyst


### Tools Commonly Used

- Confluence or similar for **problem statement docs**.
- Miro, Mural, or whiteboarding tools for **workshops**.
- Jira / Azure DevOps to track **problem statements as artifacts**.
- Analytics tools (Looker, Tableau, Amplitude) to quantify the problem.
- Process modeling tools for current-state mapping (e.g., BPMN in Signavio).


### Example Scenario

Continuing the **digital SME lending** example:

- Opportunity: “Grow SME loan volume by offering faster, digital access to credit.”
- In Problem Definition, the team discovers:
  - SMEs must fill out multiple paper forms across several visits.
  - Bank staff manually re-enter data into multiple systems, causing errors.
  - Customers lack visibility into application status, leading to anxiety and repeat calls.

They formulate a problem statement:

> “Small business owners applying for loans at our bank face a slow, opaque process requiring multiple branch visits and manual paperwork, resulting in lost time and frustration, and causing us to lose potential customers to competitors offering faster digital options.”

They define outcomes:

- Reduce **time to decision** from 5 business days to under 2 hours.
- Increase **application completion rate** from 60% to 80%.
- Reduce **call center volume** related to loan status by 30%.

They also log constraints:

- KYC checks must follow regulator-approved process.
- Credit underwriting models are owned by a central risk team with limited capacity for changes in the next 6 months.


### Best Practices

- **Separate problem from solution**: “We need a mobile app” is not a problem statement.
- **Quantify impact**: Use data to estimate current-state metrics and desired future state.
- **Involve the right people**: Include operations, compliance, and engineering early.
- **Make the problem testable**: Define success metrics to validate whether the problem is solved.
- **Document “non-problems”**: Capture what is out of scope and why.
- **Iterate**: Refine the problem as new information emerges during research.


### Common Mistakes

- **Ambiguous problem statements** that can be interpreted multiple ways.
- **Boiling the ocean**: Overly broad problems that are impossible to tackle in one initiative.
- **Ignoring constraints**: Defining a problem solution that is impossible due to regulation or tech limitations.
- **Lack of stakeholder alignment**: Different teams holding conflicting views of the core problem.
- **No measurable outcomes**: Making it impossible to evaluate success.

A strong Problem Definition acts as a “north star” for subsequent research and design phases.