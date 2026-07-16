---
layout: default
---

# HSR Reserve-Ceiling Reproduction

## Input

- Current pity: 45
- Guarantee: no
- Available pulls: 130
- Protected reserve: 50
- Session ceiling: 80

## Expected result

No scenario may spend below the protected reserve, including a lost featured chance.

## Reproduce

1. Enter pity, guarantee, and resources in the [HSR Warp Calculator](https://hsrwarpcalc.com).
2. Model early win, normal result, and costly loss.
3. Subtract each case from available pulls.
4. Stop any path that crosses the reserve.
5. Save the action tied to each outcome.

Pass when the ceiling remains fixed after pulls begin and the costly case has a defined stop action.
