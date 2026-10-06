# opencode-Powered Prompt Generation

Use opencode (this local assistant) to turn a product/category into a ready-to-run video prompt without rewriting the structure each time.

## Quick use

Paste this into opencode:

```
Read prompts/evergreen/<category>.md. Generate a new 10-second UGC prompt for <PRODUCT> following the exact same structure: VISUALS (time-coded), AUDIO, COLOR & MOOD, OUTPUT. Brand placeholders stay as [BLANK ...]. Save to prompts/custom/<product-slug>.md
```

## Batch use

```
For every entry in data/product-database.json with status "planned", read its promptFile, and generate a branded variation for <BRAND>. Save to prompts/custom/<slug>.md. Then set status to "prompt-ready" in the json.
```

## Rules

- Never change the 10s time-code structure — consistency keeps templates on-brand
- Keep `[BLANK ...]` placeholders so brands can edit
- After generating, update `data/product-database.json` status
