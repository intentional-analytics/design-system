# Intentional Design System

## Overview

**Intentional** is a commercial growth consultancy that helps businesses solve revenue growth problems through brand strategy, creative execution, business data analysis, and AI-enabled execution. The brand projects confidence, precision, and intelligence — designed to command trust at the highest commercial level.

### Sources Provided
- **Logo mark**: `uploads/18.05.29-Logo-1000px.png` — Red circular badge with white 3-pointed navigation arrow mark
- **Brand illustration**: `uploads/10Up_Red.png` — Overlapping circles filled with red line-pattern textures (the "10Up" motif)
- **Fonts**: PP Neue Montreal Medium, PP Neue Montreal Mono Medium, Founders Grotesk X Condensed Bold + Semibold
- **No codebase or Figma link provided** — design system built from brand brief and assets

---

## CONTENT FUNDAMENTALS

### Voice & Tone
- **Confident, not boastful.** Statements are declarative. "We solve revenue problems" not "We try to help with revenue challenges."
- **Direct.** Short sentences. No hedging. No filler words.
- **Authoritative but human.** The brand speaks peer-to-peer with senior business leaders — not at them.
- **We vs. You.** First-person plural ("We work with…") when describing the company. Second person ("Your growth…") when addressing the client.
- **No emoji.** The brand does not use emoji — ever. The tone is too serious for it.
- **Sentence case** for UI and body copy. **ALL CAPS** for display/eyebrow/label type — never mixed case for those roles.
- **No exclamation marks.** The brand earns emphasis through design, not punctuation.
- **Vibe**: Boardroom intelligence. Moody. Considered. Restrained. Purposeful.

### Copy Examples
- "Revenue growth, solved."
- "Where strategy becomes momentum."
- "Built for leaders who move fast."
- "Data. Brand. AI. Results."
- "We turn growth problems into growth systems."

---

## VISUAL FOUNDATIONS

### Color
- **Background**: `#0F0F10` — near-black, almost charcoal. Not pure black; slightly warm.
- **Primary text**: `#F2F0EC` — near-white with a warm, slightly creamy tint. Never pure white.
- **Secondary text**: `#9A9896` — mid-grey, warm undertone.
- **Muted / disabled**: `#5C5B59`
- **Accent**: `#D4271C` — a saturated, punchy red. Used sparingly and deliberately. Never decorative.
- **Elevated surfaces**: `#1A1A1B`, `#232324` — near-invisible layering above background.
- **Borders**: Translucent white at 10–20% opacity. Barely visible separators.

### Typography
Three typefaces, each with a distinct role:

| Face | Role | Weight | Treatment |
|---|---|---|---|
| Founders Grotesk X Condensed | Display / Hero / Headlines | Bold (700), Semibold (600) | ALL CAPS, very tight tracking |
| PP Neue Montreal | Body / UI / Headings | Medium (500) | Sentence case, slightly negative tracking |
| PP Neue Montreal Mono | Data / Code / Labels | Medium (500) | Used for numeric data, code, mono UI |

- Display type runs **extremely large** — 64px to 112px+. Tight leading (1.05).
- Body copy is generous: 16–18px, leading 1.45.
- Eyebrow labels: all-caps, wide tracking (0.12em), accent red or mid-grey.
- The type system creates contrast through **scale**, not weight variety.

### Imagery
- **Large-scale, moody, atmospheric.** Photography that uses dramatic lighting, shadows, and natural gradients.
- Images are **full-bleed backdrops**, not decorative thumbnails.
- Text is **layered directly over imagery** with high-contrast separation (dark overlays, gradient washes, or natural dark zones in the photo).
- **Directional lighting** within the image frames the text — light draws the eye toward the message.
- Images feel **cinematic and directional** — not stock, not illustrative.
- Preferred tonal grade: **cool-dark**, desaturated with retained shadow depth. Occasional warm grade for warmth.

### Brand Illustration: The 10Up Circles
- A cluster of overlapping circles, each filled with a distinct red line pattern: concentric rings, dot grids, radial rays, square spirals, wave lines, cross-hatch.
- This is the brand's **primary textural motif** — used as a background flourish, section divider, or atmospheric element.
- Always in **Intentional Red** (`#D4271C`) on a light or dark surface.
- Never used as a primary visual; always in the background or periphery.

### Logo
- **Mark**: Red circle (`#D4271C`) containing a white 3-pointed directional arrow/star form. Represents direction, navigation, and intentionality.
- **Usage**: The mark works alone at small scales. Full wordmark (not provided) pairs with the mark.
- **Clearspace**: Minimum 1× the mark's diameter in all directions.
- **Never** recolor the mark. Never use on a similarly red background.

