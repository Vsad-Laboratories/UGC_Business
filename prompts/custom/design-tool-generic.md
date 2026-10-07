# Design Tool (generic) — UGC Ad Prompt

Source: `prompts/evergreen/design-tool.md`. Generic version — no brand named, so any design tool (Canva, Figma, Adobe Express) can be swapped in.

"Create a 10-second professional UGC ad for graphic design software (editable template).

VISUALS (artistic, colorful, inspiring):
- 0-1s: Blank canvas appearing with color palette loading, artistic lighting with warm overhead glow
- 1-3s: Rapid design creation montage (2x speed): templates being selected, colors changing, text being added, elements being arranged
- 3-5s: Close-up of designer's workspace: hands moving mouse, design coming to life in real-time, vibrant colors popping (satisfying to watch)
- 5-7s: Fast montage (2.5x speed) of finished designs: social media post, flyer, business card, poster—variety showcase
- 7-10s: Final polished design centered on screen with [BLANK LOGO SPACE], '[BLANK: BRAND NAME]' overlay, '[BLANK: CTA]', fade to black with colored accent

AUDIO (creative, modern, energetic):
- 0-0.5s: Artistic 'swoosh' with subtle music swell
- 0.5-3s: Upbeat modern pop/indie music (120+ BPM), creative energy, feels fun and accessible
- 2-4s: Add satisfying UI sounds (click, confirmation tones), synced to design actions
- 4-7s: Music intensifies with layered synths and subtle percussion
- 7-10s: Music peaks with triumphant moment, single satisfying audio hit at logo reveal

COLOR & MOOD:
- Vibrant: rainbow spectrum used tastefully, not chaotic
- Modern: contemporary typography
- Mood: creative freedom, professional results, fun to use
- Emphasize: 'Anyone can create professional designs'

OUTPUT: 10-second template with clearly marked brand customization zones."

---

## Voiceover overlay (add after generation — templates/voiceover-script-template.md)

Keep this version visual-only as the template master. For the YouTube Short, burn in the series VO (0.3s delay, ~3s total) and duck the music bed -6 dB under it. Script: `seo/design-tool-generic.md`.

## Rules

- Do NOT name a brand in the visuals unless that brand's actual UI appears on screen
- Every text/logo moment stays a `[BLANK ...]` placeholder so brands can edit