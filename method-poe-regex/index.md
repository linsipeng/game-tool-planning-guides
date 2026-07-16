---
layout: default
title: PoE Map Regex Testing Methodology
---

# PoE Map Regex Testing Methodology

## Test model

A pattern is evaluated against mandatory dangerous lines, optional lines, safe controls, and similar-text false-positive traps.

## Evaluation order

1. Start from exact dangerous phrases.
2. Create reject and allow fixtures.
3. Combine alternatives.
4. Replace phrases with semantic fragments only when needed.
5. Rerun the entire fixture after each edit.
6. Preserve the last passing version.

## Assumptions

- Shorter is not better unless behaviour is unchanged.
- Safe controls are required evidence.
- Optional preferences should remain separable.
- Current in-game wording is the authoritative text.

Run every pattern revision through [PoE Map Regex](https://poemapregex.com).

