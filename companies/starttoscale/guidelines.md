# Start to Scale Financial Management — Brand Guidelines

**Version 1.0 · 2026-06-01 · derived from `charter.json`**

> Plain Dutch. No jargon. No false urgency. Speaks like a senior CFO at a board table: direct, honest about what's broken, confident about how to fix it.

---

## 1. Brand foundation

| Field | Value |
|---|---|
| Brand name | Start to Scale Financial Management |
| Short name | Start to Scale |
| Slug | `starttoscale` |
| Founder | Wilgert Hart, Managing Partner |
| Geography | Netherlands (Amersfoort) — international touchpoints |
| Primary language | Dutch (`nl`) |
| Supported languages | Dutch, English |
| Domain | `starttoscalefinance.nl` |
| Backers | Duke Strategies (silent partners) |
| Archetype | Sage (primary) · Caregiver (secondary) |

### Essence

Senior CFO leadership that turns gut-feel finance into the structure a scale-up actually needs.

### Positioning

Start to Scale Financial Management is the senior finance partner that takes a growing SME from kladje-on-the-back-of-the-envelope to a fully professional finance function — diagnosis, roadmap, hands-on implementation, and ongoing operation. Wilgert Hart brings nearly 30 years of CFO experience at WPP, EMI and Warner Music Benelux, backed by a network of finance professionals.

### Audience

Owners and boards of NL-based start-ups making the scale-up transition (€1M–€20M revenue, growing fast, finance still informal).

### Personality

Senior · Calm · Structured · Pragmatic · Trustworthy

---

## 2. Tagline system

**Hero (NL, three-line, primary surface):**

> Van chaos naar controle.
> Van onderbuik naar inzicht.
> Van start-up naar serieuze scale-up.

**Supporting (EN, single line, secondary / international surface):**

> Finance that scales with you.

**Rules:**
- The NL three-line hero is the headline on the homepage and the cover of every deliverable.
- The EN supporting line is used in international correspondence, signatures, and EN-locale pages.
- Never translate the NL hero into English. Use the EN line instead.
- Never break the rhythm of the NL hero — three lines, same meter, same dot punctuation.

---

## 3. Voice

| Do | Don't |
|---|---|
| Plain Dutch, board-table register | Buzzwords ("synergy", "next-level", "agile") |
| Name what's broken, then say what fixes it | Vague reassurance |
| Use numbers when you have them | Use numbers as decoration |
| Short sentences. Then a longer one when nuance matters. | Long sentences that hide the verb |
| Treat the reader as a peer | Hype, urgency, "limited time" framing |
| Switch to English cleanly when the reader does | Mix NL and EN in the same sentence |

**Voice test:** Read it back as if Wilgert is delivering it across a boardroom table to a CEO he respects. If it sounds like a brochure, rewrite it.

---

## 4. Logo system

| File | Use |
|---|---|
| `logos/logo.svg` | Primary wordmark on light/paper backgrounds. Default. |
| `logos/logo_white.svg` | Wordmark on navy or photo backgrounds. |
| `logos/logo_mono.svg` | Single-colour use (emboss, foil, single-colour print). Uses `currentColor`. |
| `logos/symbol.svg` | Standalone Three-Steps mark. Use when the wordmark is already established (favicons at 32px+, social avatars, watermarks, app icons). |
| `logos/symbol_white.svg` | Standalone mark on dark backgrounds. |
| `logos/icon_dark.svg` | 96×96 navy-rounded-square icon (app icon, large favicon). |
| `logos/favicon.svg` | 64×64 navy-rounded-square favicon. |

**Construction (Step Rail):**
- Four bars in a fixed geometric ascent — each bar is +18% taller than the one before.
- Bar width 16 units, gap between bars 6 units, 1px corner radius.
- The mark is **single-colour**: amber on navy (hero), navy on paper (marks). No two-tone cap — the ascent itself is the signature.
- The wordmark is set in **Archivo Bold** with an Archivo caption beneath, tracked 0.20em, reading `FINANCIAL MANAGEMENT`.

**Clear space:** Minimum clear space around the wordmark = height of the tallest bar. Don't crowd it.

**Minimum size:** Wordmark 120px wide. Symbol 16px (favicon) is the smallest deployment — all four bars must remain visible.

**Don't:**
- Don't recolour the bars mid-mark. The rail is one colour at a time.
- Don't drop a bar or add a fifth. Four bars, +18% ascent — that progression is the meaning.
- Don't round the bars into a "bar-chart" look; the 1px radius is the maximum.
- Don't tilt or rotate. The rail is upright, always.

