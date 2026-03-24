---
name: amazon-listing-planner
description: This skill should be used when the user wants to "plan a product listing", "create a detail page brief", "策划详情页", "新品上新", "上架新品", "product page planning", "write Amazon listing content", "策划亚马逊详情页", "create listing strategy", or needs help with Amazon product page copywriting, visual planning, or a new product launch brief. Always activate this skill when a new product is being launched on Amazon, even if the user doesn't say "listing" explicitly.
version: 1.0.0
---

# Amazon Listing Planner

A skill for producing professional Amazon product detail page (PDP) strategy briefs that drive high CTR (Click-Through Rate) and CVR (Conversion Rate) on the North America market.

This skill covers four core problem areas:
1. **Brand positioning** — establishing a clear, consistent brand voice and identity
2. **Product positioning** — defining the product's differentiated value proposition
3. **Marketing awareness** — applying North America consumer psychology and buying triggers
4. **Localized copywriting** — crafting native-quality English copy that resonates with US/CA shoppers

---

## How to Use This Skill

When a user initiates a new product listing or detail page project, follow the workflow below in order. Do not skip steps unless the information is already clear from context.

---

## Step 1 — Intake Interview

Ask the user for the following. Combine questions into no more than 2 messages to avoid friction:

**Message 1:**
- Product name and category (e.g., "clip-on book light", "wake-up light alarm clock")
- Key product features: list up to 5 physical/functional specs
- Target retail price on Amazon (USD)
- Main competitors (optionally, an ASIN or brand name)
- Any existing brand name or style guide

**Message 2 (if needed):**
- Who is the target buyer? (demographics, lifestyle, pain point)
- Any mandatory claims or certifications (e.g., CE, FCC, eye-safe LED)
- Any forbidden claims or sensitive topics
- Are there existing visual assets (product photos, lifestyle images)?
- What is the desired tone? (premium, cozy/warm, techy/precise, fun/bright)

If the user is in a hurry or provides partial info, use the brand context from `references/brand-framework.md` to fill reasonable gaps and state your assumptions.

---

## Step 2 — Brand & Product Positioning

Before writing any copy, define the strategic foundation. Output a concise positioning block:

```
BRAND POSITIONING
Brand Personality: [3 adjectives, e.g. "Warm · Thoughtful · Reliable"]
Brand Promise: [1 sentence]
Target Emotion: [What feeling should the buyer have after purchase?]

PRODUCT POSITIONING
Hero Benefit: [The #1 reason this product exists for the buyer]
Key Differentiators: [2–3 specific, provable claims vs. competitors]
Objection Pre-empt: [Top 1–2 doubts a shopper has and how we address them]
Search Intent Match: [Primary job-to-be-done — functional or emotional?]
```

Reference `references/brand-framework.md` for tone calibration and brand consistency guidance.

---

## Step 3 — Keyword & SEO Layer

Identify the top keyword clusters for this product's niche. Structure them as:

- **Primary keyword** (highest volume, exact match — goes in title and bullet 1)
- **Secondary keywords** × 3–5 (mid-volume, use in bullets and description)
- **Long-tail / occasion keywords** × 3–5 (e.g., "gift for book lovers", "dorm room reading light")

Use North America shopper language. Avoid translating Chinese product names literally.

---

## Step 4 — Title Formula

Apply Amazon's title best practices:

```
[Brand] + [Primary Keyword] + [Top Feature or Benefit] + [Variant or Size if relevant]
```

Rules:
- 150–200 characters max (check mobile truncation at ~80 chars)
- No ALL CAPS for non-acronyms
- Include the #1 search keyword naturally
- Lead with the emotional hook or top differentiator if possible

Output **2 title options** and explain which is recommended and why.

---

## Step 5 — 5 Bullet Points (Key Product Features)

Each bullet follows this structure:
```
[BENEFIT HOOK in caps] — [Proof point or feature detail]. [Emotional payoff or use scenario].
```

Bullet order:
1. **Hero benefit** (most compelling differentiator)
2. **Comfort / ease of use** (removes friction for the buyer)
3. **Quality / durability** (addresses doubt)
4. **Versatile use cases** (broadens appeal)
5. **Gift / occasion angle OR brand promise** (emotional close)

