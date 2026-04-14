---
action_type: Free triggered
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Melee 1
effect: You can spend a Recovery.
feature_type: ability
file_basename: my-turn
file_dpath: feature/ability/fury/level-5
flavor: You quickly strike back at a foe.
item_id: my-turn
item_name: My Turn!
keywords:
    - Melee
    - Strike
    - Weapon
level: "5"
name: My Turn!
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-5/my-turn
source: mcdm.heroes.v1
subtype: triggered
target: The triggering creature
tier1: 6 + M damage
tier2: 9 + M damage
tier3: 13 + M damage
trigger: A creature causes you to be winded or dying, or damages you while you are winded or dying.
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Melee 1
effects:
    - effect: You can spend a Recovery.
    - roll: Power Roll + Might
      tier1: 6 + M damage
      tier2: 9 + M damage
      tier3: 13 + M damage
feature_type: ability
flavor: You quickly strike back at a foe.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Free triggered
    class: fury
    cost: 9 Ferocity
    distance: Melee 1
    effect: You can spend a Recovery.
    flavor: You quickly strike back at a foe.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "5"
    name: My Turn!
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-5/my-turn
    subtype: triggered
    target: The triggering creature
    tier1: 6 + M damage
    tier2: 9 + M damage
    tier3: 13 + M damage
    trigger: A creature causes you to be winded or dying, or damages you while you are winded or dying.
    type: ability
name: My Turn!
target: The triggering creature
trigger: A creature causes you to be winded or dying, or damages you while you are winded or dying.
type: feature
usage: Free triggered
```
