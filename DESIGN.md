<!-- SEED: re-run /impeccable document once there's code to capture the actual tokens and components. -->

---
name: "Cravio JO"
description: "Premium dessert bakery landing page — elegant, warm, indulgent"
---

# Design System: Cravio JO

## 1. Overview

**Creative North Star: "The Midnight Patisserie"**

Cravio's digital presence is a dark, warm-lit bakery window at night. The surface is deep and moody — like walking into a premium Amman patisserie after sunset, where the gold-lit display cases do all the talking. The desserts glow against the dark; the brand doesn't shout, it invites.

This is a **committed** color strategy: one saturated brand color carries 30–60% of the surface. The deep blue-black background is the canvas; warm gold accents and product photography carry the warmth and indulgence. Typography pairs an elegant serif display with a warm Arabic-first sans-serif body. Motion is choreographed — scroll-driven reveals, staggered entrances, and intentional transitions that feel cinematic without being flashy.

**Reference direction:** Almond Coffee House (premium local bakehouse nominated for best cafe design in Jordan), Rumi Cafe (literary warmth in Jabal Al Weibdeh), the emerging modern Amman cafe culture — spaces that feel authentically Jordanian, sophisticated, and design-conscious without importing a European or Western template.

**Key Characteristics:**
- Deep, moody surfaces with warm gold accents
- Photography-forward — desserts are the hero, not decoration
- Arabic-first typography with elegant English pairings
- Cinematic scroll reveals that respect reduced motion
- Premium restraint — luxury through craft, not excess

## 2. Colors

**The Committed Rule.** A single saturated color — deep blue-black — carries 30–60% of the surface. Gold is the accent, used sparingly (≤10% of any screen). Cream and warm neutrals serve text and light surfaces. This is not a multi-color system; the restraint IS the voice.

### Primary
- **Midnight Blue** `[to be resolved during implementation]`: The brand's dominant color — used as the page background, hero sections, and card surfaces. Should read as a deep blue-black (not pure black, not navy). Hint of blue so it's unmistakably Cravio, not generic dark mode.

### Neutral
- **Pure White** `[to be resolved during implementation]`: Text on dark surfaces. Pure white, no cream tint, for maximum contrast against midnight blue.
- **Warm Cream** `[to be resolved during implementation]`: Light surface variant for occasional contrast sections. Very sparing use — most content lives on dark.
- **Muted Gold-Gray** `[to be resolved during implementation]`: Secondary text, subtle borders, dividers. A warm gray that carries a hint of gold.

### Accent
- **Burnished Gold** `[to be resolved during implementation]`: CTAs, highlights, section dividers, badge accents. Used on ≤10% of any screen. Its rarity is the point. Must carry readable text (dark, not white, since gold is light).

**The Warmth-Through-Accent Rule.** Warmth comes from the gold accents and product photography, not from tinting the background or text. The surface stays cool (deep blue-black) so the warmth reads as intentional, not ambient.

## 3. Typography

**Display Font:** Playfair Display (serif) — for the Cravio wordmark, hero headlines, and section titles. Elegant, editorial, timeless.

**Body Font (Arabic):** Cairo — warm, rounded sans-serif with full Arabic character set. 400 for body, 600 for emphasis, 700 for headings.

**Body Font (English):** Poppins — geometric sans-serif that pairs well with Cairo's warmth. 300 for light text, 400 for body, 500-600 for emphasis.

**Character:** The serif display carries the luxury; the warm sans keeps it approachable. Cairo and Poppins share a similar geometric warmth that makes the bilingual pairing feel intentional, not patched together. The combined feel is "editorial bakery" — like a high-end food magazine translated into Arabic.

### Hierarchy (to be refined during implementation)
- **Display** (Playfair Display, bold, clamp): Hero headlines only. Maximum 2–3 words.
- **Headline** (Cairo/Poppins, 600–700): Section titles, category headers.
- **Body** (Cairo/Poppins, 400): Product descriptions, paragraphs. Max line length 65–75ch.
- **Label** (Cairo/Poppins, 500–600, uppercase for English): CTAs, badges, navigation.

**The Arabic-First Rule.** Every typographic decision starts with Arabic. Cairo was chosen for its Arabic character set first, its Latin pairing second. English is accommodated, not centered. RTL layout is the default; LTR is the exception.

## 4. Elevation

**The Flat-By-Default Rule.** Surfaces are flat at rest. Depth comes from color contrast (dark surface, light cards) and subtle borders, not shadows. Shadows appear only as a response to state: hover elevation on cards, focus rings on inputs, the WhatsApp FAB's ambient glow.

The dark background naturally creates depth — lighter elements (cards, images, CTAs) pop forward without shadow assistance. This is a tonal-depth system, not a shadow-depth system.

## 5. Components

*No components exist yet. This section will be populated on the next `/impeccable document` scan after implementation.*

## 6. Do's and Don'ts

### Do:
- **Do** use deep blue-black as the dominant surface — it's the brand's signature
- **Do** let product photography carry the warmth — desserts should glow against the dark
- **Do** use gold accents sparingly — one gold element per viewport section is enough
- **Do** lead with Arabic — RTL layout first, English as secondary
- **Do** keep CTAs clear and tappable — minimum 44×44px touch targets on mobile
- **Do** respect `prefers-reduced-motion` — all choreographed animations must degrade to instant reveals

### Don't:
- **Don't** use warm-cream/beige/sand as a page background — the AI default bakery template
- **Don't** apply Islamic geometric patterns, arabesque, or ornate calligraphy as decoration — this is NOT a traditional Arabic sweet shop
- **Don't** use glassmorphism, gradient text, or hero-metric stats — these are SaaS clichés
- **Don't** add tiny uppercase tracked eyebrow labels above every section — "COOKIES" / "CAKES" / "DONUTS" — this is AI grammar
- **Don't** number sections as default scaffolding (01, 02, 03) — unless the content IS a sequence
- **Don't** use `border-left` or `border-right` greater than 1px as a colored accent stripe on cards or callouts
- **Don't** pair Cairo with another geometric sans — it's already paired with Poppins; don't add a third font
- **Don't** let gold exceed 10% of any screen — when everything is special, nothing is
