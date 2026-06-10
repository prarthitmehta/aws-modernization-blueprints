# AWS Resource Tagging Blueprint

A governance model for tagging AWS resources across ownership, cost, security, automation, and compliance.

## Diagram

```mermaid
flowchart TD
    S[Tagging Strategy] --> C[Cost Allocation]
    S --> O[Ownership]
    S --> A[Automation]
    S --> G[Governance]
    S --> Sec[Security & Compliance]
    C --> R[Reports]
    O --> Ops[Operations]
    A --> LC[Lifecycle Actions]
    G --> P[Policy Enforcement]
    Sec --> E[Evidence & Audit]
```

## Recommended Tag Categories

- Business: business-unit, project, cost-center
- Ownership: owner, application, support-team
- Environment: dev, test, staging, prod
- Operations: backup, patching, lifecycle
- Compliance: data-classification, regulatory-scope
