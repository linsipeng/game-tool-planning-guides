---
layout: default
title: HSR Warp Plan QA Checklist
---

# HSR Warp Plan QA Checklist

Use this checklist before committing passes to a banner.

## Starting state

- [ ] Banner type is correct.
- [ ] Current pity comes from the matching banner history.
- [ ] Guarantee state is recorded.
- [ ] Available passes exclude protected currency.

## Boundaries

- [ ] Reserve amount is explicit.
- [ ] Hard-pity ceiling is calculated from current pity.
- [ ] Featured-loss outcome is considered when not guaranteed.
- [ ] A stop rule is defined before pulling.

## Session record

- [ ] Every five-star result updates pity and guarantee.
- [ ] Early success triggers a pause and review.
- [ ] Reserve is never reclassified mid-session.
- [ ] Remaining passes are recorded after stopping.

Validate the starting state and ceiling in [HSR Warp Calculator](https://hsrwarpcalc.com).

