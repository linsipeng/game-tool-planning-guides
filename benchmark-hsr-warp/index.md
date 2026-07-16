---
layout: default
title: HSR Warp State Benchmark
---

# HSR Warp State Benchmark

These cases test pity, guarantee, reserve, and stopping-boundary handling.

| Case | Pity | Guaranteed | Passes | Reserve | Expected maximum spend |
| --- | ---: | --- | ---: | ---: | ---: |
| A | 0 | No | 90 | 0 | 90 |
| B | 40 | No | 80 | 20 | 50 |
| C | 70 | Yes | 30 | 10 | 20 |
| D | 89 | No | 15 | 5 | 10 |
| E | 20 | No | 120 | 70 | 50 |

## Acceptance matrix

- Reserve is never counted as spendable.
- Starting pity reduces pulls to the next five-star ceiling.
- Guarantee state is preserved until a five-star result occurs.
- The stop rule wins over optimistic probability.

Evaluate every row with [HSR Warp Calculator](https://hsrwarpcalc.com) and store the resulting ceiling.

