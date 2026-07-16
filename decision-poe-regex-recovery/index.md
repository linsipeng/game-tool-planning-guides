---
layout: default
title: PoE Regex False-Match Recovery Decision Tree
---

# PoE Regex False-Match Recovery Decision Tree

Use this tree when a map regex misses a dangerous modifier or rejects a safe map.

1. Is a required dangerous phrase missing?
   - Yes: test that phrase alone before recombining alternatives.
   - No: inspect false positives.
2. Does a safe control line match?
   - Yes: replace broad substrings with bounded semantic fragments.
   - No: test optional rules.
3. Are optional modifiers mixed into mandatory rejection?
   - Yes: separate them into a second pattern.
   - No: continue to compression.
4. Did compression change the fixture result?
   - Yes: restore the last passing pattern.
   - No: save the shorter version.

Run both reject and allow controls in [PoE Map Regex](https://poemapregex.com) after every edit.