Each bullet: 200–250 characters. No promotional phrases like "best" or "amazing."
Reference `references/copywriting-swipe.md` for North America–tested phrasing patterns.

---

## Step 6 — Product Description / A+ Content Plan

### Option A: Text-only Description (Standard Listing)
Write a 3–4 paragraph narrative description (~200 words). Structure:
1. **Lead with the problem** the product solves
2. **Introduce the product** and its core promise
3. **Feature highlights** in plain language (not a repeat of bullets)
4. **Call to action / close** (gift appeal, satisfaction, brand assurance)

### Option B: A+ Content Module Plan (if brand-registered)
Propose a module layout. Reference `references/amazon-listing-formula.md` for the A+ module blueprint.

Standard 5-module layout:
| Module | Type | Purpose |
|--------|------|---------|
| M1 | Hero Banner | Brand header + tagline |
| M2 | Feature Grid (3-col) | Top 3 benefits with icons |
| M3 | Comparison Table | Us vs. generic, highlight wins |
| M4 | Lifestyle Story | Emotional use-case image + copy |
| M5 | Brand Bar | Trust signals, warranty, contact |

---

## Step 7 — Image Brief

Provide a shot list and visual direction for the designer.

### Main Image (White Background)
- Product must occupy ≥85% of frame
- Most legible angle, show key functional detail if possible
- No text overlays permitted

### Image 2–3: Feature Callout
- Annotated product view with labels
- Highlight top 2–3 differentiators visually
- Use clean, modern typography (sans-serif, high contrast)

### Image 4–5: Lifestyle / Context
- Show product in use by a relatable North America persona
- Match target buyer: e.g., "30s woman reading in bed", "college student at desk"
- Warm, natural lighting preferred over studio sterile look
- Props should reinforce the emotional story (cozy blanket, coffee mug, etc.)

### Image 6: Comparison or Spec Sheet
- Side-by-side with generic competitor or feature comparison table
- Emphasize unique differentiator visually

### Image 7 (optional): Social Proof / Packaging
- UGC-style testimonial overlay or 5-star graphic
- Show retail packaging if premium unboxing is a selling point

Reference `references/amazon-listing-formula.md` for image spec rules.

---

## Step 8 — Output the Full Brief

Compile all steps into a single structured document for the visual designer. Format:

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📦 [PRODUCT NAME] — AMAZON LISTING BRIEF
Date: [today's date] | Market: 🇺🇸 USA
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1. BRAND & PRODUCT POSITIONING
[Filled block from Step 2]

2. KEYWORDS
Primary: ...
Secondary: ...
Long-tail: ...

3. TITLE OPTIONS
Option A: ...
Option B: ...
✅ Recommended: ...

4. BULLET POINTS
• ...
• ...
• ...
• ...
• ...

5. DESCRIPTION / A+ PLAN
[Text or module table]

6. IMAGE BRIEF
Shot 1 (Main): ...
Shot 2 (Feature): ...
...

7. DESIGNER NOTES
Tone: ...
Color palette suggestion: ...
Do NOT: ...
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## Quality Checklist (self-review before output)

Before delivering the brief, verify:

- [ ] Title is ≤200 chars, includes primary keyword, readable on mobile
- [ ] Each bullet opens with a capitalized benefit hook
- [ ] No prohibited Amazon claims (free, guaranteed, #1, etc. without proof)
- [ ] Copy is written in native US English, not translated Chinese
- [ ] Brand positioning is consistent across title, bullets, and description
- [ ] Image brief specifies subject, angle, lighting, and emotional story
- [ ] All differentiators are specific and provable — no vague superlatives

---

## Additional Reference Files

Read these files when more detail is needed:

- **`references/brand-framework.md`** — Brand personality types, tone calibration, brand promise examples for consumer electronics
- **`references/amazon-listing-formula.md`** — Amazon character limits, A+ module specs, SEO rules, prohibited claims
- **`references/copywriting-swipe.md`** — North America–tested copy patterns, emotional triggers, localization tips, product-specific example phrases
