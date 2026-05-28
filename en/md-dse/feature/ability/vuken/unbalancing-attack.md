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
    - Strike
    - Weapon
kit: vuken
name: Unbalancing Attack
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.vuken/unbalancing-attack
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 4 + M damage; A < WEAK, prone
tier2: 7 + M damage; A < AVERAGE, prone
tier3: 9 + M damage; A < STRONG, prone
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 4 + M damage; A < WEAK, prone
      tier2: 7 + M damage; A < AVERAGE, prone
      tier3: 9 + M damage; A < STRONG, prone
feature_type: ability
flavor: A wild assault forces your foe onto their back.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    flavor: A wild assault forces your foe onto their back.
    keywords:
        - Melee
        - Strike
        - Weapon
    kit: vuken
    name: Unbalancing Attack
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.vuken/unbalancing-attack
    subtype: signature
    target: One creature or object
    tier1: 4 + M damage; A < WEAK, prone
    tier2: 7 + M damage; A < AVERAGE, prone
    tier3: 9 + M damage; A < STRONG, prone
    type: ability
name: Unbalancing Attack
target: One creature or object
type: feature
usage: Main action
```
