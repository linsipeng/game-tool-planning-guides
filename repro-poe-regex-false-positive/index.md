---
layout: default
title: PoE Regex False-Positive Reproduction
---

# PoE Regex False-Positive Reproduction

## Input

- Must match: three exact dangerous modifier lines
- Must not match: two safe lines sharing a short word fragment
- Boundary case: one line with punctuation and a number

## Expected result

The expression catches every dangerous line without highlighting the similar safe lines.

## Reproduce

1. Copy exact modifier text into [PoE Map Regex](https://poemapregex.com).
2. Test each alternation separately.
3. Combine the patterns.
4. Shorten one fragment.
5. Rerun all positive, negative, and boundary cases.

Pass only when the full case set remains correct after compression.
