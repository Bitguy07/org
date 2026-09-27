# Playbook — Ship a New Feature (Medium-size work, cross-functional)

**Lead owner:** the relevant Product Manager. **Gatekeeper for launch:** Trust & Safety (user-facing) and Legal (liability/data).

---

## Stage A — Frame (Week 0)
1. Problem statement + evidence (data, research, tickets). State the metric it moves (Shared_Metrics.md) and how it will be measured.
2. PM raises `FEATURE` ticket; tags Design, Engineering, Community, T&S (if user-facing), Legal (if data/liability), Data (measurement).
3. Data files instrumentation ticket **before** build starts (Dependency Map #5).

## Stage B — Options & Input (Week 0–1)
4. PM writes 2–4 options incl. "do nothing." Cross-functional comments due in 5 business days:
   - Design: UX risk, anxiety/friction assessment per activity type.
   - Engineering: effort estimate, technical risk.
   - Community: host/user operational load; training needed?
   - T&S: abuse vectors; does it touch P1–P4 principles?
   - Legal: liability, privacy, terms impact.
5. Decision per Decision_Making_Framework (Medium: dept head; Big: leadership). **Decision Record filed.**

## Stage C — Build (Week 1–4)
6. Design hands off final flow; changes after handoff require Change Request ticket.
7. Engineering builds behind flag; QA writes test plan incl. safety flows and check-in edge cases.
8. In parallel: Content_Design writes all copy; Support drafts help content; Community prepares host/user comms.

## Stage D — Launch Gates (Week 4)
| Gate | Check | Sign-off |
|---|---|---|
| G1 Quality | QA pass; no open P0/P1 bugs | ENG-QA |
| G2 Safety | T&S abuse review; safety flows tested | TS-SPP |
| G3 Legal | Privacy/terms check if data touched | LG-PRIV/LG-COUN |
| G4 Measurement | Dashboard live; experiment readout date set | DA-AN |
| G5 Density | Current campus still >70% attendance (P5: features never justify density neglect) | COM-HC |

## Stage E — Rollout & Learn
9. Ship to 1 campus → 2 weeks → readout at Metrics Review → full rollout, iterate, or rollback (decision recorded).
10. Action_Log + Decision Record entries closed; lessons to Knowledge_Base.md.

**Anti-pattern:** shipping to all campuses on day one. We earn scale campus by campus.
