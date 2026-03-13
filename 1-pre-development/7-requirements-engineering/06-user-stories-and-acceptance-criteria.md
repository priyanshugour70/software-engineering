## 06 – User Stories & Acceptance Criteria

This file explains **how to write good user stories and acceptance criteria**, and how they connect to PRDs and tests.

---

### 1. What User Stories Are For

User stories:

- break down PRD requirements into **small, deliverable units**,
- express work from a **user’s point of view**,
- act as:
  - conversation starters in refinement sessions,
  - anchors for acceptance criteria and tests.

They are not meant to:

- fully capture every detail alone (PRD and designs provide more context),
- replace discussion within the team.

---

### 2. Basic Structure of a User Story

Common template:

> As a \<persona>, I want \<capability>, so that \<benefit>.

Examples (digital SME lending):

- “As an SME owner, I want to see a checklist of required documents, so that I can prepare everything before starting the application.”
- “As a relationship manager, I want to view the status of my SME clients’ applications, so that I can proactively support them.”

Good story statements:

- are **concise**,
- focus on **user value**,
- avoid implementation details.

---

### 3. Connecting Stories to PRDs and Strategy

Each story should:

- link to:
  - PRD section(s) (e.g., FR‑3 in `05-prd-structure-and-authoring.md`),
  - roadmap epic or initiative,
  - relevant objective/theme (optional but recommended).

This ensures:

- traceability:
  - from story → requirement → objective,
  - and back.

In tools like `Jira`:

- use:
  - Epic links,
  - Components or custom fields for:
    - theme,
    - PRD ID,
    - NFR category (if applicable).

---

### 4. What Makes a “Good” Story (INVEST)

A commonly used checklist is **INVEST**:

- **I**ndependent:
  - can be developed largely on its own (within reason).
- **N**egotiable:
  - open to discussion; not a rigid contract.
- **V**aluable:
  - delivers value to a user or stakeholder.
- **E**stimable:
  - team can roughly estimate its size.
- **S**mall:
  - fits within a sprint or two.
- **T**estable:
  - has clear acceptance criteria.

If a story fails many of these, consider:

- splitting or rewriting.

---

### 5. Acceptance Criteria – Purpose and Structure

**Acceptance criteria** define:

- the conditions that must be met for a story to be considered done and acceptable.

They:

- reduce ambiguity,
- guide manual tests,
- serve as input for automated tests,
- help PO/PM and stakeholders validate outcomes.

Typical style:

- **Given / When / Then** (Gherkin‑like).

Example:

- Story:
  - “As an SME owner, I want to upload required documents, so that my loan application can be reviewed.”
- Acceptance criteria:
  - Given I am on the “Upload Documents” step with an in‑progress application  
    When I upload a supported file type (PDF, JPEG, PNG) under 10 MB  
    Then the file is accepted and shown in the document list.  
  - Given I attempt to upload an unsupported file type  
    When I click upload  
    Then I see an error message explaining which file types are allowed.  

---

### 6. Including NFR‑Related Criteria

Stories can also include NFR‑relevant criteria, for example:

- performance:
  - “Given normal load conditions, upload processing must complete within 5 seconds for 95% of users.”
- security:
  - “Uploaded documents must not be accessible via direct URL without authentication.”
- logging and monitoring:
  - “Every upload attempt (success/failure) must be logged with timestamp and masked customer ID.”

Not all NFRs need to appear per story, but:

- **critical NFRs** should be reflected in:
  - acceptance criteria,
  - broader NFR test plans.

---

### 7. Examples – Better vs Weaker Stories

**Weaker:**

- “Improve SME application page.”

Issues:

- unclear persona,
- unclear benefit,
- no testable outcome.

**Better:**

- “As an SME owner, I want to save my partially completed application and return later, so that I don’t lose progress if I’m interrupted.”

Acceptance criteria:

- Given I have filled mandatory fields on the current step  
  When I click “Save & exit”  
  Then my progress is saved and I see a confirmation message.  
- Given I return to the application portal and log in  
  When I open my previous application  
  Then I resume from the last completed step with data pre‑filled.  

---

### 8. Collaboration Around Stories

Good practice:

- write stories as a **starting point**, then:
  - refine them together with engineering, QA, design, and sometimes risk/ops.

In refinement:

- confirm:
  - feasibility and dependencies,
  - edge cases,
  - NFR implications.

Update:

- acceptance criteria as understanding improves.

---

### 9. Beginner Checklist

- [ ] Does each story:
  - [ ] clearly state a persona, capability, and benefit?
  - [ ] link to a PRD section or requirement ID?
  - [ ] have acceptance criteria in Given/When/Then or equivalent form?
- [ ] For key stories:
  - [ ] have we considered NFR‑related criteria where relevant?
- [ ] Are stories:
  - [ ] small enough to fit in 1–2 sprints?
  - [ ] understandable by someone new to the team?

If several answers are “no,” revisit story wording and criteria before committing them into a sprint.

---

### Connections to Other Files

- `05-prd-structure-and-authoring.md` – PRD sections that stories should map back to.
- `07-non-functional-requirements.md` – source for NFR‑related acceptance criteria.
- `08-traceability-and-documentation.md` – how stories and criteria connect to objectives and tests.

