---
layout: default
title: Minecraft Image Palette Worked Example
---

# Minecraft Image Palette Worked Example

## Scenario

A 64 × 64 source image contains a transparent background, four near-identical gray shades, and a small red emblem that must remain readable after conversion.

## Conversion fixture

| Setting | Value |
| --- | --- |
| Output size | 64 × 64 blocks |
| Background | Transparent |
| Palette rule | Survival-obtainable blocks |
| Dithering | Off for first pass |
| Protected region | 12 × 12 red emblem |

## Decision

First reduce the gray shades without dithering, then inspect the emblem. Enable limited dithering only if the emblem survives and the material count remains practical.

## Verification

Run the fixture through [Minecraft Image Art](https://mcimgart.com). The output passes when transparency is preserved, the emblem remains recognizable, and the material list contains no disallowed blocks.

