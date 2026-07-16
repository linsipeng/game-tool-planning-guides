---
layout: default
title: PoE Map Regex Regression Card
description: Preserve must-match, must-not-match, and boundary cases for a PoE map regex.
---

# PoE Map Regex Regression Card

Keep three groups of real map-mod text:

## Must match

- Dangerous modifiers the filter must catch

## Must not match

- Acceptable modifiers with similar words or numbers

## Boundary cases

- Punctuation, abbreviations, combined mods, and changed wording

Test every group in [PoE Map Regex](https://poemapregex.com) after adding, removing, or shortening a pattern. Record the game version and the final expression beside the examples.

A compact regex is only an improvement when the full regression card still passes. Preserve the readable source list even if the in-game expression must be shortened.
