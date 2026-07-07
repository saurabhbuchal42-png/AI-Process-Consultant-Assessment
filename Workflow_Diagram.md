# Workflow Diagram

## Consulting Engagement Workflow

```mermaid
flowchart TD

A[Client Inquiry<br/>Referral / LinkedIn / Website]

--> B[Discovery Call]

B --> C{Client is a Good Fit?}

C -->|No| D[Close Opportunity]

C -->|Yes| E[Prepare Proposal]

E --> F{Proposal Approved?}

F -->|Revision Requested| E

F -->|Approved| G[Client Signs Agreement]

G --> H[Schedule Kickoff Meeting]

H --> I[Create Project in Asana]

I --> J[Create Shared Folder]

J --> K[Assign Resources]

K --> L[Project Execution]

L --> M[Weekly Project Updates]

M --> N{Client Update Preference}

N -->|Meeting| O[Weekly Status Meeting]

N -->|Report| P[Written Status Report]

N -->|Call| Q[Quick Client Call]

O --> R{Billing Type}

P --> R

Q --> R

R -->|Fixed Fee| S[Monthly Invoice]

R -->|Hourly| T[Consultant Submits Time Entries]

T --> U[Accounting Generates Invoice]

S --> V[Project Completion]

U --> V
```

---

## Notes

### Known Exceptions

- Referral leads are not always entered into HubSpot.
- Consultants may begin work before project setup is completed.
- Proposal revisions may occur before approval.
- Resource allocation may be performed by the Managing Partner for high-priority clients.
- Consultants sometimes update project progress through Slack or Email instead of Asana.
- Late time entries delay invoice generation.

### Assumptions

- Every engagement follows the same high-level workflow.
- Every project has a designated Project Manager.
- All clients sign an agreement before project execution unless an exception exists.