---
name: faceless-tiktok-product-review
description: Plan and produce faceless, vertical TikTok-style product-review videos from real product references, hands-only or first-person footage, voiceover, and readable captions. Use for product demos and review-style short videos without a visible presenter; not for creator-led talking-head reviews, silent ASMR, or unboxing-first videos.
---

# Faceless TikTok Product Review

Make the product—not an invented presenter—the focus of a concise, useful TikTok review. This is tool-agnostic: use the host agent's available media-generation, editing, voice, and file tools. Use real product imagery and supplied facts as the source of truth. Do not fabricate branding, claims, mechanisms, dimensions, product sides, or results.

## Required inputs and capabilities

Accept product photos, a product-page URL, a supplied video clip, or a combination. Extract only observable facts from images; use product-page information only as a claim source after the user authorizes access. Ask for a reference if none is supplied.

Before promising a finished video, identify which of these capabilities the host agent has: image/video generation or editing, text-to-speech or a user-supplied voice track, caption rendering, and file export. If a capability is unavailable, still deliver the script, storyboard, narration text, caption file, and an explicit handoff plan; do not imply that media was rendered.

Keep files portable: use UTF-8 plain-text formats for plans and captions (for example, Markdown and SRT), standard MP4/H.264/AAC for video where export is available, and relative paths within the project whenever the host supports a workspace.

## Scope and defaults

Default to a 30-second, 9:16, 1080p video with off-screen narration and burned-in captions. A person may appear only as hands, a cropped body, or a first-person view; never show a face or a speaking mouth. Use a natural phone-shot look, with practical lighting and ordinary use rather than a glossy advertisement.

When the user requests a video, collect only what is missing: product photos or a product page, verified product details or claims, desired language/tone, and any required call to action. If no product reference is available, do not generate a lookalike product—ask for one or find an official source only when authorized.

## Plan from evidence

Create a compact product-facts note that separates visible facts, user-confirmed mechanics, and marketing claims. Record which sides are actually shown. Use the host's image-analysis or image-editing capability to prepare assets; if the host has no such capability, write clear asset instructions instead.

Choose one buyer question that can be demonstrated visibly. Favor a credible friction-and-payoff sequence over a list of benefits. For a standard 30-second review, use this shape:

1. 0–3s: open mid-action with the clearest payoff or problem.
2. 3–18s: demonstrate the main use with hands-only or POV footage.
3. 18–26s: show a second, distinct proof point or practical detail.
4. 26–30s: final result, product view, and a low-pressure CTA.

Every shot must add useful evidence. Keep the product recognisable by three seconds. Avoid filler close-ups, fictional before/after claims, and repeated hero poses. Read [TikTok production guidance](references/tiktok-production.md) when timing, shot prompts, captions, or disclosure need more detail.

## Write and produce

Write one continuous, conversational voiceover first. Describe visible actions and evidence; do not claim personal experience unless the user provided it. Keep the language direct, brief, and believable. Captions should reinforce the narration, not introduce unsupported claims.

Plan each clip with: a time range, framing, one principal action, a visible end state, and a continuity lock (same product, hands, sleeve, environment, light, and prop state). Use hard cuts between distinct shots. Do not embed captions or text into generated footage; add them in editing.

Use available video, voice, image, and editing tools only after the user has approved a script and storyboard when the workflow involves paid, rate-limited, or irreversible generation. Never upload, publish, send, or schedule the video on any platform without separate explicit permission.

## Verify and deliver

Before delivery, verify the final export's aspect ratio, duration, resolution, and presence of audio/captions as requested. Check that the visible product identity is consistent, no face appears, captions do not cover key product details, and claims match the supplied evidence. State any unverified product feature or production limitation plainly. If no rendering tools exist, label the deliverable as a production package rather than a finished video.
