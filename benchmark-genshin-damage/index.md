---
layout: default
title: Genshin Damage Input Benchmark
---

# Genshin Damage Input Benchmark

Use these fixtures to detect swapped critical fields, missing resistance assumptions, and inconsistent buff states.

| Case | ATK | Crit rate | Crit damage | DMG bonus | Expected relation |
| --- | ---: | ---: | ---: | ---: | --- |
| A | 1800 | 50% | 100% | 0% | Baseline |
| B | 1800 | 75% | 100% | 0% | Average above A |
| C | 1800 | 50% | 150% | 0% | Critical above A |
| D | 1800 | 50% | 100% | 46.6% | All hit values above A |
| E | 1600 | 80% | 160% | 46.6% | Compare by average |

## Acceptance matrix

- Non-critical output is unaffected by crit rate.
- Critical output rises with crit damage.
- Expected average stays between non-critical and critical results.
- Buffs and enemy assumptions remain fixed across comparisons.

Run the matrix in [Genshin Damage Calculator](https://gidamagecalc.com) and record all three output columns.

