## 25 – Templates for RFCs & Related Artifacts

This file provides **copy‑paste templates** you can adapt for RFCs, ADRs, and decision logs.

---

### 1. RFC Template (Markdown‑Friendly)

```markdown
# RFC-XXX: <Title>

## 1. Metadata
- Author(s): <names>
- Owner: <name, role>
- Status: Draft | In Review | Accepted | Rejected | Superseded
- Created: <YYYY-MM-DD>
- Last Updated: <YYYY-MM-DD>
- Reviewers: <roles/names>
- Approvers: <roles/names> (to be filled on decision)
- Related Documents: <links to PRDs, feasibility, previous RFCs>

## 2. Summary
<Short paragraph summarising the proposal and expected impact.>

## 3. Context & Problem Statement
- Business context:
  - ...
- Technical context:
  - ...
- Pain points / limitations:
  - ...

## 4. Goals & Non-Goals
- Goals:
  - G1: ...
  - G2: ...
- Non-Goals:
  - NG1: ...
  - NG2: ...

## 5. Proposed Solution
- High-level architecture and components:
  - ...
- Technology choices and rationale:
  - ...
- Data and integration overview:
  - ...

## 6. Alternatives Considered
- Option A – <name>
  - Description:
  - Pros:
  - Cons:
- Option B – <name>
  - Description:
  - Pros:
  - Cons:
- Rationale for chosen option:
  - ...

## 7. Architecture & Diagrams
- Context diagram:
  - <embed or link>
- Logical architecture:
  - <embed or link>
- Key sequences/flows:
  - <embed or link>

## 8. Security, Compliance & Privacy
- Assets and data:
  - ...
- Access control:
  - ...
- Threats and controls (summary):
  - ...
- Relevant regulations/policies:
  - ...
- Audit/logging requirements:
  - ...

## 9. Operational Considerations
- Performance and scalability:
  - ...
- Availability and resilience:
  - ...
- Monitoring and alerting:
  - ...
- Deployment and rollback:
  - ...
- Backup and disaster recovery:
  - ...

## 10. Migration / Rollout Plan
- Phases:
  - ...
- Co-existence with legacy:
  - ...
- Data migration approach:
  - ...
- Cutover and fallback:
  - ...

## 11. Risks & Open Questions
- Risks:
  - R1: ...
  - R2: ...
- Open questions:
  - Q1: ...
  - Q2: ...

## 12. Decision & Approvals
- Decision:
  - Accepted / Rejected / Superseded by RFC-YYY
- Approvers:
  - <name, role, date>
  - <name, role, date>
- Conditions:
  - ...

## 13. Appendix
- Detailed diagrams:
  - ...
- Benchmarks / POC results:
  - ...
- References:
  - ...
```

---

### 2. ADR Template

```markdown
# ADR-XXX: <Decision Title>

## Context
<Short background of the situation and why a decision is needed.>

## Decision
<The decision made, as clearly and concisely as possible.>

## Consequences
- Positive:
  - ...
- Negative / Risks:
  - ...

## References
- RFC: RFC-XXX <link>
- Related docs: <links>
```

---

### 3. RFC Decision & Change Log Template

Simple table (in docs/wiki or sheet):

| Date       | RFC ID  | Change / Decision Summary                     | Type (Minor/Major) | Approver(s)       | Notes                                   |
|------------|---------|-----------------------------------------------|--------------------|-------------------|-----------------------------------------|
| 2026-03-20 | RFC-012 | Accepted Option B with condition on POC       | Major              | Arch Board, Sec   | POC to validate performance in 6 weeks  |
| 2026-04-10 | RFC-012 | Updated NFRs based on POC results             | Minor              | Tech Lead, SRE    | Latency target adjusted from 100ms->150ms |

---

### Connections to Other Files

- `05-rfc-structure-and-authoring.md` – conceptual explanation behind these templates.
- `08-security-compliance-and-risk-in-rfcs.md` – informs security/compliance sections.
- `24-governance-review-and-lifecycle.md` – how these templates fit into governance.

