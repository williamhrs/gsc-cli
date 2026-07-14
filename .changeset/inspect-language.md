---
"@gsc-cli/cli": patch
---

Add `--language` to `inspect`. Sets the BCP-47 `languageCode` (e.g. `en-US`, `pt-BR`) controlling the language of the issue messages Google returns. The SDK and command layer already supported it; this exposes it on the CLI.
