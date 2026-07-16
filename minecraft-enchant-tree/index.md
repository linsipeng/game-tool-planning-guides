# Minecraft Enchanted-Book Combination Tree

Use a balanced tree to reduce prior-work penalties instead of adding every book to one growing item.

Model the final sequence with [Minecraft Enchant Order](https://enchantorder.com) before spending levels or rare books.

## Inventory

- Base item:
- Required enchantments:
- Incompatible enchantments removed:
- Books that must first be combined to increase level:
- Existing prior-work history:

## Balanced pairing rule

Pair fresh items with fresh items:

```text
Book A + Book B -> Pair 1
Book C + Book D -> Pair 2
Pair 1 + Pair 2 -> Group 1
```

Avoid:

```text
Base + A -> Base'
Base' + B -> Base''
Base'' + C -> Base'''
```

The second pattern repeatedly increases the history of one item.

## Execution sheet

For each operation, record:

| Step | Left item | Right item | Cost | Result |
|---|---|---|---:|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |

Check that the lower-history item is placed on the correct side when the edition and operation make that relevant.

## Safety

- Keep rare books out of experiments.
- Include intended repairs and renaming in the plan.
- Consider a fresh base item if the current one has already been worked repeatedly.
- Gather the whole book set before executing the final order.

