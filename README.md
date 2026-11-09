# Agency operations board

Static public board for Green Insurance Agency ops items.

- Live site: https://wagreen84.github.io/gia-ops/
- Each item’s **Respond** link opens that owner bot in the Grok Bot app (`grokbot://…`).
- No client names / PHI. No tokens or secrets in this repo.
- Sales TV board stays at https://wagreen84.github.io/gia-board/ (separate).

## Refresh

On the Grok Bot box:

```bash
/workspace/agency-ops-board/publish_pages.sh
```

That regenerates `data.json` from the local board DB (PHI-scrubbed), copies into this site, commits, and pushes to `main` (GitHub Pages).
