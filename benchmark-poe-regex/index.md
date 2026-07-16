---
layout: default
title: PoE Map Regex Benchmark
---

# PoE Map Regex Benchmark

The dataset contains dangerous modifiers, safe controls, and phrases designed to expose substring false positives.

| Text | Expected |
| --- | --- |
| Monsters reflect elemental damage | Match |
| Players cannot regenerate life, mana or energy shield | Match |
| Reduced recovery rate of life and energy shield | Match |
| Area contains two unique bosses | No match |
| Increased rarity of items found | No match |
| Monsters have increased area of effect | No match |
| Players have reduced effect of non-curse auras | Configurable |

## Acceptance matrix

- Required dangerous lines match.
- Safe control lines remain unmatched.
- Optional modifiers are clearly separated from mandatory ones.
- Compression does not change the pass/fail set.

Paste the exact lines into [PoE Map Regex](https://poemapregex.com) before and after any pattern compression.

