---
"@gsc-cli/sdk": patch
"@gsc-cli/cli": patch
---

Support the `sitemapIndex` query parameter on `sitemaps.list` (`--sitemap-index` on `sitemaps list`). Lists only the child sitemaps contained in a given sitemap index URL, instead of every submitted sitemap — useful on sites with a large sitemap index.
