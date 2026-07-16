# Path of Exile Map Regex Test Cases

Treat a map regex as a filter that requires regression tests.

Generate the candidate pattern with [PoE Map Regex Generator](https://poemapregex.com), then test it against explicit allowed and rejected examples.

## Build profile

- Damage type:
- Recovery method:
- Ailment dependence:
- Charge dependence:
- Defensive mechanics:
- League or patch:

## Modifier decisions

Classify each relevant modifier:

- Impossible: reject automatically.
- Uncomfortable: warn or inspect manually.
- Acceptable: must not match.

## Test table

| Map text | Expected | Actual | Reason |
|---|---|---|---|
| | Reject | | |
| | Allow | | |
| | Warn | | |

Include:

1. Exact dangerous modifiers.
2. Similar wording that should remain allowed.
3. Values immediately below and above numeric thresholds.
4. Maps containing several dangerous conditions.
5. Safe maps with long modifier text.

## Maintenance

Keep separate patterns for builds with different weaknesses. Label each saved regex with the build and patch. When equipment or game wording changes, update the build profile first, regenerate the pattern, and rerun every test case.

A compact pattern is not automatically a safe pattern. Readability and reproducible tests matter more than saving a few characters.

