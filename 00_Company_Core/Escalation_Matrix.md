# Escalation Matrix — When and How Issues Move Up

General decisions follow Decision_Making_Framework.md. **This file governs risk, conflict, and time-critical escalation.**

---

## Severity Levels
| SEV | Definition | Examples | Max Time to Engage |
|---|---|---|---|
| **SEV-0** | Physical safety, legal exposure, live incident at an event | Assault report, injury at event, data breach of location history | Immediate — all paths fire now |
| **SEV-1** | Platform broken for many users; campus density collapsing | Check-in down on event night; host mass-quit; viral bad-press thread | < 2 hours |
| **SEV-2** | Cross-department deadlock; metric red for 2+ weeks | Product vs T&S disagreement; attendance <50% for 3 weeks | < 48 hours |
| **SEV-3** | Routine disagreements | Priority disputes, resource conflicts | Next weekly ritual |

## Escalation Paths
### SEV-0 (Life/Law First)
```
1. ANY agent who sees it → raises P0 ticket + INCIDENT message to T&S Investigations + Legal Counsel + CEO. Now.
2. T&S owns the response playbook (Playbooks/Handle_Safety_Incident.md). CEO is informed, not consulted, for the first hour.
3. Legal decides external statements and regulatory exposure.
4. Post-incident: Incident_Log entry + post-mortem in Knowledge_Base within 72h.
```
**Nobody needs permission to escalate SEV-0. Delaying a SEV-0 escalation is itself a SEV-0.**

### SEV-1 (Platform/Campus Health)
Owner agent → owning department head → CEO if unresolved in 2h. War-room thread; hourly updates until green.

### SEV-2 (Deadlock)
1. Both sides write one-page positions (problem, evidence, options, recommendation) — Decision Record format.
2. Lowest common manager (usually COO or relevant head) decides within 48h.
3. If heads are the deadlock → CEO decides at/next Leadership Meeting. Decision is final until new evidence.

### SEV-3 (Routine)
Resolve at team level or next ritual. If it survives two rituals, it is SEV-2 by definition.

## Veto Invocation (any size, any time)
Trust & Safety or Legal may halt any work item instantly by filing a ticket tagged `VETO` + notifying the owner and CEO. The item resumes only after T&S/Legal sign-off recorded in the Decision Log.

## Anti-Patterns (Bannable Offenses)
- Escalating without a written position and options.
- Sitting on a SEV-1 for a day to "gather more data."
- Re-opening a Big decision without new evidence and without citing the original Decision Record.
- Punishing an agent for escalating in good faith.
