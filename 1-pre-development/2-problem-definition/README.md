## Problem Definition

### What This Folder Is

This folder is a **mini‑handbook** for the *Problem Definition* phase.  
It turns broad opportunities from `1-market-opportunity-discovery` into **clear, structured, testable problem statements** that can guide research, design, and delivery.

If you are a **beginner**, you can start with `01-concepts.md` and read in order.  
If you are **experienced**, you can jump directly to a topic using the table of contents below.


### Quick Table of Contents (Click to Navigate)

- **Foundations**
  - [01 – Concepts](./01-concepts.md)
  - [02 – Objectives](./02-objectives.md)
  - [03 – Workflow](./03-workflow.md)
  - [04 – Frameworks](./04-frameworks.md)
  - [05 – Research Methods](./05-research-methods.md)
  - [06 – Data Sources](./06-data-sources.md)
  - [07 – Problem Evaluation](./07-problem-evaluation.md)

- **Execution Enablers**
  - [08 – Tools](./08-tools.md)
  - [09 – Metrics](./09-metrics.md)
  - [10 – Documents](./10-documents.md)

- **People & Skills**
  - [11 – Roles and Positions](./11-roles-and-positions.md)
  - [12 – Skills](./12-skills.md)
  - [13 – Job Market](./13-job-market.md)
  - [14 – Salary Benchmarks](./14-salary-benchmarks.md)

- **Context & Patterns**
  - [15 – Contexts and Domains](./15-contexts-and-domains.md)
  - [16 – Anti-Patterns vs Good Problems](./16-anti-patterns-vs-good-problems.md)
  - [17 – Startup vs Enterprise](./17-startup-vs-enterprise.md)

- **Learning from Examples**
  - [18 – Case Studies](./18-case-studies.md)
  - [19 – Real-World Examples](./19-real-world-examples.md)

- **Quality & Risk Management**
  - [20 – Best Practices](./20-best-practices.md)
  - [21 – Common Mistakes](./21-common-mistakes.md)
  - [22 – Risks](./22-risks.md)

- **Assets for Execution**
  - [23 – Templates](./23-templates.md)
  - [24 – Checklists](./24-checklists.md)
  - [25 – Glossary](./25-glossary.md)


### Overview (Beginner Friendly)

**Problem Definition** transforms broad opportunities into **clear, structured problem statements**. It describes **who** is affected, **what** is wrong, **why** it matters, and **what success looks like**. In enterprises, this step avoids building features that solve the wrong problem or only address symptoms.

Problem Definition is **solution‑agnostic**; it frames the problem so multiple solution options can be evaluated later.


### Objectives (Summary)

> Deep dive in `02-objectives.md`.

- **Clarify the core problem** and differentiate it from symptoms.
- **Define scope and boundaries** of the problem to be addressed.
- **Align stakeholders** on what needs to be solved and why.
- **Identify constraints and assumptions** early.
- **Establish measurable outcomes** that will indicate success or failure.

This phase bridges **Market Opportunity Discovery** and downstream phases like **User & Market Research** and **Business Case & ROI Analysis**.


### Typical Activities (Summary)

> Detailed workflow in `03-workflow.md` and frameworks in `04-frameworks.md`.

- **Stakeholder Interviews & Workshops**
  - Discuss opportunity briefs with business, operations, engineering, and compliance.
  - Capture pain points, blockers, and desired outcomes from each group.

- **Problem Framing**
  - Use frameworks such as:
    - 5 Whys
    - Problem statement templates (“As a [who], I struggle with [what], which causes [impact]”).
    - Current vs desired state mapping.

- **Scope Definition**
  - Identify what is **in scope** for the next iteration and what is not.
  - Document affected business processes, geographies, and channels.
  - Define target segment(s) for initial rollout.

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


### Inputs and Outputs (Summary)

> See `06-data-sources.md` and `10-documents.md` for details.

**Key Inputs**

- **Opportunity briefs** from Market Opportunity Discovery.
- **High‑level strategy and objectives**.
- Existing **process documentation**, SLAs, and KPI dashboards.
- Feedback from **frontline teams** (sales, operations, support).
- Any early **user research** or analytics insights.

**Key Outputs**

- **Formal Problem Statement**
  - Target users and stakeholders.
  - Current‑state problems and pain points.
  - Impact of current issues (quantitative when possible).

- **Scope Definition**
  - Scope boundary (what is included/excluded).
  - Affected systems, processes, and channels.

- **Desired Outcomes**
  - Outcome metrics (e.g., SLA improvements, NPS changes, error rate reductions).

- **Constraints & Assumptions Register**
  - Documented and visible assumptions and constraints.

This package guides **User & Market Research** and **Business Case & ROI Analysis**.


### Roles Responsible (Summary)

> Detailed view in `11-roles-and-positions.md` and `12-skills.md`.

- **Primary**
  - Product Manager
  - Business Owner / Sponsor

- **Supporting**
  - UX / Researcher
  - Engineering Lead / Architect
  - Operations / Process Owners
  - Compliance / Risk (where appropriate)
  - Data Analyst


### Tools Commonly Used (Summary)

> Detailed list and usage in `08-tools.md`.

- Confluence or similar for **problem statement docs**.
- Miro, Mural, or whiteboarding tools for **workshops**.
- Jira / Azure DevOps to track **problem statements as artifacts**.
- Analytics tools (Looker, Tableau, Amplitude) to quantify the problem.
- Process modeling tools for current‑state mapping (e.g., BPMN in Signavio).


### Example Scenario (Digital SME Lending)

> More end‑to‑end examples in `18-case-studies.md` and shorter ones in `19-real-world-examples.md`.

Continuing the **digital SME lending** example:

- Opportunity: “Grow SME loan volume by offering faster, digital access to credit.”
- In Problem Definition, the team discovers:
  - SMEs must fill out multiple paper forms across several visits.
  - Bank staff manually re‑enter data into multiple systems, causing errors.
  - Customers lack visibility into application status, leading to anxiety and repeat calls.

They formulate a problem statement:

> “Small business owners applying for loans at our bank face a slow, opaque process requiring multiple branch visits and manual paperwork, resulting in lost time and frustration, and causing us to lose potential customers to competitors offering faster digital options.”

They define outcomes:

- Reduce **time to decision** from 5 business days to under 2 hours.
- Increase **application completion rate** from 60% to 80%.
- Reduce **call center volume** related to loan status by 30%.

They also log constraints:

- KYC checks must follow regulator‑approved process.
- Credit underwriting models are owned by a central risk team with limited capacity for changes in the next 6 months.


### Best Practices & Common Mistakes (Where to Look)

- High‑level best practices are summarized at the end of this file and expanded in `20-best-practices.md`.
- Common pitfalls are listed in `21-common-mistakes.md`.

**Key best practices**

- **Separate problem from solution**: “We need a mobile app” is not a problem statement.
- **Quantify impact**: Use data to estimate current‑state metrics and desired future state.
- **Involve the right people**: Include operations, compliance, and engineering early.
- **Make the problem testable**: Define success metrics to validate whether the problem is solved.
- **Document “non‑problems”**: Capture what is out of scope and why.
- **Iterate**: Refine the problem as new information emerges during research.

A strong Problem Definition acts as a **north star** for subsequent research and design phases.
