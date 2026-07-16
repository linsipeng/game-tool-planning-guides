---
layout: default
title: Sky Route Option Comparison
---

# Sky Route Option Comparison

| Option | Time cost | Delay tolerance | Reset risk | Best use |
| --- | ---: | --- | --- | --- |
| Full route | High | Low | High | Large open window |
| Core candle route | Medium | Medium | Medium | Normal session |
| Timed event only | Low | High | Low | Short event-focused session |
| Claim-first route | Low | High | Lowest | Near daily reset |
| Optional realm detour | Variable | Low | High | Only with surplus buffer |

## Decision rules

- Protect claims and timed events before optional detours.
- Treat exact-fit routes as fragile.
- Include measured travel and loading time.
- Refresh the route after a late start.

Use [Sky Clock Online](https://skyclockonline.com) to compare the live event and reset windows.

