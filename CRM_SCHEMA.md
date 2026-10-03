# CRM & Prospect Database

## Purpose

Track every prospect from discovery through sale, delivery, and recurring operations without relying on memory or scattered spreadsheets.

## Prospect record

| Field | Purpose |
|---|---|
| Lead ID | Unique internal identifier |
| Date added | First date recorded |
| Company | Prospect company |
| Contact name | Primary contact |
| Email | Approved business contact |
| Industry | Segment |
| Source | Website, referral, LinkedIn, outreach, etc. |
| Workflow | Problem being investigated |
| Frequency | How often the task occurs |
| Manual time | Estimated time consumed |
| Current tools | Existing systems |
| Impact | Delay, cost, error, or workload |
| Stage | Current pipeline stage |
| Estimated value | Potential project value |
| Next action | Immediate sales action |
| Next action date | Follow-up date |
| Owner | Person responsible |
| Notes | Context and discovery notes |

## Pipeline stages

1. Prospect
2. Contacted
3. Responded
4. Discovery
5. Audit Proposed
6. Audit Active
7. Implementation Proposed
8. Won
9. Delivery
10. Monthly Operations
11. Lost / Nurture

## Rules

- One record per company/contact opportunity.
- Never mark a lead Won without a confirmed customer commitment.
- Record the next action for every active opportunity.
- Record the reason when a lead is lost or moved to nurture.
- Do not store passwords, API keys, payment credentials, or unnecessary sensitive personal information in the CRM.
