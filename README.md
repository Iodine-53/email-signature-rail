# Rail — HTML Email Signature

A pixel-robust HTML email signature: navy sidebar rail, monogram badge, live contact rows, CTA button and stat strip. 600×306 — standard landscape signature proportions. Built as a portfolio piece for an HTML-signature gig — every detail is placeholder, swap in your own.

![preview](preview.png)

## Why this layout survives real inboxes

- **No graphic ever shares a row with live text** — the #1 cause of white-band breakage when phones reflow text under fixed image slices.
- **Table layout, inline CSS only** — Outlook-safe.
- **Dividers are CSS borders**, never part of an image.
- **Foreground images** (badge, icons) live in fixed-size cells; nothing decorative needs to align with text baselines.
- Verified: normal render + forced-font render, zero banding.

## Files

| File | What |
|------|------|
| `signature.html` | Source of truth, references `slices/` relatively |
| `signature-standalone.html` | Local slices base64; social icons load from ibb.co hosted URLs — paste-ready |
| `slices/` | `e5_monogram.png`, white contact icons (`e5_ic_*`) regenerated from glyph alpha; socials use hosted ibb.co links (see `signature.html`) |
| `preview.png` | Rendered preview |

## Placeholders to replace

Contact details (`+1 (555) 013-4470`, `hello@jordanblake.design`, `jordanblake.design`, `Austin, TX`), all four social links (`href="#"`), and the portfolio URL.

## Use

Copy `signature-standalone.html` into Gmail / Outlook / Apple Mail signature settings, or host `slices/` and use `signature.html` with absolute image URLs.
