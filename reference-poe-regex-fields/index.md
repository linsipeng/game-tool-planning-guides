---
layout: default
title: PoE Map Regex Field Reference
description: Store readable sources and regression cases with every compressed expression.
---

# PoE Map Regex Field Reference

| Field | Meaning | Common mistake |
| --- | --- | --- |
| Game version | Patch whose modifier text was tested | Reusing old wording silently |
| Source list | Readable dangerous-mod list | Saving only the compressed regex |
| Must match | Exact dangerous examples | Testing only fragments |
| Must not match | Similar acceptable examples | Ignoring false positives |
| Boundary cases | Numbers, punctuation, abbreviations | Testing clean text only |
| Length | Final interface character count | Optimizing length before correctness |
| Expected action | Reroll, inspect, or accept | Treating every match identically |

Generate and test the expression with [PoE Map Regex](https://poemapregex.com). Rerun the complete case set whenever one pattern changes.
