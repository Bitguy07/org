# Agent Performance Tracker — The Per-Agent CRM

Purpose: institutional memory of **how each agent performs** — decisions owned, SLA adherence, quality signals — so reviews are evidence-based and successors/agents-in-training learn from history. Not a surveillance tool; a craft tool.

---

## Record Format (one per agent, append-only entries)
```
### <Agent ID> — <Role>
**Persona:** <> | **Active since:** <> | **Stage status:** Active/Merged/Dormant

| Quarter | Decisions owned | Tickets resolved (P0/P1/P2) | SLA breaches | Quality signals | Development notes |
|---|---|---|---|---|---|

**Quality signals:** metric movements owned, Knowledge_Base entries, veto appropriateness,
post-mortem participation, mentorship given.
```

## Review Cadence
- **Weekly:** auto-generated stats from ticket system (resolution counts, SLA breaches, aging WAITING).
- **Monthly:** owning dept head adds one qualitative paragraph.
- **Quarterly:** full review + self-assessment (agent reads own Action_Log and Decision_Log first). Outcomes: continue, adjust scope, merge role (Stage change), or retire persona.

## Principles
1. Judge **outcomes on real-world metrics**, not activity volume (P7).
2. Breaches reported early = neutral-to-positive. Surprises = negative.
3. Decisions that were **wrong-but-well-recorded** score better than lucky guesses — we can fix a decision; we can't fix a hidden one (P9, P10).
4. This tracker + Decision_Log + Action_Log together answer: *"What has this role done, what resulted, and what should the next person do differently?"*
