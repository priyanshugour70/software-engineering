## RFC / Technical Proposal

### Overview

The **RFC (Request for Comments) / Technical Proposal** phase produces a **structured, reviewable document** describing a significant technical change or new system. It is the primary mechanism for **cross-team alignment and architectural decision-making**.

In enterprises and banks, RFCs often serve as official records that support audits, risk assessments, and technical governance.


### Objectives

- **Describe the context and problem** from a technical perspective.
- **Propose one or more solution options** with rationale and trade-offs.
- **Obtain feedback and approval** from relevant stakeholders.
- **Document decisions** and alternatives for future reference.
- **Provide input to detailed architecture design and implementation**.

RFCs scale architectural decision-making across multiple teams and domains.


### Activities

- **RFC Scoping**
  - Decide whether a change warrants an RFC (based on impact, risk, or cross-team dependencies).
  - Clarify objectives, success criteria, and constraints.

- **Drafting the RFC**
  - Capture context, problem, goals, and non-goals.
  - Describe current state, proposed solution(s), and alternatives.
  - Document high-level architecture, data flows, and APIs.
  - Add security, compliance, and operational considerations.

- **Review & Feedback**
  - Share with architects, engineering leads, product, security, and compliance.
  - Conduct asynchronous reviews and review meetings as needed.
  - Capture comments, Q&A, and design discussions.

- **Decision & Sign-Off**
  - Converge on a recommended approach.
  - Document decisions, approvals, and conditions.
  - File the RFC in a version-controlled repository.

- **Post-Decision Updates**
  - Keep RFC updated with major changes.
  - Link to downstream design docs and implementation tickets.


### Example RFC Structure

Below is a commonly used RFC template:

```markdown
# RFC-001: Digital SME Lending Platform – Technical Proposal

## 1. Metadata
- Author: Jane Doe
- Status: Draft | In Review | Accepted | Rejected | Superseded
- Created: 2026-03-13
- Reviewers: Architecture, Security, Risk, Ops
- Related Documents: PRD-123, Feasibility Study v1.1

## 2. Summary
Short paragraph summarizing the proposed change and its expected impact.

## 3. Context & Problem Statement
- Business context and drivers.
- Current system/process limitations.
- Why existing approaches are insufficient.

## 4. Goals & Non-Goals
- Goals describe what the proposal aims to address.
- Non-goals clarify what is explicitly out of scope.

## 5. Proposed Solution
- High-level architecture and components.
- Technology choices and rationale.
- Data model overview.
- Interactions with existing systems.

## 6. Alternatives Considered
- Option A: Description, pros/cons.
- Option B: Description, pros/cons.
- Rationale for selecting the proposed solution.

## 7. Architecture & Diagrams
- Logical architecture.
- Deployment topology.
- Sequence diagrams for key flows.

## 8. Security, Compliance & Privacy
- Threat model summary.
- Data classification and protection.
- Compliance considerations (e.g., KYC/AML, GDPR).

## 9. Operational Considerations
- Scalability, performance, and availability.
- Monitoring and observability.
- Deployment strategies and rollback.
- Backups and disaster recovery.

## 10. Migration / Rollout Plan
- Phasing, co-existence strategy, data migration, cutover.

## 11. Risks & Open Questions
- Known risks and mitigations.
- Items needing further research or decisions.

## 12. Decision & Approvals
- Decision summary.
- List of approvers and dates.

## 13. Appendix
- Detailed diagrams, links, POCs, benchmarks.