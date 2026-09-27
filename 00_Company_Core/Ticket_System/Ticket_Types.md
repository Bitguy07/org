# Ticket Types & Default Routing

| Type | Use For | Default Owner | Typical Priority |
|---|---|---|---|
| **BUG** | Product broken (check-in fails, streak miscounts) | ENG-QA triages → ENG-BE/FE/RL | P1–P2 |
| **FEATURE** | New capability or improvement | PM of affected area (PM-CEX/PM-SQD/PM-SAF/GR-PM) | P2–P3 |
| **SUPPORT** | User/host needs help | SUP-US (users) / SUP-HS (hosts) | P1–P3 |
| **TASK** | Internal work item (docs, setup, screening) | Owning dept head assigns | P2–P3 |
| **INCIDENT** | SEV-0/1 live event (outage, safety, campus crisis) | TS-INV (safety) / ENG-INF (platform) | P0 |
| **CHANGE** | Modify process/system already in flight | Original owner + requesting agent agree | P2 |
| **SAFETY** | Harassment, abuse, policy violation report | TS-INV (P0) or COM-MOD (P1/P2 content-level) | P0–P1 |

## Type-Specific Rules
- **SAFETY tickets are invisible by default:** restricted visibility, logged in Incident_Log if SEV-0/1. Never discussed in open channels.
- **FEATURE tickets must name a metric** (Shared_Metrics.md) or be returned to sender.
- **BUG tickets require repro steps** and environment; check-in bugs always tagged ENG-RL.
- **CHANGE tickets after design handoff** require impact note from Engineering before approval.
- Duplicate tickets: mark `DUPLICATE of #<NNNN>`, link, close. The original stays open.

## Cross-Type Conversions
A SUPPORT ticket revealing a product flaw converts to BUG (linked, original stays open until user helped). A FEATURE ticket revealing legal exposure converts to CHANGE + Legal CC with a `VETO` flag until cleared.
