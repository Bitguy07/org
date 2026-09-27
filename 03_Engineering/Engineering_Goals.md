# Engineering Goals — 03_Engineering

**Department mission:** Ship reliable, privacy-aware, boring-in-the-best-way infrastructure for real-world check-ins — on free tiers until revenue justifies more.

## Quarterly Goals
| Goal | Metric | Owning role |
|---|---|---|
| G1: Check-in works, always, on event night | Check-in success rate ≥ 96%, event-night incident count = 0 | ENG-RL |
| G2: Core loop ships at MVP scope | Roadmap commitment (DECISION-2026-004) delivered | ENG-BE/FE |
| G3: Costs stay near-zero until Stage 1 | Infra spend <$50/mo; free-tier headroom alerts | ENG-INF |
| G4: Safety rails are testable | 100% safety flows in automated regression | ENG-QA |
| G5: Location data minimized | No raw location stored beyond check-in event; audit pass | ENG-RL + LG-PRIV |

## Department Rules
- Free tiers are a constraint we design *for*, not around: caching, quotas, and graceful degradation are features.
- No AI services in the product (P8). Automation scripts internal-only, reviewed.
- Event-night (Thu–Sat) on-call rotation exists from Stage 0; check-in is the P1-est P1.
