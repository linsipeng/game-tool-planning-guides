---
layout: default
title: Survivor.io Upgrade Benchmark
---

# Survivor.io Upgrade Benchmark

This dataset tests fair comparisons between incremental levels and breakpoint upgrades.

| Case | Currency | Option A | Option B | Expected comparison |
| --- | ---: | --- | --- | --- |
| A | 10,000 | 2 weapon levels | 1 armor level | Same stage assumptions |
| B | 20,000 | 4 weapon levels | Equipment breakpoint | Include remaining currency |
| C | 35,000 | Character level | Weapon breakpoint | Compare stage output |
| D | 50,000 | Mixed upgrades | Single major tier | Report total cost |
| E | 75,000 | Current build | Saved future build | Separate present/future |

## Acceptance matrix

- Both options use identical stage and character assumptions.
- Costs include all prerequisite levels.
- Remaining currency is reported.
- Lifetime totals are not confused with the next upgrade cost.

Recreate the five rows in [Survivor.io Calculator](https://survivoriocalc.com) and compare like-for-like outputs.

