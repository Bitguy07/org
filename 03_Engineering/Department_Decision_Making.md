# Engineering — Department Decision-Making

## Internal Order
Area engineer owns technical decisions inside their surface; cross-surface changes go through eng lead review (rotating senior, Stage 0: ENG-BE); architecture changes are Medium decisions with PM-CEX + PM-OPS impact notes.

## Standing Contracts
| Before deciding on... | Engineering must hear from... |
|---|---|
| Data model changes | RES-PA (metric impact), LG-PRIV (privacy), PM owners |
| Check-in / location logic | PM-SAF (abuse), DS-UXS (crisis UX), LG-PRIV (data) |
| Vendor/dependency adoption | ENG-INF (cost/lock-in), Legal (terms) |
| Performance/UX tradeoffs | DS-LPD + PM-CEX |

## Interface Rules
- Estimates are commitments; slippage is flagged at stand-up, never discovered at demo.
- Scope change after design handoff = CHANGE ticket, accepted or rejected by Engineering with effort note.
- Security/privacy defects outrank features, no exceptions (P4, P6).
