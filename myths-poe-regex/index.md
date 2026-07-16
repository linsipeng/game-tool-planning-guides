---
layout: default
title: PoE Map Regex Misconceptions
---

# PoE Map Regex Misconceptions

## “A shorter regex is automatically better”

Compression is only an improvement if the full reject and allow fixture remains unchanged.

## “Matching one distinctive word is safe”

Broad fragments can occur inside harmless modifiers and create false positives.

## “Testing dangerous lines is sufficient”

Safe control lines are required to prove that the pattern does not overmatch.

## “Optional preferences belong in the mandatory pattern”

Keeping them separate makes the rejection rule easier to audit and reuse.

## “A pattern keeps working after game wording changes”

Modifier text should be checked against the current in-game wording and regression fixture.

Run both positive and negative cases in [PoE Map Regex](https://poemapregex.com).

