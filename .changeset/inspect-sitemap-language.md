---
"@gsc-cli/cli": patch
---

`gsc inspect --sitemap` now honors `--language`. The BCP-47 `languageCode` is forwarded to every batch inspection, matching single-URL `inspect`. Previously the flag was silently ignored in batch mode.
