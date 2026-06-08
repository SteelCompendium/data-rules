---
action_type: Main action
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: 3 burst
feature_type: ability
file_basename: dramatic-reversal
file_dpath: feature/ability/troubadour/level-1
flavor: Give the audience a surprise.
item_id: dramatic-reversal
item_name: Dramatic Reversal
keywords:
    - Area
    - Magic
level: "1"
name: Dramatic Reversal
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/dramatic-reversal
source: mcdm.heroes.v1
target: Self and each ally in the area
tier1: The target can [shift](../../../../movement/shifting.md) 1 square and make a [free strike](../../../common/main-actions/free-strike.md).
tier2: The target can [shift](../../../../movement/shifting.md) up to 2 squares and make a [free strike](../../../common/main-actions/free-strike.md) that gains an edge.
tier3: The target can [shift](../../../../movement/shifting.md) up to 3 squares and make a [free strike](../../../common/main-actions/free-strike.md) that gains an edge, then can spend a [Recovery](../../../../rule/health/recoveries.md).
type: ability
---

```ds-feature
cost: 5 Drama
distance: 3 burst
effects:
    - roll: Power Roll + Presence
      tier1: The target can [shift](../../../../movement/shifting.md) 1 square and make a [free strike](../../../common/main-actions/free-strike.md).
      tier2: The target can [shift](../../../../movement/shifting.md) up to 2 squares and make a [free strike](../../../common/main-actions/free-strike.md) that gains an edge.
      tier3: The target can [shift](../../../../movement/shifting.md) up to 3 squares and make a [free strike](../../../common/main-actions/free-strike.md) that gains an edge, then can spend a [Recovery](../../../../rule/health/recoveries.md).
feature_type: ability
flavor: Give the audience a surprise.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: troubadour
    cost: 5 Drama
    distance: 3 burst
    flavor: Give the audience a surprise.
    keywords:
        - Area
        - Magic
    level: "1"
    name: Dramatic Reversal
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/dramatic-reversal
    target: Self and each ally in the area
    tier1: The target can [shift](../../../../movement/shifting.md) 1 square and make a [free strike](../../../common/main-actions/free-strike.md).
    tier2: The target can [shift](../../../../movement/shifting.md) up to 2 squares and make a [free strike](../../../common/main-actions/free-strike.md) that gains an edge.
    tier3: The target can [shift](../../../../movement/shifting.md) up to 3 squares and make a [free strike](../../../common/main-actions/free-strike.md) that gains an edge, then can spend a [Recovery](../../../../rule/health/recoveries.md).
    type: ability
name: Dramatic Reversal
target: Self and each ally in the area
type: feature
usage: Main action
```
