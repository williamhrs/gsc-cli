---
"@gsc-cli/cli": patch
---

Document how to express OR in `analytics query` filters. The Search Console API ANDs all filters and has no cross-filter OR, so OR within a dimension is done with the existing `=~` regex operator (e.g. `--filter 'query=~seo|marketing'`). Clarified the `--filter` help text and the README accordingly.
