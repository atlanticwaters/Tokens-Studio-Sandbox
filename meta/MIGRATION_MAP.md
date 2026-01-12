# Migration Map (old -> new)

## File moves (token paths mostly unchanged)
- tokens/color.json -> tokens/core/color-base.json + tokens/core/color-alpha.json
- tokens/spacing.json -> tokens/core/spacing.json
- tokens/radius.json -> tokens/core/radius.json
- tokens/border-width.json -> tokens/core/border-width.json
- tokens/typography.json -> tokens/core/typography-primitives.json
- tokens/effects.json -> tokens/core/effects.json
- tokens/semantic.json -> tokens/semantic/semantic.json
- tokens/component-tokens.json -> tokens/components/foundation.json
- tokens/buttons.json -> tokens/components/button.json
- tokens/ios-overrides.json -> tokens/platform/ios.json

## Path renames (semantic)
- surface.greige -> surface.neutral
- surface.container.greige -> surface.container.neutral
- accent.blue -> accent.info
- accent.yellow -> accent.warning
- accent.greige -> accent.neutral

All references updated accordingly.
