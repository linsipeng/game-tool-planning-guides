---
layout: default
title: Minecraft Image-Art Output Audit
description: Diagnose unexpected dimensions, colors, or material counts in converted image art.
---

# Minecraft Image-Art Output Audit

Use this checklist when converted image art has unexpected colors, dimensions, or material counts.

1. Confirm the source image dimensions and transparency.
2. Check the requested output width, height, and aspect-ratio behavior.
3. Verify the selected Minecraft palette and game version.
4. Review blocks affected by lighting, orientation, gravity, or biome tint.
5. Compare the preview at full size rather than only as a thumbnail.

Unexpected material totals often come from transparent pixels, scaling, or palette substitutions rather than a counting error. Test a small crop containing the problematic colors before processing the entire image again.

Prepare the controlled sample with [Minecraft Image Art](https://mcimgart.com). Save the source crop, settings, preview, and palette count together. Once the sample is correct, reuse the same settings for the full build and add a small placement reserve.
