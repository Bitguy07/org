# Communication Protocols — How Agents Talk to Each Other

A multi-agent company dies from message chaos, not from bad strategy. These rules keep communication load-bearing.

---

## The One Law
> **If it matters, it is a ticket. If it is decided, it is a Decision Record. If it happened, it is in a log. Chat/messages are for coordination only — never for decisions, never for history.**

## Message Format (all inter-agent messages)
```
FROM: <Agent ID> | TO: <Agent ID(s)> | CC: <relevant dept>
TYPE: FYI | INPUT-NEEDED | DECISION-PROPOSAL | ESCALATION | INCIDENT
CONTEXT: <2-3 sentences, with ticket/decision links>
ASK: <the one thing needed from the recipient>
DEADLINE: <date/time + why>
```
No ask + no deadline = the message should have been a log entry, not a message.

## Channels & Their Rules
| Channel | Use For | Never For |
|---|---|---|
| Ticket system (Ticket_System/) | All work: bugs, requests, incidents | — |
| Decision Log (Work_History/) | Every Medium/Big decision | — |
| Department threads | Coordination within a department | Cross-department decisions |
| Leadership Meeting | Medium decisions needing heads; Big decision prep | Status theatre |
| Knowledge_Base.md | Lessons, post-mortems, playbooks updates | — |

## Response & SLA Expectations
| Priority | First Response | Resolution Target |
|---|---|---|
| P0 (safety incident, outage) | Immediate; per Escalation_Matrix | < 24h |
| P1 (blocked user, broken check-in) | Same business day | < 3 days |
| P2 (standard work) | 2 business days | Per sprint plan |
| P3 (ideas, polish) | Next weekly triage | Best effort |

## Escalation Language (Use Exactly)
- "BLOCKED-BY: <agent/department> on <ticket #>. Needed by <date>." → goes to owning department head.
- "VETO-INVOKED: <P#>, <principle>, <evidence>." → immediately pauses the work item; per Escalation_Matrix.
- "ESCALATE-TO-LEADERSHIP: <decision>, <options>, <recommendation>." → for Big decisions or unresolved Medium conflicts.

## Tone
Direct, evidence-first, no blame. Attack the ticket, never the agent. Disagree in writing before a meeting, so meetings decide instead of debate.

## Agent Self-Check Before Sending
1. Is there a ticket number? 2. Is there exactly one ask? 3. Is there a deadline? 4. Would a stranger understand this in 30 seconds? If any answer is no, revise.
