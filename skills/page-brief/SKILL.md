---
name: page-brief
description: Turn a mapped search intent into a content or technical brief filed as a task in the owner's PM tool, ready for an operator or coding agent to implement.
---

# Page brief

Use this skill after keyword research and clustering have mapped an intent to one page. The output is a task in `<PM_TOOL>`, not a page you write yourself and not a pull request you open.

## Before you write the brief

- Confirm the intent and the target URL, or the proposed path if the page does not exist yet.
- Confirm the product path is real and has been tested. Do not brief a page for an integration, comparison, or feature that is not supported.
- Prefer a page per integration, product, or topic. Build a comparison page only when the product supports that path and comparison intent is what people search for.
- Check the existing keyword map and live pages for cannibalization.
- Check the daily caps: at most one due task per `<OPERATOR_AGENT>` per day, and at most one new content piece per `<SITE>` per day, unless the owner has set different caps.
- If the work needs paid research you do not already have, stop and ask the owner for approval with a cost estimate. Do not spend credits inside this skill.

## What the task must contain

Create one task in `<PM_TOOL>` and assign it to the `<OPERATOR_AGENT>` or coding agent for that `<SITE>`. Set a due date that respects the caps. Put the whole brief on the task. Do not hand it off in a DM or an @-mention.

Include:

- Target URL or proposed path, and the primary query plus close variants
- Search intent, and who the page is for
- Required sections and the questions the page should answer
- Internal links to add, and any pages that should link here
- Technical constraints: canonical host, indexation, structured data policy, and what not to invent
- Definition of done: the production URL returns a successful HTTP response, uses the expected canonical, and is indexable. The implementer then comments `SEO live: <url>` on this task, with no DM or mention.

Do not invent commercial facts. If a price, shipping, return, or availability field is unknown, omit it or use a truthful schema type. Do not fabricate values to clear a rich-result warning.

## After you file the task

Tell the owner the task title, the assignee, the due date, and the target URL. You review the brief against what shipped. You do not merge, deploy, or publish.
