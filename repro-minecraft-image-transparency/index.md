---
layout: default
---

# Minecraft Image Transparency Reproduction

## Input

- Source: 32×32 PNG
- Transparent border: 4 pixels on every side
- Output scale: one source pixel per block
- Palette: current selected version

## Expected result

Transparent border pixels must not inflate visible palette block counts.

## Reproduce

1. Process the source in [Minecraft Image Art](https://mcimgart.com).
2. Record source and output dimensions.
3. Compare counts with transparency preserved and replaced.
4. Inspect a full-size preview.
5. Export the chosen palette count with settings.

Pass when the visible area and material total reflect the selected transparency behavior.
