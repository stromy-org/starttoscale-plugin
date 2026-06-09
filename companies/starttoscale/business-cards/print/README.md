# Print-ready business cards (PDF/X-1a)

`c01-eu-print.pdf` is the press deliverable: 2-page (front + back), EU 85×55 mm
trim, 3 mm bleed, crop marks, CMYK, fonts embedded, PDF/X-1a:2003.

## How it's built

From `client-data/clients/starttoscale/`, run the brand-builder converter on the
vector sources in `../source/`:

```bash
python <stromy-org>/.claude/skills/brand-builder/scripts/build-card-print-pdf.py \
    --front business-cards/source/c01-eu-front.svg \
    --back  business-cards/source/c01-eu-back.svg \
    --size eu --icc-target eu \
    --out business-cards/print/c01-eu-print.pdf
```

The **`source/` SVGs are the editable master** — change the design there and
re-run the command to regenerate this PDF.

## ⚠️ Profile provenance — re-render before sending to a printer

The committed `c01-eu-print.pdf` was rendered with the macOS **Generic CMYK**
profile as a proof — it is a valid PDF/X-1a but **not colour-accurate for a
press**. For production, drop the EU press profile
`PSOcoated_v3.icc` (FOGRA51, from eci.org) into
`<stromy-org>/.claude/skills/brand-builder/assets/icc/` and re-run with
`--icc-target eu`. Always confirm the standard/profile the chosen print house
prefers.

Requires `brew install librsvg ghostscript` (native tools, operator-local).
```
