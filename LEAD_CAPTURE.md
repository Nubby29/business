# Lead Capture System

## Current state

The website contains a structured qualification form with these fields:

- Name
- Company
- Email
- Workflow type
- Repetitive task
- Frequency

The current static implementation prepares and copies a structured inquiry locally. It does **not** pretend to send or store leads remotely.

## Launch connection

Before public launch, connect the form to an owner-approved destination.

Recommended sequence:

1. Owner chooses the primary business email or lead-management destination.
2. Choose the lowest-complexity capture method compatible with the hosting platform.
3. Add spam protection and a privacy notice appropriate to the chosen provider.
4. Test submission from desktop and mobile.
5. Confirm that the lead is actually received/stored.
6. Connect the lead to the sales pipeline.
7. Record source, date, status, estimated value, and next action.

## Minimum lead record

- Lead ID
- Date received
- Name
- Company
- Email
- Workflow/problem
- Frequency
- Source
- Qualification status
- Estimated project value
- Next action
- Owner
- Notes

## Approval blockers

Do not publish a fake or placeholder submission endpoint. The owner must approve the destination and any third-party service before it is connected.
