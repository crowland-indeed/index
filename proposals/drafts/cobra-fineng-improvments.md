# FINENG Improvement Proposals

## Training module / documentation
- TBD

## Developer Workflow
- Daily -- Weekly -- Quarterly
- Ticket Investigation
- Standup
- Ticket Review
- Status update
- Product requirements investigation
- Epic determination with product
- Client review (to identify business value improvements)
- Training
- Database change review
- Architecture review
- Code Review
- Improvement process

## Application Improvements
- Email logging, and lower environment routing to a distribution email to catch logic errors in cron job and email sending issues
- Requires Cobra-Fineng-Development Notification distribution group
- Feature flagging (ideally not split.io , something more performant and less queries and lightweight)
- Tax Rules Engine (To keep up with individual state and federal changes (eventually countries))
- Pipeline engine for requests and cron jobs
- JSON configurable tax and year system to make sure calculations rerun for audit at a later date are valid
- basic user interface

## Developer Recommendations

## Cron Job Management Proposal (Scaling)

 - By Tenant (DB)
 - By Tenant (App Instance)
 - By Application / Tenant Priority in Configuration
