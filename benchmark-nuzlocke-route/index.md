---
layout: default
title: Nuzlocke Route Planning Benchmark
---

# Nuzlocke Route Planning Benchmark

This fixture tests whether a route plan remains legal after encounters, losses, and level-cap changes.

| Case | Captured species | Lost role | Next cap | Expected plan |
| --- | --- | --- | ---: | --- |
| A | Water starter, early bird | None | 14 | Keep original route |
| B | Water starter, early bird | Defensive pivot | 14 | Reserve guaranteed encounter |
| C | Fire starter, cave encounter | Fast cleaner | 18 | Add priority backup |
| D | Grass starter, duplicate route roll | None | 18 | Apply dupes clause reroll |
| E | Water starter, over-levelled bird | None | 20 | Bench bird before boss |

## Acceptance matrix

- Every suggested encounter must still be available.
- No planned battler may exceed the stated cap.
- A lost role cannot appear in later steps.
- Duplicate handling must follow the selected clause.

Validate the five cases with [Nuzlocke Guide](https://nuzlockeguide.com) and save any rule variation alongside the result.

