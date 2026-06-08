---
action_type: Main action
distance: Melee 1
feature_type: ability
file_basename: unbalancing-attack
file_dpath: feature/ability/vuken
flavor: A wild assault forces your foe onto their back.
item_id: unbalancing-attack
item_name: Unbalancing Attack
keywords:
    - Melee
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
kit: vuken
name: Unbalancing Attack
scc: mcdm.heroes.v1/feature.ability.vuken/unbalancing-attack
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: "*A wild assault forces your foe onto their back.*\n\n| **Melee, [Strike](../../../rule/combat/strike.md), Weapon** |               **Main action** |\n|---------------------------|------------------------------:|\n| **\U0001F4CF Melee 1**            | **\U0001F3AF One creature or object** |\n\n**[Power Roll](../../../rule/dice/power-roll.md) + [Might](../../../rule/character/might.md):**\n\n- **≤11:** 4 + M damage; A < WEAK[, prone](../../../condition/prone.md)\n- **12-16:** 7 + M damage; A < AVERAGE[, prone](../../../condition/prone.md)\n- **17+:** 9 + M damage; A < STRONG[, prone](../../../condition/prone.md)"
feature_type: ability
flavor: A wild assault forces your foe onto their back.
keywords:
    - Melee
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    flavor: A wild assault forces your foe onto their back.
    keywords:
        - Melee
        - '[Strike](../../../rule/combat/strike.md)'
        - Weapon
    kit: vuken
    name: Unbalancing Attack
    scc: mcdm.heroes.v1/feature.ability.vuken/unbalancing-attack
    subtype: signature
    target: One creature or object
    type: ability
name: Unbalancing Attack
target: One creature or object
type: feature
usage: Main action
```
