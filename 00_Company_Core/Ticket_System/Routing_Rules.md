# Routing Rules — From Ticket to Owner

Exactly one owner per ticket. Route by **type first, area second, escalation last**.

---

## Quick Routing Table
| If the ticket is about... | Route To |
|---|---|
| Event discovery, joining, check-in UX, streaks | PM-CEX |
| Squads, friend connections, recurring anchors | PM-SQD |
| Reporting, blocking, host verification policy in-product | PM-SAF |
| Research plan, user interviews, usability tests | RES-UR |
| Metric definitions, dashboards, experiment readouts | RES-PA / DA-AN |
| Visual screens, design system, prototypes | DS-LPD → DS-UX* by area |
| In-app words, tone, anxiety-reducing copy | DS-CD |
| Web app, mobile UI build | ENG-FE |
| APIs, database, auth, event/squad logic | ENG-BE |
| GPS/QR check-in, maps, location privacy | ENG-RL |
| Hosting, deploys, scaling, costs | ENG-INF |
| Test plans, release quality | ENG-QA |
| Campus density, club partnerships, local hosts | COM-CM (+ COM-HC oversight) |
| Host training, verification interviews, host quality | COM-HS |
| Live event logistics, venue issues | COM-EO |
| Chat/content moderation, norms enforcement | COM-MOD |
| Safety policy, rules per activity type | TS-POL |
| Active reports, investigations, enforcement | TS-INV |
| Safety requirements into product | TS-SPP |
| Referral loops, activation, pricing experiments | GR-PM |
| Campus marketing, ambassadors, content | GR-GM (+ GR-BC) |
| Club/venue/brand deals | GR-PART |
| Terms, waivers, liability, university policy | LG-COUN |
| Location data, consent, privacy requests | LG-PRIV |
| Insurance, incident liability review | LG-RISK |
| Metric pipelines, data infrastructure | DA-DE |
| User questions, account help | SUP-US |
| Host questions, tooling help | SUP-HS |
| Cross-department deadlock, unclear owner | LD-COO (SEV-2 path) |

## Routing Protocol
1. Triage agent (daily Support Triage) applies this table; uncertainty → LD-COO with a 24h SLA.
2. Re-routing is allowed once without penalty; repeated misroutes → Knowledge_Base lesson + table update (table changes are Medium decisions).
3. Veto-flagged tickets route to the vetoing authority for sign-off before work resumes.
4. Every routing decision is one log line in the ticket — who routed, why, when.
