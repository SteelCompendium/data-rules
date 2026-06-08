---
action_type: Main action
distance: Ranged 10
feature_type: ability
file_basename: hamstring-shot
file_dpath: feature/ability/ranger
flavor: A well-placed shot leaves your enemy struggling to move.
item_id: hamstring-shot
item_name: Hamstring Shot
keywords:
    - Ranged
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
kit: ranger
name: Hamstring Shot
scc: mcdm.heroes.v1/feature.ability.ranger/hamstring-shot
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: "*A well-placed shot leaves your enemy struggling to move.*\n\n| **Ranged, [Strike](../../../rule/combat/strike.md), Weapon** |     **Main action** |\n|----------------------------|--------------------:|\n| **\U0001F4CF Ranged 10**           | **\U0001F3AF One creature** |\n\n**Power Roll + [Might](../../../rule/character/might.md) or [Agility](../../../rule/character/agility.md):**\n\n- **≤11:** 3 + M or A damage; A < WEAK, [slowed](../../../condition/slowed.md) (save ends)\n- **12-16:** 5 + M or A damage; A < AVERAGE, [slowed](../../../condition/slowed.md) (save ends)\n- **17+:** 7 + M or A damage; A < STRONG, [slowed](../../../condition/slowed.md) (save ends)"
feature_type: ability
flavor: A well-placed shot leaves your enemy struggling to move.
keywords:
    - Ranged
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: Ranged 10
    flavor: A well-placed shot leaves your enemy struggling to move.
    keywords:
        - Ranged
        - '[Strike](../../../rule/combat/strike.md)'
        - Weapon
    kit: ranger
    name: Hamstring Shot
    scc: mcdm.heroes.v1/feature.ability.ranger/hamstring-shot
    subtype: signature
    target: One creature
    type: ability
name: Hamstring Shot
target: One creature
type: feature
usage: Main action
```
