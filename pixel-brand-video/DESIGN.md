# Design spec — Arzbar warm pixel

## Concept

Loose, disconnected work pieces snap into a legible route: diagnose first, then choose only the tools that fit. Pixel blocks are the visual metaphor for turning scattered fragments into a clear system.

## Palette

- Canvas: `#f5efe6`
- Raised surface: `#eadfd2`
- Ink: `#30251f`
- Muted text: `#78685d`
- Rules: `#d7c5b4`
- Main accent: `#b85f3c`
- Secondary accent: `#e6c66b`
- Caution accent: `#b55248`

These are inherited from the warm Arzbar page. Keep the light canvas; use the terracotta at full strength for key actions and pixel wipes.

## Typography

Use the site's Traditional Chinese sans and rounded handwritten display pairing where installed (`Noto Sans TC` / `LXGW WenKai TC`), with Windows Traditional Chinese fallbacks for local rendering. Use `Martian Mono` or a mono fallback only for small scene labels. Headlines are 72–96 px, supporting copy 30–38 px, and labels at least 22 px at 1920×1080.

## Composition

The six-step route and the decision hub carry the message. Anchor headlines to the left or upper edge; keep diagrams on the right or across the lower half. Use the 16×9 pixel-grid wipe as the recurring transition. The final frame uses only the site's existing text name and LINE URL, without inventing a separate logo.

## Motion

Four 7.5-second scenes: scattered work resolves to a question; six steps assemble in sequence; four solution paths connect to a diagnosis hub; the existing wordmark and CTA resolve through a pixel reveal. Keep entrances readable and staggered. Motion and all scene changes are seek-safe and deterministic.
