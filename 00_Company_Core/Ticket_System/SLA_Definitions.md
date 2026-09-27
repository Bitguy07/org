# SLA Definitions

Service-Level Agreements per priority. SLAs are commitments to **each other and to users** — breaching an SLA auto-escalates.

---

| Priority | First Human Response | Status Update Cadence | Resolution Target | Breach Escalation |
|---|---|---|---|---|
| P0 | Immediate | Hourly during incident | <24h | Auto: LD-CEO + dept heads at 4h without resolution update |
| P1 | Same business day | Daily | <3 business days | Dept head at breach; LD-COO at 2× target |
| P2 | 2 business days | Every 2 days | ≤ current sprint | Dept head review at sprint end |
| P3 | Next weekly triage | Weekly | Best effort, quarter-bound | Backlog review; auto-close after 2 quarters idle with note |

## Clock Rules
- SLA clock starts at TRIAGED, not raised (triage itself must be same-day for P0/P1).
- WAITING pauses the resolution clock but **never the update cadence** — silence is a breach even when blocked.
- SAFETY/INCIDENT tickets follow incident playbooks first; this table governs the residual work after containment.
- Business days = campus-active days. Event-night (Thu–Sat) P1s follow the on-call rotation.

## Reporting
Weekly: tickets raised/resolved per dept, SLA breach count, aging WAITING list (top 10). Breaches are reviewed without blame in Metrics Review — but *patterns* of breach (same team, same cause) become a Medium decision: fix the process or the staffing.

## User-Facing SLAs (Support)
Users get: P1 <24h first reply · P2 <3 days. Hosts get the same plus event-night emergency line. Published SLAs are kept conservative; we meet them before we advertise them.
