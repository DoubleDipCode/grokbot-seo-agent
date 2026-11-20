# Bi-weekly SEO site review

- **Schedule:** when a review task comes due (bi-weekly in the original setup)
- **Trigger:** webhook from `<PM_TOOL>` when that task comes due
- **Placeholders to fill during setup:** `<PM_TOOL>`, `<SITE>`, `<OPERATOR_AGENT>`

## Prompt

```text
Bi-weekly SEO site review, only when the triggering <PM_TOOL> task title starts with "Bi-weekly SEO review". If it does not, stop without changing the task.

Identify <SITE> from the task. Make sure OpenSEO is running. Use free reads only: saved keywords, rank-tracker history, audit issues, and Search Console performance. Open the Search Console web UI for the Generative AI report. Compare this window with the previous review window. Do not invent metrics and do not run paid tools.

Post the review as a comment on the task and mark the task done. List recommendations, each with the <OPERATOR_AGENT> who would implement them. Do not create those tasks, assign work, spend credits, or send outreach until the owner approves.

Send a short summary to the owner in this Grok Bot chat. If the webhook was not a review task, do nothing and do not message anyone.
```
