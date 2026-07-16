---
layout: default
title: Minecraft Image Conversion Methodology
---

# Minecraft Image Conversion Methodology

## Conversion model

Map source pixels to permitted block colours after resolving dimensions, transparency, aspect ratio, and palette restrictions.

## Evaluation order

1. Inspect source size and alpha channel.
2. Select output dimensions with preserved aspect ratio.
3. Define allowed block palette.
4. Compare dithering off and on.
5. Protect small details.
6. Validate preview and material list.

## Assumptions

- Transparent pixels produce no block.
- Palette availability matters as much as colour distance.
- Dithering can improve gradients but harm sharp symbols.
- The material list is part of the output quality check.

Compare conversion passes in [Minecraft Image Art](https://mcimgart.com).

