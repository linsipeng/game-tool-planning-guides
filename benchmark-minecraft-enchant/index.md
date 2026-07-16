---
layout: default
title: Minecraft Enchantment Cost Benchmark
---

# Minecraft Enchantment Cost Benchmark

This matrix checks prior-work penalties and pair-order comparisons.

| Case | Base prior work | Book A | Book B | Expected rule |
| --- | ---: | ---: | ---: | --- |
| A | 0 | 0 | 0 | Cheapest baseline |
| B | 1 | 0 | 0 | More than A |
| C | 0 | 1 | 1 | Book pairing matters |
| D | 2 | 1 | 0 | Avoid adding to base early |
| E | 3 | 2 | 2 | May approach legal limit |

## Acceptance matrix

- Prior-work values travel with the resulting item.
- Reversing an anvil operation may change level cost.
- Invalid enchantment combinations are rejected.
- The recommended order is compared against at least one alternative.

Model the cases in [Minecraft Enchant Order](https://enchantorder.com) and retain the lowest legal sequence.

