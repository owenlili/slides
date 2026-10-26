# Problem links

Links cited in the notes that open in a browser but that the daily check cannot verify, because the site refuses automated requests. They are kept out of [links.json](links.json) so they don't keep the `broken-links` issue open, and are checked by hand instead.

To check one, open it in a browser and update its "Checked by hand" date. If a site stops refusing the checker, move the link back into `links.json` and delete its row. If a link no longer opens in a browser either, note it here and fix the citation in the notes.

| Title | URL | Cited in | Why the check fails | First seen | Checked by hand | Notes |
|---|---|---|---|---|---|---|
| ThreadSafe | https://medium.com/threadsafe/ | `lectures/08-multi-agent-systems.md` | Medium returns 403 to the checker, curl, and WebFetch | 2026-10-26 | 2026-10-26: opens | Publication home page, not a specific article. |
| OpenAI: Building self-improving tax agents with Codex | https://openai.com/index/building-self-improving-tax-agents-with-codex/ | `field-notes/tax-ai-feedback-driven-improvement.md` | openai.com returns 403 to the checker, curl, and WebFetch | 2026-10-26 | 2026-10-26: opens | |