> ⚠️ The wordmark SVGs use `<text>` referencing the Archivo webfont. Before deploying to print/PDF or contexts where Archivo may not be available, convert the wordmark text to outlined paths (Illustrator, fontTools, or Inkscape "Object to Path"). The Step Rail symbol/motif SVGs are pure geometry and need no conversion.

---

## 5. Colour system

### Primary palette — Midnight Authority

| Token | Hex | Use |
|---|---|---|
| `--brand-primary` (Midnight Navy) | `#0A1F3D` | Headlines, logo, primary surfaces, body text |
| `--brand-primary-alt` | `#1A3358` | Hover states, secondary surfaces |
| `--brand-accent` (Amber) | `#E8A33D` | CTA, signal, logo cap, single accents — never as body text |
| `--brand-background` (Paper) | `#FAF8F3` | Default background, warm off-white |
| `--brand-background-alt` | `#FFFFFF` | Cards, raised surfaces |
| `--brand-text` | `#0A1F3D` | Body text on paper |
| `--brand-text-light` | `#6B7280` | Captions, meta, secondary text |

### Semantic palette

| Token | Hex | Use |
|---|---|---|
| `--success` | `#4A7A5A` | Positive states (forest, palette-aligned) |
| `--warning` | `#C28F3D` | Caution (amber-adjacent) |
| `--error`   | `#B85648` | Issues (muted brick) |
| `--info`    | `#4A6390` | Informational (navy-derived) |

Each semantic has a `-light` variant for background fills.

### Application rules

- **Accent is a signal**, not a decoration. One amber element per surface — the logo cap, a CTA button, a single data accent. Never both a button and an underlined link in amber on the same page.
- **Body text is navy** (`--brand-primary`), not pure black. Pure black reads cold and impersonal.
- **Backgrounds default to paper** (`#FAF8F3`), not pure white. Pure white reads as a software product; paper reads as a finance partner.
- **Dark sections** use navy (`--brand-primary`), with paper or white text and amber accent — for hero closes, key quotes, and section-of-honour treatment only.

---

## 6. Typography

| Role | Family | Weight | Source |
|---|---|---|---|
| Display / Headings | Archivo | 700–800 (Bold) | Google Fonts (OFL) |
| Body | Archivo | 400 (Regular) | Google Fonts (OFL) |
| Label / Eyebrow (Component L) | Archivo | 600, UPPER, tracked 0.20em | Google Fonts (OFL) |
| Mono / Data | JetBrains Mono | 400 | Google Fonts |

**Pairing logic:** Archivo is a confident, engineered grotesque with a wide weight range — it carries the Sage archetype as *diagnostic clarity* rather than literary warmth, and reads as modern and precise for a senior finance buyer. Hierarchy comes from weight + case + tracking within one family (Bold display → Regular body → 600-caps eyebrow), not a second typeface. JetBrains Mono is reserved for numbers, tables, and code-adjacent surfaces so columns align. The **eyebrow / small-title** is Archivo caps at 0.20em tracking — a deliberate brand signal, never the shared mono default.

**Type scale** (defined in `tokens.css`):

| Token | Size | Use |
|---|---|---|
| `--text-display-xl` | 56px | Hero on landing pages |
| `--text-display-lg` | 44px | Hero on internal pages |
| `--text-h1` | 32px | Page title |
| `--text-h2` | 26px | Section title |
| `--text-h3` | 22px | Subsection title |
| `--text-h4` | 18px | Card title |
| `--text-body-lg` | 17px | Lead paragraph |
| `--text-body` | 16px | Body |
| `--text-caption` | 12px | Captions, meta |
| `--text-overline` | 11px | Overlines (tracked 0.18em uppercase) |

**Rules:**
- Headings in Archivo Bold (700, or 800 for display) with `--tracking-tight` (-0.02em).
- Body in Archivo Regular with `--leading-body` (1.7).
- Overlines / eyebrows and the wordmark caption are tracked `--tracking-label` (0.20em), uppercase, Archivo Semibold (`.font-label` / `.overline`).
- Numbers in data contexts use JetBrains Mono so columns align.

---

## 7. Motif — Step Rail

