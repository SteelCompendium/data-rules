---
action_type: Main action
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: Melee 1
effect: The target can make a melee [free strike](../../../trait/common/main-actions/free-strike.md) against you. If they do, you can make a melee [free strike](../../../trait/common/main-actions/free-strike.md) against the target.
feature_type: ability
file_basename: en-garde
file_dpath: feature/ability/troubadour/level-2
flavor: Wait, it's... Guard! Turn! Parry! Dodge! Spin! Thrust! Ha!
item_id: en-garde
item_name: En Garde!
keywords:
    - Melee
    - Strike
    - Weapon
level: "2"
name: En Garde!
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.troubadour.level-2/en-garde
source: mcdm.heroes.v1
target: One creature
tier1: 7 + **A** damage
tier2: 11 + **A** damage
tier3: 16 + **A** damage
type: ability
---

```ds-feature
cost: 5 Drama
distance: Melee 1
effects:
    - effect: The target can make a melee [free strike](../../../trait/common/main-actions/free-strike.md) against you. If they do, you can make a melee [free strike](../../../trait/common/main-actions/free-strike.md) against the target.
    - roll: Power Roll + Agility
      tier1: 7 + **A** damage
      tier2: 11 + **A** damage
      tier3: 16 + **A** damage
feature_type: ability
flavor: Wait, it's... Guard! Turn! Parry! Dodge! Spin! Thrust! Ha!
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 5 Drama
    distance: Melee 1
    effect: The target can make a melee [free strike](../../../trait/common/main-actions/free-strike.md) against you. If they do, you can make a melee [free strike](../../../trait/common/main-actions/free-strike.md) against the target.
    flavor: Wait, it's... Guard! Turn! Parry! Dodge! Spin! Thrust! Ha!
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "2"
    name: En Garde!
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-2/en-garde
    target: One creature
    tier1: 7 + **A** damage
    tier2: 11 + **A** damage
    tier3: 16 + **A** damage
    type: ability
name: En Garde!
target: One creature
type: feature
usage: Main action
```
