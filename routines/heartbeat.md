# Heartbeat

- **Schedule:** on the cadence the owner's PM tool uses for a regular heartbeat
- **Trigger:** webhook from `<PM_TOOL>`
- **Placeholders to fill during setup:** `<PM_TOOL>`, `<SITE>`, `<OPERATOR_AGENT>`

## Prompt

```text
Heartbeat for SEO work in <PM_TOOL>. Queues only.

Inspect the open SEO-related task queues for each <SITE> and <OPERATOR_AGENT>. Note overdue, blocked, or missing-due-date work. Do not request indexing, spend paid data credits, create or reprioritize tasks, or treat this heartbeat as approval to ship work.

If a due task title starts with "Bi-weekly SEO review", leave it for the site-review routine; do not run the review here.

If the queues are healthy, do not message anyone. If the owner needs to decide something, send a short note to the owner in this Grok Bot chat. Nothing new means no message.
```
