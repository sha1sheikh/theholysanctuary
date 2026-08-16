# assets

Logo files used by `index.html`. Each one is optional: if a file is missing the
image removes itself and the page falls back to the organisation's name in text,
with no broken-image icon.

| File | Used in | Status |
| --- | --- | --- |
| `alhikma-logo.png` | Masthead (every page) and footer credits | present |
| `silver-halo-logo.png` | Footer credits | needed |
| `inspire-films-logo.png` | Footer credits | needed |

Names must match exactly — lowercase, hyphens, no spaces. To use SVG instead,
add the `.svg` file and change the matching `src` in `index.html`.

## Requirements

**Transparent background.** The masthead and footer are dark navy (`#06192B`),
so a logo saved on a solid white background shows up as a white rectangle.
Export as PNG with transparency, or supply SVG.

**Light artwork.** For the same reason, dark elements disappear against the
footer. Any logo with black or dark grey parts needs a white or light variant
for use here — the colour version intended for white backgrounds will not read.

**Size.** Footer logos display 56px tall (44px on phones), the masthead logo
50px (38px on phones). Supply roughly 2x that height so they stay sharp on
high-density screens. Width is free; the layout preserves each logo's aspect
ratio and caps the width.
