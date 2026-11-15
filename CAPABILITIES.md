# Product capabilities and design direction

**In development.** This public-facing document describes intended workflows and architecture; it is not a release certificate or technical status report.

| Product area | Planned behavior |
|---|---|
| Document intake | Receive purchase agreements, amendments, addenda, disclosures, notices, inspection and financing documents. |
| Source-grounded intelligence | Extract proposed terms with verifiable source excerpts, document version, page and section provenance. |
| FIRRC review | Structure Facts, Issue, Rule, Reasoning and Conclusion while separating contract facts from independently checked legal rules. |
| Deadline engine | Respect effective-date triggers, business-day definitions, time zones, holidays and contract-specific cutoff rules. |
| Amendment management | Compare versions, preview changes to deadlines or obligations, and preserve prior approved records. |
| Decision control | Require appropriate human review for consequential changes, log approvals and support corrections. |
| Task management | Assign obligations, stage-aware checklists, reminders, escalations and completion evidence. |
| Brokerage oversight | Expose urgent exceptions, missing documents, overdue acknowledgments and unassigned work. |
| Contract questions | Ask questions against permitted transaction documents with precise evidence or explicit abstention. |
| Calendar and email | Intended Google/Outlook calendar synchronization and durable notification delivery. |
| Connected systems | Intended e-sign status links, inbound document/email routing and authorized brokerage API integrations. |
| Jurisdiction awareness | 50 states plus DC represented from initial architecture; separately validated state-specific rule coverage. |
| Access and audit | Brokerage/office/transaction-scoped roles, controlled sharing, immutable action records and privacy safeguards. |

## Illustrative end-to-end transaction journey

1. Create transaction and assign the agent, coordinator and broker.
2. Ingest the contract and relevant supplementary documents.
3. Review AI-proposed terms against original quoted evidence.
4. Approve operative deadlines and obligations.
5. Coordinate tasks, reminders, and calendar records.
6. Review subsequent amendments and approve any downstream changes.
7. Resolve closing-readiness exceptions with recorded responsibility.

**Explicit exclusions from the initial product scope:** general CRM replacement; consumer IDX listing platform; lead generation; native e-signature execution.

[Back to README](README.md) · [Brochure](BROCHURE.md) · [Sample screens](SCREENS.md)