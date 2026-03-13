## Architecture Design

### Overview

**Architecture Design** elaborates the solution approach chosen in the RFC into a **detailed, implementable architecture**. It covers component boundaries, data models, interfaces, deployment topologies, and cross-cutting concerns.

In enterprises and banks, architecture design must align with **enterprise standards, shared platforms, and regulatory constraints**.


### Objectives

- **Design a robust, scalable, and maintainable system** that meets requirements.
- **Define clear boundaries and interfaces** between components and teams.
- **Specify data flows and storage patterns** with proper security.
- **Plan for non-functional requirements** (performance, availability, resiliency).
- **Produce artifacts that guide engineers and reviewers**.

Architecture design converts conceptual proposals into **concrete blueprints**.


### Activities

- **Domain and Component Modeling**
  - Identify bounded contexts and domains.
  - Define services, modules, and responsibilities.

- **API and Contract Definition**
  - Specify REST/GraphQL/gRPC APIs or event schemas.
  - Define input/output formats, error handling, and versioning.

- **Data Modeling**
  - Design logical and physical data models.
  - Map relationships and ownership (system of record vs caches).

- **Integration Design**
  - Plan integration with internal and external systems.
  - Define patterns (e.g., API, messaging, file-based, ETL).

- **Operational Architecture**
  - Deployment topologies (regions, availability zones).
  - Resilience patterns (circuit breakers, retries, timeouts).
  - Observability (metrics, logs, traces).

- **Documentation & Diagrams**
  - Create logical, physical, and sequence diagrams.
  - Maintain architecture decision records (ADRs).


### Inputs

- **Approved RFC** and decision.
- Detailed **requirements** (functional and non-functional).
- Enterprise **architecture standards** and reference models.
- Platform/infrastructure capabilities and constraints.


### Outputs

- **Architecture Design Document**
  - Component and service definitions.
  - Data models and storage strategy.
  - Integration patterns and contracts.
  - Deployment model and operational concerns.

- **Diagrams**
  - Logical architecture diagrams.
  - Deployment and network diagrams.
  - Sequence diagrams for critical flows.

- **Architecture Decision Records (ADRs)**
  - Individual decisions for specific aspects (e.g., database choice).


### Example Architecture Diagram (Markdown)

```mermaid
flowchart LR
    subgraph Frontend
        FE[SME Lending Web/Mobile UI]
    end

    subgraph Backend
        API[API Gateway]
        APP[Application Service]
        DOC[Document Service]
        DEC[Decision Service]
    end

    subgraph CoreSystems[Core Banking & Risk]
        CORE[Core Banking System]
        RISK[Credit Risk Engine]
    end

    FE --> API
    API --> APP
    API --> DOC
    APP --> DEC
    DEC --> CORE
    DEC --> RISK