**Construction:** Four rectangles in a fixed +18% geometric ascent (relative heights ≈ 0.40 / 0.59 / 0.79 / 1.00), bar width 16, gap 6, 1px corner radius. Single-colour: amber on navy, navy on paper. It doubles as the standalone symbol, the divider, and a data-bar language.

**Files:**

| File | Use |
|---|---|
| `assets/svg/motif-step-rail.svg` | Primary motif — section openers, slide divider corners, hero accents |
| `assets/svg/divider-line.svg` | Section rule — short ascending rail at the left + navy rule |
| `assets/svg/divider-line-white.svg` | Same rule, white on dark |
| `assets/svg/pattern-tile.svg` | Background tile at 8–10% opacity — for slide backgrounds, never main reading surfaces |

**Where the motif lives:**
- Section openers in presentations (small, left-aligned over the section title)
- Top-right corner of business-card backs and PDF/slide covers
- Cover marks on PDF reports
- The left of horizontal dividers (the ascent encodes the "start → scale" direction)
- As a hero accent beside the NL three-line tagline
- Micro-scale: KPI-row bullets and data annotations (the rail reads as a mini bar-language)

**Don't:**
- Don't use the motif more than once as a *signature* per visible surface (its data-bar use is separate).
- Don't drop a bar or add a fifth. Four bars, +18% ascent, is the meaning.
- Don't round the bars beyond 1px or tilt/rotate the rail. It is upright, always.

---

## 8. Imagery direction

The image catalogue is populated in a separate Phase 4 pass. The approved direction is **two themes, equal weight**:

### I1 · Architectural Minimalism (Architecturaal Minimalisme)

Clean lines, controlled light, sense of order. Office interiors, modernist façades, calm geometry. Visual proxy for the structured finance function S2S installs.

**Keywords:** stillness · structure · light · authority
**Roles:** cover · divider · closing

### I2 · Data Clarity (Data Helderheid)

Charts, tables, dashboards rendered as quiet objects. Numbers as artefact, not decoration. Turning raw data into decision-grade insight.

**Keywords:** precision · signal · order · insight
**Roles:** divider · background

**Treatment rules:**
- All hero/cover images get a 55% navy (`--brand-primary`) tint overlay.
- Logo on image always uses the white variant.
- Avoid: stock-photo handshakes, generic suits-in-meetings, mountain landscapes (no Alpine, no Dolomite — Wilgert flagged the polders-versus-mountains distinction explicitly), feel-good office candids.

---

## 9. Component patterns

Tokenised utility classes ship in `tokens.css`:

- `.btn-primary` — navy button on paper, body text in paper colour. Default CTA.
- `.btn-accent` — amber button on paper, body text in navy. Used once per page max — the "talk to Wilgert" close.
- `.btn-ghost` — outlined navy button on paper. Secondary actions.
- `.card` — white card on paper with thin neutral border.
- `.badge-success / -warning / -error / -info` — small semantic badges.
- `.divider` — horizontal rule with the navy-90 / amber-10 split.
- `.overline` / `.font-label` — 11px Archivo Semibold uppercase, tracked 0.20em (Step Rail eyebrow).

---

## 10. Surface inventory

### Document templates (`templates/html/`)

| File | Status |
|---|---|
| `templates/html/business-cards.html` | Single concept, dual-side layout |
| `templates/html/email-signature.html` | Single concept with NL and EN strings |

### Pending (Phase 5 finishing pass)

- `templates/docx/styles.docx` — DOCX style base for `docx` skill
- `templates/docx/letterhead.docx` — fixed-layout letterhead with continuation page
- `pptx-assets/` — branded gradient + photo overlay + motif tile PNGs for the `pptx-hd` skill
- `templates/pptx/` — HTML page shells (cover, section-divider, content, closing, footer-bar)
- `fonts/` — TTF/OTF for Archivo, JetBrains Mono (embedded for DOCX/PPTX/PDF)
- `logos/*.png` — pre-rendered PNG variants of every logo SVG (favicon-16/32/180/192, logo + logo_white at 1x/2x/3x)

These are tracked in `BUILD_LOG.md § Phase 5` and require a Node + Sharp + docx-js rendering pass to materialise.

---

## 11. Maintaining these guidelines

This file is a **derived view** of `charter.json` plus the strategic context that doesn't fit in JSON (voice rules, construction notes, application rules).

When `charter.json` changes — colours, fonts, logo wiring, image catalogue, templates — regenerate the relevant sections of this file in the same promotion step. Never let `guidelines.md` go stale relative to `charter.json`.
