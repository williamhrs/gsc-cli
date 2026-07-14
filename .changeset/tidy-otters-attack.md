---
"@gsc-cli/sdk": patch
"@gsc-cli/cli": patch
---

Support `aggregationType` on `searchAnalytics.query` (`--aggregation-type` on `analytics query`). Controls how metrics are aggregated — `byPage` vs `byProperty` yield different impression counts for the same query. Values: `auto` (default), `byPage`, `byProperty`, `byNewsShowcasePanel`.
