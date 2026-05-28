---
action_type: Main action
distance: 1 burst
effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the power roll.
feature_type: ability
file_basename: wing-buffet
file_dpath: feature/ability/corven
flavor: Foes who try to close in around you do so at their peril.
item_id: wing-buffet
item_name: Wing Buffet
keywords:
    - Area
    - Melee
    - Weapon
kit: corven
name: Wing Buffet
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.corven/wing-buffet
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 3 damage
tier2: 6 damage
tier3: 8 damage
type: ability
---

```ds-feature
distance: 1 burst
effects:
    - effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the power roll.
    - roll: Power Roll + Agility
      tier1: 3 damage
      tier2: 6 damage
      tier3: 8 damage
feature_type: ability
flavor: Foes who try to close in around you do so at their peril.
keywords:
    - Area
    - Melee
    - Weapon
metadata:
    action_type: Main action
    distance: 1 burst
    effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the power roll.
    flavor: Foes who try to close in around you do so at their peril.
    keywords:
        - Area
        - Melee
        - Weapon
    kit: corven
    name: Wing Buffet
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.corven/wing-buffet
    subtype: signature
    target: Each enemy in the area
    tier1: 3 damage
    tier2: 6 damage
    tier3: 8 damage
    type: ability
name: Wing Buffet
target: Each enemy in the area
type: feature
usage: Main action
```
