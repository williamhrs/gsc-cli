---
"@gsc-cli/cli": patch
---

Add `--start-row` to `analytics query` for manual zero-based pagination offset. The SDK already honored `startRow`; this exposes it so a query can resume from an arbitrary offset. Rejects negative, fractional, and non-numeric values.
