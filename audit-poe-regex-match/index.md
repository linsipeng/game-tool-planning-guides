---
layout: default
title: PoE Map Regex Match Audit
description: Reduce false positives and missed dangerous modifiers with reproducible cases.
---

# PoE Map Regex Match Audit

Use this checklist when a map regex misses a dangerous modifier or highlights an acceptable map.

1. Copy the exact map text instead of retyping it.
2. Confirm capitalization, punctuation, spacing, and numeric ranges.
3. Test each alternation independently before combining patterns.
4. Keep positive, negative, and boundary examples.
5. Recheck the expression after every shortening.

A fragment can match an unintended word, while a full phrase can fail after game text changes. Prefer distinctive fragments backed by regression cases rather than compression alone.

Test the copied examples with [PoE Map Regex](https://poemapregex.com). Record the game version and expected result beside every case. When a failure appears, reduce it to the smallest text that still reproduces the problem, fix that case, and rerun the complete set.
