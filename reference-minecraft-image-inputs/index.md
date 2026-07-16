---
layout: default
title: Minecraft Image-Art Input Field Reference
description: Record dimensions, transparency, palette, orientation, and material reserve.
---

# Minecraft Image-Art Input Field Reference

| Field | Meaning | Common mistake |
| --- | --- | --- |
| Source dimensions | Original pixel width and height | Confusing source and output size |
| Output dimensions | Intended block width and height | Stretching the aspect ratio accidentally |
| Transparency | Pixels excluded or replaced | Counting transparent background as blocks |
| Palette/version | Allowed blocks and game version | Using unavailable blocks |
| Orientation | Wall, floor, or map-art direction | Ignoring directional textures |
| Section size | Construction checkpoint dimensions | Building without verifiable boundaries |
| Reserve | Extra blocks for placement errors | Collecting exactly the displayed count |

Prepare the image with [Minecraft Image Art](https://mcimgart.com). Save the settings with the palette count so the conversion can be reproduced later.
