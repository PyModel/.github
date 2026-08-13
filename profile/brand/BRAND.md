# PyModel brand system

Identity guidelines for PyModel, by Pythoughts. One idea carries the system: think first, then code. The visuals stay dark, precise, and quiet; the geodesic mark and the teal-to-violet spectrum do the talking.

## The mark

A low-poly geodesic sphere in face-on projection: 20 facets, a decagonal silhouette with 10 hull vertices at 36 degree steps, an inner pentagon at 0.54 R, and a slightly offset center vertex. Teal crowns the top and violet anchors the lower right, with the largest violet facet just right of center.

- Clear space: keep a margin of half the mark's radius on all sides.
- Minimum size: 16 px. Below that, facet strokes close up.
- The mark always sits on ink (`#0B0C10`) or a photo dark enough to read as ink.
- Do not recolor, rotate, outline, flatten to one color, or rebuild with different facet counts.

Source of truth: `icon.svg` (vector), `icon-1024.png` and `icon-512.png` (raster).

## The wordmark

"PyModel", capital P and capital M, set in Poppins Bold with tight tracking. On dark surfaces it carries the blue-to-violet gradient (`#2E8FE8` to `#7B63E6`) or solid `#EAF2FF`. Never all lowercase, never letterspaced, never in a serif.

## Color

| Token | Hex | Role |
| --- | --- | --- |
| Ink | `#0B0C10` | Backgrounds. The default surface. |
| Light | `#EAF2FF` | Primary text on ink. |
| Teal | `#27D5C9` | Eyebrows, prompts, live indicators. |
| Blue | `#2E8FE8` | Primary actions, links, carets. |
| Indigo | `#3B3F9E` | Depth, secondary surfaces, chart fills. |
| Violet | `#7B63E6` | Gradient endpoint, highlights. |

Rules: ink is the ground, light is the figure, and the four hues are accents that repeat across a surface rather than compete on it. The blue-to-violet gradient belongs to the wordmark and small highlights only. Never wash it over a background.

## Typography

| Use | Face |
| --- | --- |
| Display and headings | Poppins Bold |
| Body | Poppins Regular |
| Code, labels, eyebrows | SF Mono or the platform monospace |

Eyebrow labels are uppercase monospace with wide tracking, in teal. Body text stays sentence case. No italic display type.

## Voice

Professional, technical, and direct. Claims are specific, verifiable, and free of filler. The tagline is "Think first, then code." Write sentences a reviewer would sign off on.

## Applications

- Org profile banner: `banner.svg` (animated SVG, safe in GitHub's image sandbox)
- App and favicon: `icon.svg`, `icon-1024.png`, `icon-512.png`
- Identity board: `brand-kit.svg`, `brand-kit-3200.png`
- Terminal motifs use the real product: `pythinker review`, a teal chevron prompt, and a blue block caret.

## Do and don't

Do: hold negative space, repeat one accent per surface, keep motion under a second and reduced-motion safe.

Don't: pure `#000000` or `#FFFFFF`, gradient text on headings outside the wordmark, emoji in brand surfaces, em dashes in copy, more than one loud panel per layout.
