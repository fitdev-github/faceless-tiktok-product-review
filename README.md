# Faceless TikTok Product Review

A portable agent skill for planning and producing vertical, faceless product-review videos for TikTok, Reels, and Shorts. It keeps the product as the evidence source and uses hands-only or first-person visuals—never a visible presenter.

The skill is written to work with different AI agents and media stacks. If an agent cannot render video, it can still produce a complete production package: an evidence-backed script, shot plan, narration text, and caption file.

## What it produces

- A product-facts note separating visible facts, verified mechanics, and marketing claims
- A short-form voiceover script, normally about 30 seconds
- A timed 9:16 storyboard with continuity requirements
- A caption plan or `.srt` file
- When the host supports it: a vertical MP4 with voiceover and burned-in captions

## What it needs

Provide at least one real product reference:

- Product photos
- A product page URL
- Existing product footage

Also provide any verified specifications, preferred language and tone, desired duration, and call to action. The skill will not invent a product's branding, performance, dimensions, mechanisms, or unshown sides.

## Add to an agent

Copy this folder into the skill directory used by your agent, retaining the structure:

```text
faceless-tiktok-product-review/
├── SKILL.md
└── references/
    └── tiktok-production.md
```

Agents that discover `SKILL.md` files can load it directly. For an agent without a skill system, add the contents of `SKILL.md` to its project instructions and make the `references/` folder available as supporting context.

### Codex Cloud

Place the folder in a repository under `.agents/skills/faceless-tiktok-product-review/`, then use that repository in a published Cloud environment. Cloud tasks can access repository skills; local personal skills do not automatically sync.

## Usage

Give your agent a clear request and the product reference, for example:

```text
Use faceless-tiktok-product-review to make a 25-second Thai TikTok review.
Use these product images as the source of truth. Keep it hands-only,
use a practical everyday tone, and deliver the script and SRT before rendering.
```

For a rendered deliverable, the host agent needs video generation or editing, narration or text-to-speech, caption rendering, and an MP4 export path. The skill requires explicit approval before paid, rate-limited, irreversible, or publishing actions.

## Default creative spec

- 30 seconds, unless a different duration is requested
- Vertical 9:16, normally 1080p
- Off-screen narration and readable captions
- Hands-only, cropped body, or POV; no face or speaking mouth
- Natural phone-shot look, practical lighting, and credible demonstrations
- No unsupported promises, fabricated testimonials, or fictional before/after results

Read [TikTok production guidance](references/tiktok-production.md) for the detailed evidence, pacing, caption, and disclosure checks.

## Limits

This is for faceless product demos and review-style videos. It is not intended for creator-led talking heads, silent ASMR-only videos, or an unboxing where the reveal is the primary story.

The skill plans and produces media; it never uploads or publishes to TikTok or another platform without a separate explicit instruction.
