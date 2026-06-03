---
action_type: Main action
distance: Melee 1
effect: You can [shift](../../../movement/shifting.md) up to the same number of squares that you pushed the target.
feature_type: ability
file_basename: driving-pounce
file_dpath: feature/ability/raden
flavor: Your enemies try in vain to fall back from your pouncing attack.
item_id: driving-pounce
item_name: Driving Pounce
keywords:
    - Melee
    - Strike
    - Weapon
kit: raden
name: Driving Pounce
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.raden/driving-pounce
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 4 + A damage
tier2: 7 + A damage; push 1
tier3: 9 + A damage; push 2
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You can [shift](../../../movement/shifting.md) up to the same number of squares that you pushed the target.
    - roll: Power Roll + Agility
      tier1: 4 + A damage
      tier2: 7 + A damage; push 1
      tier3: 9 + A damage; push 2
feature_type: ability
flavor: Your enemies try in vain to fall back from your pouncing attack.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    effect: You can [shift](../../../movement/shifting.md) up to the same number of squares that you pushed the target.
    flavor: Your enemies try in vain to fall back from your pouncing attack.
    keywords:
        - Melee
        - Strike
        - Weapon
    kit: raden
    name: Driving Pounce
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.raden/driving-pounce
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage
    tier2: 7 + A damage; push 1
    tier3: 9 + A damage; push 2
    type: ability
name: Driving Pounce
target: One creature or object
type: feature
usage: Main action
```
