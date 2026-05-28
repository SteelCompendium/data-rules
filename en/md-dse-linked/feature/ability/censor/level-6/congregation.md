---
action_type: Main action
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: Melee 1
effect: Each ally can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares and gains 2 surges before making the strike.
feature_type: ability
file_basename: congregation
file_dpath: feature/ability/censor/level-6
flavor: You focus your allies' wrath on a chosen foe.
item_id: congregation
item_name: Congregation
keywords:
    - Melee
    - Strike
    - Weapon
level: "6"
name: Congregation
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.censor.level-6/congregation
source: mcdm.heroes.v1
target: One creature
tier1: 8 + M damage; as a free triggered action, one ally within 10 squares of the target can use a strike signature ability against the target
tier2: 12 + M damage; as a free triggered action, one ally within 10 squares of the target can use a strike signature ability that gains an edge against the target
tier3: 16 + M damage; as a free triggered action, two allies within 10 squares of the target can each use a strike signature ability that gains an edge against the target
type: ability
---

```ds-feature
cost: 9 Wrath
distance: Melee 1
effects:
    - effect: Each ally can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares and gains 2 surges before making the strike.
    - roll: Power Roll + Might
      tier1: 8 + M damage; as a free triggered action, one ally within 10 squares of the target can use a strike signature ability against the target
      tier2: 12 + M damage; as a free triggered action, one ally within 10 squares of the target can use a strike signature ability that gains an edge against the target
      tier3: 16 + M damage; as a free triggered action, two allies within 10 squares of the target can each use a strike signature ability that gains an edge against the target
feature_type: ability
flavor: You focus your allies' wrath on a chosen foe.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 9 Wrath
    distance: Melee 1
    effect: Each ally can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares and gains 2 surges before making the strike.
    flavor: You focus your allies' wrath on a chosen foe.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "6"
    name: Congregation
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.censor.level-6/congregation
    target: One creature
    tier1: 8 + M damage; as a free triggered action, one ally within 10 squares of the target can use a strike signature ability against the target
    tier2: 12 + M damage; as a free triggered action, one ally within 10 squares of the target can use a strike signature ability that gains an edge against the target
    tier3: 16 + M damage; as a free triggered action, two allies within 10 squares of the target can each use a strike signature ability that gains an edge against the target
    type: ability
name: Congregation
target: One creature
type: feature
usage: Main action
```
