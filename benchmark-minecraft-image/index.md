---
layout: default
title: Minecraft Image Conversion Benchmark
---

# Minecraft Image Conversion Benchmark

These fixtures test transparency, scaling, palette restrictions, and detail retention.

| Case | Source | Output | Transparency | Palette | Expected |
| --- | --- | --- | --- | --- | --- |
| A | 16×16 icon | 16×16 | Yes | Any | Exact silhouette |
| B | 32×32 icon | 16×16 | Yes | Any | Scaled silhouette |
| C | 64×64 photo | 64×64 | No | Survival | No disallowed blocks |
| D | 64×64 logo | 64×64 | Yes | Concrete only | Transparent background |
| E | 128×64 banner | 64×32 | No | Wool only | Aspect ratio retained |

## Acceptance matrix

- Transparent pixels do not become solid background blocks.
- Output dimensions match the requested size.
- Restricted palettes contain only allowed block families.
- Non-square images preserve aspect ratio.

Process the matrix with [Minecraft Image Art](https://mcimgart.com) and compare the preview plus material list.

