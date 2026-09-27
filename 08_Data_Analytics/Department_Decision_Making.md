# Data & Analytics — Department Decision-Making

## Internal Order
Analytics owns definitions & interpretation; Data_Engineering owns pipelines & quality. Metric definition changes are Medium decisions with RES-PA + DA-AN co-sign (North Star changes are Big).

## Standing Contracts
| Data must involve... | When |
|---|---|
| Privacy (LG-PRIV) | Every new data category, every pipeline touching personal data |
| RES-PA | Every metric definition (single definitional authority together) |
| Engineering | Every instrumentation ticket (schema contracts) |

## Interface Rules
- Numbers presented without confidence/context (sample size, window, known gaps) are returned.
- Pipeline changes ship with rollback and a freshness alarm — never silently.
