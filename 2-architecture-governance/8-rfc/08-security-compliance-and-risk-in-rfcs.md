## 08 – Security, Compliance & Risk in RFCs

This file explains how to **bake security, compliance, and risk thinking into RFCs** instead of treating them as after‑the‑fact checks.

---

### 1. Why This Deserves Its Own Section

In enterprises and banks:

- many initiatives fail or stall because:
  - security and compliance concerns are:
    - discovered late,
    - under‑specified,
    - or not aligned with risk appetite.

Putting security, compliance, and risk **front‑and‑centre in RFCs**:

- reduces surprises,
- speeds approvals,
- improves overall system safety.

---

### 2. What to Cover in the Security Section

Key topics:

- **Assets & Data**
  - what sensitive data is handled?
  - where is it stored and transmitted?
- **Access Control**
  - who can do what?
  - how is authentication and authorization handled?
- **Threats & Controls**
  - high‑level threat model:
    - external attackers,
    - insider threats,
    - compromised components.
  - key controls:
    - input validation,
    - rate limiting,
    - encryption,
    - logging and monitoring.
- **Security Dependencies**
  - identity providers,
  - key management,
  - WAF, IDS/IPS, etc.

Coordinate with:

- security architects/engineers for deeper analysis where needed.

---

### 3. What to Cover in the Compliance & Privacy Section

Key topics:

- **Regulations & Policies**
  - which regulations apply?
    - e.g., KYC/AML, PSD2, GDPR, local laws.
  - which internal policies are relevant?
- **Data Protection**
  - data classification,
  - retention and deletion,
  - masking and anonymization where applicable.
- **Customer Communications & Disclosures**
  - what legal or regulatory text must appear where?
  - how is consent captured and managed?
- **Audit Trail**
  - what must be logged for regulatory evidence,
  - how logs are protected and accessed.

Coordinate with:

- compliance,
- legal,
- risk management.

---

### 4. Risk Perspective in RFCs

Beyond security and compliance:

- consider broader **risk categories**:
  - operational risk (e.g., outages, manual processes),
  - model risk (if models or scoring logic are involved),
  - vendor risk (3rd‑party services),
  - change risk (migration and rollout).

In RFCs, you should:

- identify:
  - key risks,
  - severity and likelihood (qualitatively),
  - planned mitigations or controls.

This feeds:

- the later **Compliance & Risk Assessment** phase,
- but starts here.

---

### 5. Collaboration Patterns

Good practices:

- involve:
  - security and risk/compliance early,
  - during RFC drafting, not only review.
- use:
  - short threat‑modelling or risk workshops for:
    - high‑impact RFCs,
    - new platforms or major changes.
- iterate:
  - security and compliance sections as:
    - architecture and requirements evolve.

This turns RFCs into a **collaborative risk management tool**, not a checkbox.

---

### 6. Example – Security & Compliance in a Lending RFC

For a digital SME lending RFC:

- Security:
  - describe:
    - authentication flows (e.g., SSO, MFA),
    - protecting sensitive financial and identity data,
    - session management and CSRF/XSS protections.
- Compliance:
  - map:
    - data elements and flows to KYC/AML and data protection rules,
    - logging requirements for credit decisions and changes.
- Risk:
  - highlight:
    - risk of incorrect decisions,
    - data leakage,
    - operational incidents,
  - outline:
    - mitigation measures,
    - monitoring and response.

---

### 7. Beginner Checklist

- [ ] Does the RFC:
  - [ ] identify sensitive data and how it is protected?
  - [ ] describe access control and authentication?
  - [ ] mention relevant regulations and policies?
  - [ ] specify audit logging and retention needs?
- [ ] Have security and risk/compliance:
  - [ ] reviewed early drafts?
  - [ ] provided input into controls and assumptions?
- [ ] Are major risks:
  - [ ] clearly listed,
  - [ ] with planned mitigations?

If not, work with security and risk partners to strengthen these sections before final approval.

---

### Connections to Other Files

- `05-rfc-structure-and-authoring.md` – section 8 (Security, Compliance & Privacy) structure.
- `07-diagrams-and-technical-content.md` – diagrams that support threat modelling and risk analysis.
- `10-security-review` and `11-compliance-risk` phases – later, more detailed reviews that build on RFC content.

