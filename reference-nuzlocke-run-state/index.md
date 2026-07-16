---
layout: default
title: Nuzlocke Run-State Field Reference
description: Define reproducible fields for encounter and boss planning.
---

# Nuzlocke Run-State Field Reference

| Field | Meaning | Common mistake |
| --- | --- | --- |
| Game and version | Exact title or ROM ruleset | Mixing encounter tables between versions |
| Ruleset | Dupes, level caps, item rules | Leaving house rules implicit |
| Area status | Unused, caught, failed, deferred | Counting subareas twice |
| Team role | Damage, pivot, status, immunity | Tracking species but not purpose |
| Next cap | Maximum level before the fight | Applying the cap after entering |
| Fallback trigger | Condition that changes the plan | Writing only the ideal line |

Check encounter and fight context with [Nuzlocke Guide](https://nuzlockeguide.com). Save the assumptions beside the team snapshot so another player can understand why the plan was valid at that point in the run.
