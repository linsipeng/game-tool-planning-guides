---
layout: default
title: PoE Map Regex FAQ
---

# PoE Map Regex FAQ

## Why does a safe map match?

A broad substring may also occur in an unrelated modifier. Add the safe line to the regression fixture.

## Why did a dangerous modifier fail to match?

The pattern may use outdated wording, incorrect grouping, or an over-compressed fragment.

## Should optional modifiers share the main regex?

Usually keep them separate so mandatory rejection remains predictable.

## How do I shorten a regex safely?

Save the last passing version and rerun every reject and allow line after each change.

## Are dangerous examples enough for testing?

No. False-positive controls are equally important.

## When should the fixture be refreshed?

After game wording changes, adding a modifier, or changing the pattern structure.

Run the complete fixture in [PoE Map Regex](https://poemapregex.com).

