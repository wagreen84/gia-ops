# Agency operations board

Static public board for Green Insurance Agency ops items.

- Live site: https://wagreen84.github.io/gia-ops/
- Buttons per item: **Reply**, **Remind me later**, **Completed** — each opens a Grok Bot chat (`grokbot://app/v1/agent?id=…` only; no prefilled message param is documented).
- Remind / Completed show on-page say-hints.
- No client names / PHI. No tokens or secrets.
- Sales TV board stays at https://wagreen84.github.io/gia-board/ (separate).

## Refresh

From the agency-ops-board project, run `publish_pages.sh`.

Completed items: add the item id to `data/pages_completed_ids.json`, then republish (or set the DB bucket to `completed`).
