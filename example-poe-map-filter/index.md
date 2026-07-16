---
layout: default
title: PoE Map Filter Worked Example
---

# PoE Map Filter Worked Example

## Scenario

A map regex should reject reflect, no regeneration, and reduced recovery while allowing harmless text containing similar letter fragments.

## Test fixture

| Map text | Expected |
| --- | --- |
| Monsters reflect elemental damage | Reject |
| Players cannot regenerate life | Reject |
| Reduced recovery rate of life | Reject |
| Increased rarity of items found | Allow |
| Area contains additional rogue exiles | Allow |

## Decision

Treat each rejected modifier as a semantic phrase rather than an unbounded substring. Re-run the allow-list after every compression pass.

## Verification

Paste the five-line fixture into [PoE Map Regex](https://poemapregex.com). The pattern passes only when all three dangerous modifiers match and both safe lines remain unmatched.

