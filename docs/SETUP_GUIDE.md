# Vsad Studios: Setup Guide

## 1. Repository

```bash
gh repo create UGC_Business --private --source=. --remote=origin --push
```

## 2. YouTube Channel Setup

1. Create playlist: "Free Professional UGC Templates"
2. Create category playlists (Email Marketing, Website Builders, Design, etc.)
3. Channel description: free UGC templates for startups + submission form link
4. Banner + thumbnail template (consistent brand)

## 3. Distribution Hub

- Google Drive folder: editable template files per category
- Notion/Airtable: product/template database
- Google Form: "Submit Your Product" → saves to `data/brand-submissions.json`

## 4. First Batch (Week 1)

1. Pick 3 prompts from `prompts/evergreen/`
2. Generate videos via Google Flow Agent (see `automation/opencode-generation.md`)
3. Export template version + marked editable areas
4. Upload with SEO title format: "FREE: Professional [Category] UGC Ad Template | Editable | Download"
5. Description from `templates/youtube-description-template.md`

## 5. Outreach (Weeks 5-8)

- Use `templates/brand-outreach-template.md`
- Log every partner in `data/affiliate-partners.md`
- Agree on 10% monthly rev-share → sign `templates/affiliate-contract-template.md`

## 6. Weekly Loop

| Day | Task |
|-----|------|
| Mon | Generate 3 new videos |
| Tue | Edit + export templates |
| Wed | Upload + community post |
| Thu | Outreach emails (5-10) |
| Fri | Review analytics, update `data/youtube-analytics.md` |
| Sat | Batch record next week |
| Sun | Rest / plan |

## 7. Tracking

- `data/youtube-analytics.md` — weekly views, CTR, watch time
- `data/affiliate-partners.md` — partner status, monthly rev
- `data/product-database.json` — every product + template status
