# Decision-Making Framework

How decisions are generated, agreed, recorded, and escalated across Squad. Works together with Escalation_Matrix.md (for incidents) and Ticket_System/ (for tracked work).

---

## Step 1 — Where Instructions Originate (Goal Cascade)
**Company Strategy (CEO + Leadership)** → 6–12 month goals & OKRs
→ **Department Goals** (each department's X_Goals.md)
→ **Quarterly/monthly projects** → **weekly tasks & tickets**

If your work cannot trace to a company KR, stop and question it (see P5: Density Beats Features).

## Step 2 — Decision Sizes
| Size | Who Decides | Examples | Record Required |
|---|---|---|---|
| **Small** | Owning agent, alone | Copy change, bug fix scope, ticket priority within team | Optional (log in Action_Log) |
| **Medium** | Owning department head, after cross-functional input | New event category, host policy tweak, campus experiment, UI flow change | Yes — Decision Record |
| **Big** | CEO + executive agents | New city/campus, pricing change, safety policy change, legal structure, partnership deals, anything touching P0–P2 risk | Yes — Decision Record + leadership review |

## Step 3 — The Standard Decision Process
1. **Frame the problem.** One page: what happened, evidence, why now.
2. **Generate 2–4 options.** Including "do nothing."
3. **Collect cross-functional input.** Minimum viable set by decision type:
   - Product feature → Design, Engineering estimate, Community impact, Trust & Safety if user-facing risk, Data measurement plan
   - Safety-related → Trust & Safety (always), Legal, Community
   - Growth/expansion → Community (density check), Data, Legal (new jurisdiction)
4. **Decide at the right size.** Never escalate small decisions upward (it destroys ownership); never decentralize big ones (it destroys the company).
5. **Record it.** Use Templates/Decision_Record_Template.md → file in Work_History/Decision_Log.md.
6. **Communicate.** Announce in the relevant ritual (Operating_Rituals.md) and to every department the decision touches.

## Step 4 — Veto Powers (Check on Any Decision)
- **Trust & Safety** may veto anything that increases physical, psychological, or abuse risk to users.
- **Legal/Risk** may veto anything that materially increases liability or violates law/policy.
- **CEO** may veto anything that violates Core_Principles (e.g., an engagement-loop feature that would "work").

## Step 5 — Reversing Decisions
Decisions are reversible by default at Small/Medium size with a note in the Decision Log. Big decisions require the same forum that made them. "We decided X because Y on <date>" is always searchable in Work_History.

## Agent Rule of Thumb
> Small: decide and move. Medium: consult, decide, record. Big: escalate, decide, record, announce. Safety or legal risk of any size: pause and escalate immediately.
