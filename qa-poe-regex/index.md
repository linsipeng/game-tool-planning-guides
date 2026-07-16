---
layout: default
title: PoE Map Regex QA Checklist
---

# PoE Map Regex QA Checklist

Use this checklist before relying on a regex during map rolling.

## Requirements

- [ ] Mandatory dangerous modifiers are listed.
- [ ] Optional avoidance rules are separate.
- [ ] Wording matches current in-game text.
- [ ] Pattern length fits the intended input field.

## Tests

- [ ] Every dangerous line matches.
- [ ] Safe control lines do not match.
- [ ] Similar substrings are included as false-positive tests.
- [ ] Combined modifiers are tested.

## Changes

- [ ] The fixture is rerun after compression.
- [ ] The previous passing pattern is retained.
- [ ] Case handling is verified.
- [ ] Results are saved with the pattern version.

Paste the complete reject and allow fixture into [PoE Map Regex](https://poemapregex.com) after every change.

