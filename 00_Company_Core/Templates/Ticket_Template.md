# Template — Ticket

Copy this structure. Every ticket has exactly one owner. A ticket without an owner is unraised.

```markdown
# TICKET-<YYYY>-<NNNN>: <Title>
**Type:** BUG | FEATURE | SUPPORT | TASK | INCIDENT | CHANGE | SAFETY
**Priority:** P0 | P1 | P2 | P3   (see Ticket_System/Priority_Matrix.md)
**Severity (if INCIDENT/SAFETY):** SEV-0..3 (see Escalation_Matrix.md)
**Raised by:** <Agent ID> on <date>
**Owner:** <Agent ID> — exactly one
**CC:** <agents/departments affected>
**Status:** OPEN | TRIAGED | IN_PROGRESS | WAITING | RESOLVED | CLOSED

## Problem / Request
<What and why. Evidence links: tickets, Decision Records, metric snapshots.>

## Desired Outcome
<Measurable. Which Shared Metric moves, how measured.>

## Options Considered
<2-4 incl. do-nothing, with effort/impact.>

## Decision Needed From
<None (I own) | <Agent ID> by <date>>

## Timeline
Raised: <> · Triaged: <> · Target: <>

## Log
- <date> <agent>: <action/note>
```

**Routing & lifecycle:** see Ticket_System/. When resolved, owner files a closing note with outcome + Action_Log reference, then moves status to CLOSED.
