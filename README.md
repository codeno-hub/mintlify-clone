# Mintlify Documentation Website Recreation

A pixel-faithful, desktop-first recreation of the [Mintlify](https://mintlify.com) documentation platform homepage — built with pure HTML and CSS (no JavaScript, no frameworks, no Tailwind).

---

## Sections Recreated

| # | Section | Status |
|---|---------|--------|
| 1 | **Top Navigation Bar** — Logo, nav links, CTA | ✅ |
| 2 | **Hero Section** — Headline, description, email input, browser mockup | ✅ |
| 3 | **Documentation Preview** — 3-column: sidebar nav + main content + TOC | ✅ |
| 4 | **Trusted By / Logos** — Row of company logos (Anthropic, Coinbase, Cursor, Perplexity, Vercel, HubSpot, PayPal, Replit) | ✅ |
| 5 | **Feature Highlights** — 3× two-column sections (Design, AI, API) with visual mockups | ✅ |
| 6 | **Intelligent Assistant UI Preview** — Large UI mockup with stale-doc detection interface | ✅ |
| 7 | **Enterprise Features** — 6-card grid (Security, Compliance, Private Docs, Custom Domain, Support, Analytics) | ✅ |
| 8 | **Case Studies / Customer Stories** — 4-card layout with featured card (Perplexity, Vercel, Glean, Replit) | ✅ |
| 9 | **Final Call-To-Action** — Headline, dual CTA buttons | ✅ |
| 10 | **Footer** — Brand, 4-column links, legal row | ✅ |

---

## Fonts Used

| Font | Weight | Usage |
|------|--------|-------|
| **Inter** (Google Fonts) | 300, 400, 500, 600, 700, 800 | All text — body, headings, UI labels |
| **SF Mono / Fira Code / Cascadia Code** | 400 | Code blocks (system font stack) |

> Mintlify's actual product uses Inter throughout — matching the brand's clean, modern developer aesthetic.

---

## Colors Used

| Variable | Hex | Usage |
|----------|-----|-------|
| `--green` | `#0D9373` | Primary brand color, CTAs, active states |
| `--green-light` | `#10b981` | Code prompt accents |
| `--green-muted` | `#dcfce7` | Badges, highlighted backgrounds |
| `--text-primary` | `#111827` | Headings, body text |
| `--text-secondary` | `#374151` | Secondary text |
| `--text-muted` | `#6b7280` | Subheadings, descriptions |
| `--text-subtle` | `#9ca3af` | Labels, placeholders |
| `--border` | `#e5e7eb` | Card borders, dividers |
| `--bg-secondary` | `#f9fafb` | Section backgrounds |
| `--code-bg` | `#0f172a` | Code block backgrounds (dark) |

---

## Technical Constraints Met

- ✅ Pure HTML + CSS only
- ✅ No JavaScript
- ✅ No TailwindCSS
- ✅ No animation or motion effects
- ✅ Desktop-first layout (no responsive breakpoints)
- ✅ SVG icons drawn inline (no external icon libraries)
- ✅ All brand colors matched to Mintlify's actual palette

---

## Layout Approach

- **Grid-based layouts** throughout: doc preview uses a 3-column grid, feature rows use 2-column, enterprise uses 3-column
- **CSS Custom Properties** for consistent color/radius/shadow tokens
- **Sticky navbar** with backdrop blur
- **Box shadows** with multiple layers for depth on UI mockups
- **Inline SVG icons** handcrafted to approximate Mintlify's icon style
- **Browser chrome mockup** in the hero section to simulate the doc product

---

## File Structure

```
mintlify-recreation/
├── index.html       # Full single-page markup
├── styles.css       # All styles (~700 lines, organized by section)
└── README.md        # This file
```

---

