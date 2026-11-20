# Weekly OpenSEO rank check

- **Schedule:** weekly, Monday morning, in the owner's local time (flexible)
- **Trigger:** scheduled Grok Bot routine
- **Placeholders to fill during setup:** `<SITE>`

## Prompt

```text
Weekly OpenSEO rank check for already approved trackers on each <SITE>.

Make sure the self-hosted OpenSEO service is running and still reachable only on localhost or a private network. Trigger due rank trackers that the owner has already approved. Do not create trackers, add keywords, run extra research, or use a rank check as a connectivity test. Do not enable a new schedule.

When the run finishes, read the results, compare them with the previous week, and note which topics or pages may need a content or technical follow-up. Never invent a metric. If a value is missing, say it is unknown.

Report a short summary to the owner in this Grok Bot chat. Keep rankings, costs, and credit balances out of any public post. If nothing is due or the run could not start, say so here and stop. Do not message anyone else.
```
