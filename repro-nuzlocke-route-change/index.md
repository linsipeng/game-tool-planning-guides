---
layout: default
---

# Nuzlocke Route-Change Reproduction

## Input

- Ruleset: level cap, dupes clause, no items in battle
- Current loss: planned pivot unavailable
- Next encounter: one guaranteed option and two random options
- Upcoming fight: one physical attacker and one setup threat

## Expected result

The revised plan must replace the lost role, stay under the cap, and define a fallback trigger.

## Reproduce

1. Save the original team and route.
2. Remove the unavailable pivot.
3. Check encounter context in [Nuzlocke Guide](https://nuzlockeguide.com).
4. Rank replacements by roles covered in the next two fights.
5. Confirm the new plan still works after one critical hit or missed move.

Pass when the plan produces a primary line and a named fallback without relying on the lost team member.