### Spacing
- 4px base unit. Scale: 4, 8, 12, 16, 20, 24, 32, 40, 48, 64, 80, 96, 128.
- Layouts breathe — generous whitespace is a brand signal. Density is avoided.
- Section padding typically 80–128px vertical.

### Corner Radii
- **Minimal rounding**: 2px (sm), 4px (md), 8px (lg).
- **Pills** (full radius) used only for tags/badges.
- Cards and panels tend toward sharp or very subtly rounded corners (2–4px). This is a confident, architectural brand — not a friendly rounded-corners brand.

### Borders & Dividers
- Translucent white: `rgba(242, 240, 236, 0.10)` for subtle separation.
- Stronger at 0.20 opacity when clearly delineating sections.
- 1px only. No thick borders.

### Cards
- Background: `#1A1A1B` or `#232324` (slightly elevated above page bg).
- Border: `rgba(242,240,236,0.10)` — 1px.
- Corner radius: 2–4px.
- Shadow: `0 4px 16px rgba(0,0,0,0.6)`.
- No colored left-border accents. No heavy shadows.

### Shadows & Elevation
- Shadows are **deep and dark**, not coloured. Background is so dark that elevation is expressed primarily through background color stepping.
- Accent glow (`0 0 32px rgba(212,39,28,0.25)`) used very sparingly on high-signal interactive states.

### Animation
- **Easing**: Ease-out (`cubic-bezier(0.16, 1, 0.3, 1)`) — fast start, smooth settle. Never bouncy.
- **Duration**: 150ms (micro), 250ms (default), 400ms (transitions/reveals).
- **Reveal style**: Fade up — elements enter from slightly below with opacity 0→1. No slides from the side.
- **No playful animations.** The brand is measured and deliberate.

### Hover & Press States
- **Links / text buttons**: Opacity 0.7 on hover. No underlines unless inline body text.
- **Buttons**: Background darkens (`--color-accent-hover`). Slight scale-down (0.98) on press.
- **Cards**: Border opacity increases to 0.25. Subtle background lightening.
- **No color surprises on hover.** Interactions stay within the established palette.

### Blur / Transparency
- Used for overlays on photography: `backdrop-filter: blur(12–24px)`.
- Frosted glass panels: dark tinted (`rgba(15,15,16,0.75)` + blur).
- Used strategically for modals, tooltips, floating UI over imagery.

### Iconography
See ICONOGRAPHY section below.

---

## ICONOGRAPHY

### Approach
Intentional does not have a proprietary icon font. The brand uses **minimal, stroke-based line icons** consistent with its architectural, high-end aesthetic.

- **Style**: Thin to regular stroke weight (1–1.5px), geometric, no fill. Clean and precise.
- **Size**: 16px (UI), 20px (standard), 24px (prominent).
- **Color**: `--color-fg2` (mid-grey) by default; `--color-fg1` (near-white) for active/primary; `--color-accent` sparingly for signal.
- **Recommended CDN set**: [Lucide Icons](https://lucide.dev) — matches the stroke weight and geometric style.
- **Emoji**: Never used.
- **Unicode chars as icons**: Occasionally — arrows (→, ↗), dashes (—) as punctuation-level decoration.

### Assets Available
- `assets/logo-mark.png` — Primary brand mark (red circle + white arrow)
- `assets/10up-red-circles.png` — Brand textural illustration (overlapping patterned circles)

---

## File Index

```
README.md                        — This file; brand overview and guidelines
SKILL.md                         — Agent skill definition
colors_and_type.css              — All CSS design tokens (colors, type, spacing, radius, shadow)
fonts/                           — All brand webfonts
  PPNeueMontreal-Medium.*        — Body / UI typeface (woff2, woff, ttf, otf)
  PPNeueMontrealMono-Medium.*    — Mono typeface (woff2, woff, ttf, otf)
  FoundersGroteskXCond-Bold.ttf  — Display typeface, bold
  FoundersGroteskXCond-Semibold.ttf — Display typeface, semibold
assets/
  logo-mark.png                  — Brand mark (red circle)
  10up-red-circles.png           — Brand illustration / texture
preview/                         — Design system card previews (shown in Design System tab)
ui_kits/
  website/                       — Marketing / consulting website UI kit
    index.html                   — Interactive prototype
    README.md                    — Kit-specific notes
```
