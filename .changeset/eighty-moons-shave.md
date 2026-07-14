---
"@gsc-cli/cli": patch
---

Add `--data-state` to `analytics query`. Search Console finalizes data on a lag, so the API default (`final`) omits the most recent ~2-3 days. Pass `--data-state all` to include fresh, non-finalized data.
