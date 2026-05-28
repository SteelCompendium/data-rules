---
action_type: Main action
distance: Melee 2
feature_type: ability
file_basename: net-and-stab
file_dpath: feature/ability/retiarius
flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
item_id: net-and-stab
item_name: Net and Stab
keywords:
    - Melee
    - Strike
    - Weapon
kit: retiarius
name: Net and Stab
scc: mcdm.heroes.v1/feature.ability.retiarius/net-and-stab
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Melee 2
effects:
    - effect: "*The well-thrown net that follows your main attack leaves your foes right where you want them.*\n\n| **Melee, Strike, Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF Melee 2**            | **\U0001F3AF One creature** |\n\n**Power Roll + Might or Agility:**\n\n- **≤11:** 4 + M or A damage; A < WEAK, [slowed](../../../condition/slowed.md) (EoT)\n- **12-16:** 6 + M or A damage; A < AVERAGE, [slowed](../../../condition/slowed.md) (EoT)\n- **17+:** 8 + M or A damage; A < STRONG, [restrained](../../../condition/restrained.md) (EoT)"
feature_type: ability
flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 2
    flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
    keywords:
        - Melee
        - Strike
        - Weapon
    kit: retiarius
    name: Net and Stab
    scc: mcdm.heroes.v1/feature.ability.retiarius/net-and-stab
    subtype: signature
    target: One creature
    type: ability
name: Net and Stab
target: One creature
type: feature
usage: Main action
```
