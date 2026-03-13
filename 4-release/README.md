## Release Phase Overview

The **Release** macro-phase covers activities required to **validate the integrated system** and **safely deploy** changes into production or other target environments.

It includes:

15. QA / System Testing  
16. Release Management & Deployment


### Objectives

- **Validate the system end-to-end** against requirements and non-functional expectations.
- **Ensure release readiness** with proper sign-offs and documentation.
- **Manage deployments safely** through controlled processes and automation.
- **Minimize risk of incidents** through testing, rollout strategies, and rollback plans.


### High-Level Process Flow (Release)

```mermaid
flowchart LR
    A[QA / System Testing] --> B[Release Management & Deployment]
    B --> C[Live in Production]