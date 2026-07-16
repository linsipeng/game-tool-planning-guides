---
layout: default
title: PoE Map Regex Strategy Comparison
---

# PoE Map Regex Strategy Comparison

| Strategy | Length | False-positive risk | Maintenance | Best use |
| --- | ---: | --- | --- | --- |
| Full modifier phrases | Long | Lowest | Easy | Generous field limit |
| Semantic fragments | Medium | Low after testing | Medium | Balanced pattern |
| Aggressive substrings | Short | High | Hard | Avoid unless fully tested |
| Mandatory-only pattern | Short | Low | Easy | Consistent rejection |
| Mandatory plus optional | Long | Medium | Hard | One personal preset |

## Decision rules

- Start with full phrases and a complete fixture.
- Shorten one fragment at a time.
- Keep safe controls in every regression run.
- Separate optional rules when auditability matters.

Compare patterns using [PoE Map Regex](https://poemapregex.com).

