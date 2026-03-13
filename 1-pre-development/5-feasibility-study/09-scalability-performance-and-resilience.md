## 09 – Scalability, Performance & Resilience

This file dives deeper into **non-functional feasibility**: can the solution meet performance, scale, and availability needs?

We cover:

- A. Key questions
- B. Scalability
- C. Performance
- D. Resilience & availability
- E. Practical checklist

---

### A. Key Questions

- How many users, transactions, or data volumes must the system support (now and in future)?
- What response time and throughput do we need at peak?
- How do we handle:
  - partial failures,
  - upstream/downstream outages,
  - degraded modes?

---

### B. Scalability

Assess:

- expected growth:
  - users,
  - transactions,
  - data size,
  - markets.
- current system scaling patterns:
  - vertical vs horizontal scaling,
  - sharding/partitioning,
  - autoscaling capabilities.

Questions:

- Can we scale components independently?
- Are there:
  - bottleneck systems (e.g., mainframes, single DBs),
  - licensing limits (e.g., per‑core, per‑node)?

Consider:

- scaling strategies:
  - caching,
  - partitioning,
  - asynchronous processing,
  - stateless services.

---

### C. Performance

Assess:

- target **latency** per user‑facing flow:
  - e.g., <2 seconds for typical actions,
  - lower caps for time‑critical operations.
- **throughput**:
  - peak TPS (transactions per second),
  - concurrency levels.

Use:

- existing performance metrics,
- load and stress testing plans,
- capacity modeling (together with infra teams).

Questions:

- Will added logic or integrations significantly slow down flows?
- Where do we need:
  - caching,
  - pre‑computations,
  - asynchronous operations?

---

### D. Resilience & Availability

Assess:

- required **availability** targets (e.g., 99.9%, 99.99%),
- dependencies:
  - on upstream (e.g., core banking, risk systems),
  - on downstream services (e.g., notifications, external APIs).

Questions:

- What happens if:
  - a dependency is slow or down?
  - one region or data center fails?
  - we need to roll back a deployment?
- Do we have:
  - retry and timeout strategies,
  - circuit breakers,
  - graceful degradation (reduced features instead of full failure)?
- Are:
  - backup and restore,
  - DR (disaster recovery),
  - chaos or resilience testing,
  planned and feasible?

---

### E. Practical Checklist

- Non‑functional requirements (NFRs) documented (throughput, latency, availability).
- Current performance and capacity baselines understood.
- Growth projections considered in design.
- Potential bottlenecks identified and mitigation strategies sketched.
- Scaling patterns and strategies documented (e.g., horizontal scaling, partitioning).
- Failure modes identified and handled (timeouts, retries, fallbacks).
- Backup, restore, and DR needs identified.
- Scalability/performance/resilience risks entered into the risk register.

---

### Connections to Other Files

- `05-technical-feasibility.md` – technical architecture implications.
- `06-operational-feasibility.md` – availability and incident processes rely on these NFRs.
- `22-risk-register-and-mitigation.md` – capturing related risks and mitigations.

