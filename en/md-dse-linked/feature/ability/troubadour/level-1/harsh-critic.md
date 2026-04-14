---
action_type: Main action
class: troubadour
cost: 3 Drama
cost_amount: "3"
cost_resource: Drama
distance: Melee 1 or ranged 10
effect: The first time the target uses an ability before the start of your next turn, any effects from the ability's tier outcomes other than damage are negated for all targets. Ability effects that always happen regardless of the power roll work as usual.
feature_type: ability
file_basename: harsh-critic
file_dpath: feature/ability/troubadour/level-1
flavor: Just one bad review will ruin their day.
item_id: harsh-critic
item_name: Harsh Critic
keywords:
    - Magic
    - Melee
    - Ranged
    - Strike
level: "1"
name: Harsh Critic
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/harsh-critic
source: mcdm.heroes.v1
target: One creature or object
tier1: 7 + P sonic damage
tier2: 10 + P sonic damage
tier3: 13 + P sonic damage
type: ability
---

```ds-feature
cost: 3 Drama
distance: Melee 1 or ranged 10
effects:
    - effect: The first time the target uses an ability before the start of your next turn, any effects from the ability's tier outcomes other than damage are negated for all targets. Ability effects that always happen regardless of the power roll work as usual.
    - roll: Power Roll + Presence
      tier1: 7 + P sonic damage
      tier2: 10 + P sonic damage
      tier3: 13 + P sonic damage
feature_type: ability
flavor: Just one bad review will ruin their day.
keywords:
    - Magic
    - Melee
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: troubadour
    cost: 3 Drama
    distance: Melee 1 or ranged 10
    effect: The first time the target uses an ability before the start of your next turn, any effects from the ability's tier outcomes other than damage are negated for all targets. Ability effects that always happen regardless of the power roll work as usual.
    flavor: Just one bad review will ruin their day.
    keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
    level: "1"
    name: Harsh Critic
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/harsh-critic
    target: One creature or object
    tier1: 7 + P sonic damage
    tier2: 10 + P sonic damage
    tier3: 13 + P sonic damage
    type: ability
name: Harsh Critic
target: One creature or object
type: feature
usage: Main action
```
