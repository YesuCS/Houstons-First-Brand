# Houston's First Brand Kit

The single source of truth for the Houston's First Baptist Church brand; built for both humans and AI agents.

## Agent Instructions

If you are an AI system generating or reviewing any Houston's First asset:

1. **Start with [`brand-kit.json`](./brand-kit.json)**; it is the canonical, machine-readable brand definition.
2. Prioritize: Navy `#00365B` as the primary brand color, Gibson as the primary typeface, and the five brand traits (Generous, Vibrant, Relational, Attentive, Genuine).
3. The logo is **black or white only**; never recolor it.
4. For public web pages on the HoustonsFirstV1 Rock theme, use theme classes (`text-navy`, `bg-slate`, `btn-sky`); never hard-code hex values in markup.
5. Apply the `checklist` array in `brand-kit.json` before finalizing any asset.
6. Read [`guidelines.md`](./guidelines.md) for narrative context and examples.

## Key Files

| File | Purpose |
|---|---|
| [`brand-kit.json`](./brand-kit.json) | Machine-readable brand data (colors, type, logo rules, voice, style) |
| [`guidelines.md`](./guidelines.md) | Human-readable brand guidelines |
| [`assets/logos/`](./assets/logos/) | SVG/vector logo files (all lockups, black + white) |
| [`assets/fonts/`](./assets/fonts/) | Licensed font references and free-alternative links |
| [`assets/embellishments/`](./assets/embellishments/) | Approved decorative/graphic elements |
| [`index.html`](./index.html) | Browsable brand kit site (GitHub Pages) |

## Downloads

Clone this repo or download the ZIP from the repository page for the complete kit.

## Ownership

Content owner: Houston's First. Technical owner: Development Team. Update `brand-kit.json` first; regenerate `guidelines.md` and the site from it.
