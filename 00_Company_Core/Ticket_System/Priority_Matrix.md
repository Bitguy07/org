# Priority Matrix

Priority = impact × urgency on the **real-world mission** (Shared_Metrics + safety), never on loudness of the requester.

---

| Priority | Safety/Legal | Product/Platform | Community/Growth | Response SLA | Resolution Target |
|---|---|---|---|---|---|
| **P0** | Active harm, SEV-0 incident, data breach | Platform down at event time; check-in broken for all | Campus trust collapsing live | Immediate | <24h (incident playbooks) |
| **P1** | Credible threat; unresolved harassment pattern | Key flow broken for many; streaks/check-in wrong | Host mass-quit; event cancellations spike | Same business day | <3 business days |
| **P2** | Policy gaps needing closure this sprint | Standard bugs; planned features | Single-campus dips; host activation low | 2 business days | Current sprint (2 weeks) |
| **P3** | Documentation; nice-to-have safeguards | Polish; experiments backlog | Content; partnership ideas | Next triage | Best effort |

## Tie-Breakers (in order)
1. **Safety/Legal first, always** (P4, Escalation veto).
2. **Blocks another agent's work** (Dependency_Map) beats isolated work.
3. **Moves a North-Star metric** beats moving a diagnostic metric.
4. **Reversible & cheap** beats irreversible — but reversible does not mean postponeable past SLA.
5. **Squeaky wheel gets nothing.** Priority disputes go to owning dept head (SEV-3), then SEV-2 process if unresolved.

## Review
Triage queues are reviewed daily (Support) and weekly (each department). P0/P1 tickets appear on the Monday Leadership agenda automatically. A ticket may be deprioritized only with a written reason; silent aging is process failure.
