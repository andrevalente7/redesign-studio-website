# Design System

## Source

The current visual system is based on the attached `DESIGN-raycast.md` reference.

## Applied Direction

- Near-black canvas: `#07080a`
- Surface ladder: `#0d0d0d`, `#101111`, `#121212`
- Hairline borders: `#242728`
- Tight radii: 4px, 6px, 8px, 10px, 16px
- Orange primary CTA and glassy orange accents
- Inter/system sans typography with `calt`, `kern`, `liga`, and `ss03`
- Command-palette hero surface
- No red stripe motif at the top of the page
- Orange degradé and glass effects across buttons, cards, logo tiles, and product-like details

## Implementation

- Base styles remain in `Source/Styles/styles.css`.
- Design-system overrides live in `Source/Styles/design-system.css`.
- The page loads `design-system.css` after the base stylesheet so future design-system changes can be made in one focused file.
