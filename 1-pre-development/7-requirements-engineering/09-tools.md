## 09 – Tools for Requirements Engineering

This file describes **tool categories** that support Requirements Engineering: from documentation and whiteboarding through issue tracking, testing, and traceability.

The goal is to help you understand:

- *which* tools you need,
- *how* they fit together,
- without over‑focusing on any single vendor.

---

### 1. Documentation & Collaboration Tools

Purpose:

- capture:
  - PRDs,
  - NFR specs,
  - decision logs,
  - traceability tables,
  - diagrams and notes.

Common choices:

- `Confluence`
- `Notion`
- `Google Docs`
- `Microsoft Word` / `SharePoint`

Best practices:

- create:
  - a dedicated space per product/domain,
  - standard PRD and NFR templates (`25-templates.md`),
  - index page with links to key docs.
- enforce:
  - clear ownership and status labels (Draft, Baseline for Release X, Superseded).

---

### 2. Whiteboarding & Mapping Tools

Purpose:

- visualize:
  - user journeys,
  - service blueprints,
  - flows for requirements discussions,
  - domain and data models at a high level.

Common tools:

- `Miro`
- `FigJam`
- `Mural`
- `Lucidchart`

Usage in Requirements Engineering:

- workshops to:
  - refine scope and flows,
  - identify edge cases,
  - align on NFR scenarios (e.g., failure modes).

Link diagrams back to PRDs:

- embed them,
- or link with context.

---

### 3. Issue Trackers & Backlog Tools

Purpose:

- manage:
  - epics,
  - user stories,
  - tasks,
  - bugs.

Common tools:

- `Jira`
- `Azure DevOps`
- `Trello`
- `Asana`

Requirements usage:

- stories and epics:
  - should link to:
    - PRD sections,
    - requirement IDs,
    - NFR categories.
- use:
  - custom fields or labels for:
    - theme,
    - objective/OKR,
    - requirement ID (FR‑x / NFR‑x),
    - regulatory tag (if applicable).

This enables:

- lightweight traceability between:
  - roadmap,
  - requirements,
  - and implementation.

---

### 4. Testing & Quality Tools

Purpose:

- express and execute:
  - test cases,
  - test suites,
  - automated checks,
  - performance and security tests.

Examples:

- Test management:
  - `Xray for Jira`, `Zephyr`, `TestRail`, `Azure Test Plans`.
- Automation frameworks:
  - `Cypress`, `Playwright`, `Selenium`, `JUnit`, etc.
- Performance tools:
  - `JMeter`, `Gatling`, `k6`.

Connection to requirements:

- each test or suite:
  - should reference:
    - story IDs,
    - requirement IDs,
    - NFRs where relevant.

This supports:

- proving coverage,
- answering audit questions.

---

### 5. Analytics, Logging & Monitoring Tools

Purpose:

- verify that NFRs and behavioural expectations are met **in production**.

Examples:

- Product analytics:
  - `Amplitude`, `Mixpanel`, `Heap`, `Pendo`.
- Monitoring and logging:
  - `Prometheus`, `Grafana`,
  - `Splunk`, `ELK` stack,
  - cloud monitoring tools.

Use in Requirements Engineering:

- define:
  - what events and metrics must be tracked (see `10-documents-and-artifacts.md`),
  - as part of PRD and NFRs.
- ensure:
  - dashboards and alerts are created to validate NFRs.

---

### 6. Traceability & ALM (Application Lifecycle Management) Tools

Some organizations use specialized tools to manage:

- requirements,
- design,
- tests,
- defects,
- and traceability.

Examples:

- `Jira` + `Xray` / `Zephyr`,
- `Azure DevOps` end‑to‑end,
- dedicated ALM tools in regulated sectors.

Tips:

- avoid:
  - duplication of the same requirement across tools;
  - choose clear “source of truth.”
- integrate:
  - references rather than copy‑pasting.

---

### 7. Tooling Pitfalls to Avoid

Common issues:

- too many tools with overlapping purposes,
- inconsistent usage between teams,
- heavy configuration before basic practices exist.

Better approach:

- start from:
  - process and information needs,
  - then configure minimal tools to support them.
- align:
  - templates,
  - naming conventions,
  - linking practices.

---

### 8. Beginner Checklist

- [ ] Do we have:
  - [ ] a clear home for PRDs and NFR docs?
  - [ ] a single issue tracker as source of truth for stories and epics?
  - [ ] a way to record and execute tests linked to requirements?
  - [ ] monitoring/analytics that can check key NFRs in production?
- [ ] Are:
  - [ ] IDs and links used consistently across tools?
  - [ ] teams aligned on basic tooling conventions?

If not, focus first on:

- documentation space,
- issue tracker conventions,
- and minimal integration with test and monitoring tools.

---

### Connections to Other Files

- `08-traceability-and-documentation.md` – how tools support traceability.
- `10-documents-and-artifacts.md` – documents you should maintain and where they live.
- `22-best-practices.md` and `23-common-mistakes.md` – good and bad patterns around tool usage.

