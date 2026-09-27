# Ticket Lifecycle

Tickets are the company's unit of work. "If it matters, it is a ticket."

---

## States
```
OPEN → TRIAGED → ASSIGNED → IN_PROGRESS → RESOLVED → CLOSED
                     ↘ WAITING/BLOCKED ↗ (reason + unblocker required)
```

## State Definitions & Rules
| State | Meaning | Rule |
|---|---|---|
| OPEN | Just filed | Anyone may raise (P: low friction). Untriaged queue reviewed at Support Triage (daily) and weekly dept triage. |
| TRIAGED | Priority + type confirmed | Triage owner sets P0–P3 (Priority_Matrix). Wrong priority is worse than slow priority. |
| ASSIGNED | Exactly one owner | Two owners = zero owners. CC ≠ ownership. |
| IN_PROGRESS | Actively worked | Updates in the ticket log at least every 2 business days (P2) or per SLA (P0/P1). |
| WAITING | Blocked or needs info | Must name: what is needed, from whom, by when. Silent WAITING > 5 days → auto-escalates SEV-2. |
| RESOLVED | Work complete | Owner posts outcome: what changed, metric link, Action_Log reference. |
| CLOSED | Confirmed & archived | Resolver (or QA for bugs) confirms. Closed tickets are searchable history — never deleted. |

## Lifecycle SLA Anchors
- P0: resolve <24h (SEV-0 path bypasses queue entirely — see Handle_Safety_Incident.md)
- P1: <3 business days · P2: within current sprint/2 weeks · P3: best effort, reviewed weekly

## Reopening
A CLOSED ticket reopens only with new evidence, referencing the original closure note. Reopening without cause is logged as process debt in the closing agent's performance tracker.

## Agent Obligations
1. Raise liberally, own strictly. 2. Never let your queue hide WAITING tickets. 3. Resolve = outcome + record, not "I did stuff." 4. Every RESOLVED ticket lands in Work_History/Action_Log.md.
