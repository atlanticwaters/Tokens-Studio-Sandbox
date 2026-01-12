# Tokens

## Layering
- core: primitives only, no references
- semantic: role-based tokens, references to core only
- components: component-scoped tokens, references to semantic only (foundation.json is shared component adapter referencing semantic)

## Notes
- Opacity primitives live in `core/opacity.json` ($type: opacity).
- Alpha colors are kept as raw color tokens in `core/color-alpha.json` to remain compatible with Token Studio (no color math).
