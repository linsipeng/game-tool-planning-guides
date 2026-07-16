---
layout: default
title: Shortening a PoE Map Regex Without Losing Safety
description: Compress a PoE map regex while preserving positive and negative regression cases.
---

# Shortening a PoE Map Regex Without Losing Safety

A map regex can become difficult to maintain when every dangerous modifier is added as a full phrase. Shortening it is useful only if the compressed expression still behaves correctly on real map text.

Start with a test list containing every modifier that must match, several safe modifiers that look similar, and awkward punctuation or number cases. Group phrases by distinctive fragments, but avoid fragments that also occur inside acceptable mods.

After each shortening, run the entire positive and negative set again. Measure length only after correctness is preserved. If a compact alternative is hard to understand, keep a commented source version in your notes so it can be rebuilt after game text changes.

Generate and test candidates with [PoE Map Regex](https://poemapregex.com). The final expression should be short enough for the intended interface, but its safety comes from the regression examples, not from clever compression alone.
