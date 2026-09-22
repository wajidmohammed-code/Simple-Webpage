# Oklahoma Christian University — DESIGN.md

A lightweight design system for building web pages and apps that feel consistent with
Oklahoma Christian University's brand identity.

## Brand Voice
Oklahoma Christian University (OC) is a private Christian university in Edmond, OK.
Communications should feel: **trustworthy, warm, academically serious, and rooted in
faith** — never flashy or gimmicky. Copy should be direct and welcoming, avoiding
corporate jargon.

## Color Palette

| Role | Name | Hex | Usage |
|---|---|---|---|
| Primary | OC Maroon | `#660000` | Headers, nav bars, primary buttons, links |
| Primary Dark | Maroon Deep | `#4A0000` | Hover/active states, footer background |
| Secondary | Silver Gray | `#CCCCCC` | Borders, dividers, secondary backgrounds |
| Accent | Eagle Tan | `#E2D79B` | Callouts, highlights, badges |
| Neutral Light | Off White | `#F7F6F4` | Page background |
| Neutral Dark | Charcoal Text | `#222222` | Body copy |
| Success | Green | `#2E7D32` | Confirmations only |
| Alert | Red | `#B3261E` | Warnings/errors only — do not confuse with brand maroon |

> Rule: Maroon carries brand weight. Never place large blocks of bright/competing color
> next to it — let maroon and tan do the talking, gray does the resting.

## Typography

- **Headings:** A clean serif or slab serif (e.g., "Source Serif Pro" or system serif) —
  conveys the academic, established feel.
- **Body:** A neutral sans-serif (e.g., "Source Sans Pro", "Inter", or system sans) for
  readability at small sizes.
- **Scale:** H1 40px / H2 28px / H3 22px / Body 16px / Small 13px. Line-height 1.5 for body.
- Do not use more than 2 typefaces on a single page.

## Logo & Imagery
- Use the official OC Eagle mark or wordmark; never recolor, stretch, rotate, or add
  effects (drop shadows, glows, bevels) to the logo.
- Maintain clear space around the logo equal to the height of the "O" in the mark.
- Photography should be warm, natural-light, candid campus/student life shots — avoid
  stock-photo stiffness.

## Layout & Spacing
- Base spacing unit: 8px. Use multiples of 8 for padding/margins (8, 16, 24, 32, 48...).
- Max content width: 1200px, centered, with 24px side gutters on mobile.
- Cards/panels: 1px `#CCCCCC` border or soft shadow, 8px corner radius, 24px internal padding.

## Components

**Buttons**
- Primary: maroon `#660000` background, white text, 8px radius, hover → `#4A0000`.
- Secondary: white background, maroon border + text, hover → tan `#E2D79B` fill.

**Navigation**
- Maroon top bar, white/light-gray text, active link underlined in tan.

**Callout / Alert Boxes**
- Left border 4px in accent color (tan for info, red for warnings), light tinted
  background, icon + short bolded label.

## Accessibility
- Maroon `#660000` on white passes WCAG AA for normal text (contrast ratio > 7:1).
- Never rely on tan alone to convey meaning (low contrast) — pair with text/icon.
- All interactive elements need a visible focus state (2px tan outline).

## Tone Checklist for any generated page
- [ ] Maroon and gray dominate; tan used sparingly as accent
- [ ] Serif headings, sans body
- [ ] Generous whitespace (8px grid)
- [ ] Copy is warm, direct, no corporate buzzwords
- [ ] Logo unaltered, proper clear space
