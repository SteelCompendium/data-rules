---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Melee 1
effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 4 squares, bringing the target with you. While [grabbed](scc:mcdm.heroes.v1/condition/grabbed) this way, the target takes damage equal to twice your Might score at the start of each of your turns.
feature_type: ability
file_basename: pounce
file_dpath: feature/ability/fury/level-6
flavor: You strike at the target like the ultimate predator you are.
item_id: pounce
item_name: Pounce
keywords:
    - Magic
    - Melee
    - Strike
    - Weapon
level: "6"
name: Pounce
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-6/pounce
source: mcdm.heroes.v1
target: One creature
tier1: 8 damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
tier2: 13 damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
tier3: 17 damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Melee 1
effects:
    - effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 4 squares, bringing the target with you. While [grabbed](scc:mcdm.heroes.v1/condition/grabbed) this way, the target takes damage equal to twice your Might score at the start of each of your turns.
    - roll: Power Roll + Might
      tier1: 8 damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
      tier2: 13 damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
      tier3: 17 damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
feature_type: ability
flavor: You strike at the target like the ultimate predator you are.
keywords:
    - Magic
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 9 Ferocity
    distance: Melee 1
    effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 4 squares, bringing the target with you. While [grabbed](scc:mcdm.heroes.v1/condition/grabbed) this way, the target takes damage equal to twice your Might score at the start of each of your turns.
    flavor: You strike at the target like the ultimate predator you are.
    keywords:
        - Magic
        - Melee
        - Strike
        - Weapon
    level: "6"
    name: Pounce
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-6/pounce
    target: One creature
    tier1: 8 damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
    tier2: 13 damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
    tier3: 17 damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
    type: ability
name: Pounce
target: One creature
type: feature
usage: Main action
```
