---
action_type: Main action
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: Melee 1 or ranged 5
effect: If a target is [force moved](../../../../movement/forced-movement.md) into another creature, they must make a [free strike](../../../common/main-actions/free-strike.md) against that creature.
feature_type: ability
file_basename: panic-in-their-lines
file_dpath: feature/ability/tactician/level-6
flavor: You confuse your foes, causing them to turn on each other.
item_id: panic-in-their-lines
item_name: Panic in Their Lines
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "6"
name: Panic in Their Lines
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/panic-in-their-lines
source: mcdm.heroes.v1
target: Two creatures
tier1: 6 + M damage; slide 1
tier2: 9 + M damage; slide 3
tier3: 13 + M damage; slide 5
type: ability
---

```ds-feature
cost: 9 Focus
distance: Melee 1 or ranged 5
effects:
    - effect: If a target is [force moved](../../../../movement/forced-movement.md) into another creature, they must make a [free strike](../../../common/main-actions/free-strike.md) against that creature.
    - roll: Power Roll + Might
      tier1: 6 + M damage; slide 1
      tier2: 9 + M damage; slide 3
      tier3: 13 + M damage; slide 5
feature_type: ability
flavor: You confuse your foes, causing them to turn on each other.
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 9 Focus
    distance: Melee 1 or ranged 5
    effect: If a target is [force moved](../../../../movement/forced-movement.md) into another creature, they must make a [free strike](../../../common/main-actions/free-strike.md) against that creature.
    flavor: You confuse your foes, causing them to turn on each other.
    keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "6"
    name: Panic in Their Lines
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/panic-in-their-lines
    target: Two creatures
    tier1: 6 + M damage; slide 1
    tier2: 9 + M damage; slide 3
    tier3: 13 + M damage; slide 5
    type: ability
name: Panic in Their Lines
target: Two creatures
type: feature
usage: Main action
```
