# Vsad Studios: UGC Prompt Templates

Master prompt structure for all UGC videos. Every prompt follows the same skeleton so output stays consistent.

## Master Skeleton

```
Create a 10-second professional UGC ad for [PRODUCT CATEGORY] (editable template).

VISUALS (clean, business-focused, minimal):
- 0-1s: [intro scene]
- 1-3s: [product in use]
- 3-6s: [value moment / dashboard]
- 6-8s: [result / growth]
- 8-10s: [BLANK LOGO AREA] + '[BLANK: BRAND NAME]' + '[BLANK: CTA]', fade

AUDIO (professional, trustworthy):
- 0-1s: subtle ambience
- 1-4s: calm uplifting music
- 4-6s: success notification sound
- 6-8s: music builds
- 8-10s: fade with satisfying chord

COLOR & MOOD:
- [palette], modern typography, [mood]
- Text overlays bold sans-serif, editable by brands

OUTPUT: 10s template video + separate file with editable text/logo areas marked.
```

## Per-Category Prompts

- Email marketing → `prompts/evergreen/email-marketing.md`
- Website builders → `prompts/evergreen/website-builder.md`
- Design tools → `prompts/evergreen/design-tool.md`
- Project management → `prompts/evergreen/project-management.md`
- Payment gateway → `prompts/evergreen/payment-gateway.md`
- CRM → `prompts/evergreen/crm-software.md`
- Social scheduler → `prompts/evergreen/social-media-scheduler.md`
- Hosting/domain → `prompts/evergreen/hosting-domain.md`
- Analytics → `prompts/evergreen/analytics-platform.md`
- VPN/security → `prompts/evergreen/vpn-security.md`

Custom products: copy `prompts/custom/template.md` and fill in.

## Generation Workflow

See `automation/opencode-generation.md` — use opencode to generate a filled prompt from a category + product, then run it through Google Flow Agent / Veo / Runway for the video.
