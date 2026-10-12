# DNA-X logo pack

Generated, not hand-drawn. The mark is pure type, so it can be rebuilt at
any size without losing fidelity.

## The two marks

| | used for |
|---|---|
| **X** — the mark | favicons, app icons, square avatars. The only thing that reads at 16px. |
| **DNA^x** — the wordmark | wide formats, social covers, GHL business logo slots. |

Same split as the PsikiQ pack: a single glyph for small square contexts,
the full wordmark where there is room.

## Palette — taken from the live site's own tokens

| token | hex | use |
|---|---|---|
| `--dnax-navy` | `#1A1A2E` | default ground |
| `--dnax-deep-navy` | `#080808` | on-dark variant |
| `--dnax-orange` | `#E84C1E` | the mark, and the superscript x |
| `--dnax-light-bg` | `#F8F8F8` | on-light variant |

## Typeface

**Barlow Black** for DNA and the X mark, **Barlow ExtraBold** for the
superscript — the same family the site loads. SIL Open Font Licence.
Rendered output carries no licence obligation; the font files themselves
are not in this repo.

## Files

`icons/` — favicon.ico (16/32/48), favicon-16, favicon-32,
apple-touch-icon (180), icon-192, icon-512

`logo/` — square 512 and 1024, on-dark 512, on-light 512, mark-avatar 512,
wide (transparent, on-dark, on-light), GHL business logo 350x180 in both
grounds plus 700x360, og 1200x630, LinkedIn cover 1128x191 and 2256x382

## Rebuilding

The generator lives outside this repo. It takes a Barlow directory and an
output directory, and overwrites the whole set. To change a colour or a
size, change it there and regenerate — do not retouch these files by hand,
because the next run will overwrite them.
