---
layout: default
title: Sky Event Timing Benchmark
---

# Sky Event Timing Benchmark

This dataset tests schedule calculations around reset, late arrival, and travel buffers.

| Case | Time remaining | Event duration | Travel | Expected |
| --- | ---: | ---: | ---: | --- |
| A | 45 min | 10 min | 6 min | Safe |
| B | 18 min | 10 min | 6 min | Safe with 2-min buffer |
| C | 15 min | 10 min | 6 min | Too late |
| D | 25 min | 12 min | 8 min | Safe with 5-min buffer |
| E | 20 min | 12 min | 8 min | Exact, no resilience |

## Acceptance matrix

- Displayed reset time uses the selected local timezone.
- Travel is counted before the event, not after it.
- Exact-fit plans are labelled risky rather than comfortably safe.
- A late arrival reduces the remaining activity window.

Check the cases against [Sky Clock Online](https://skyclockonline.com) without changing timezone between rows.

