---
action_type: Main action
class: tactician
cost: 11 Focus
cost_amount: "11"
cost_resource: Focus
distance: Melee 1 or ranged 5
effect: One ally within 10 squares of you can use a heroic ability against the target as a free triggered action without spending any of their [Heroic Resource](../../../../rule/resource/heroic-resource.md), as long as they have enough [Heroic Resource](../../../../rule/resource/heroic-resource.md) to pay for the ability. If the target is reduced to 0 [Stamina](../../../../rule/health/stamina.md) before the chosen ally has used their ability, the ally can pick a different target.
feature_type: ability
file_basename: ill-open-and-youll-close
file_dpath: feature/ability/tactician/level-8
flavor: You create an opening for an ally.
item_id: ill-open-and-youll-close
item_name: I'll Open and You'll Close
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "8"
name: I'll Open and You'll Close
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.tactician.level-8/ill-open-and-youll-close
source: mcdm.heroes.v1
target: One creature
tier1: 6 + M damage
tier2: 10 + M damage
tier3: 14 + M damage
type: ability
---

```ds-feature
cost: 11 Focus
distance: Melee 1 or ranged 5
effects:
    - effect: One ally within 10 squares of you can use a heroic ability against the target as a free triggered action without spending any of their [Heroic Resource](../../../../rule/resource/heroic-resource.md), as long as they have enough [Heroic Resource](../../../../rule/resource/heroic-resource.md) to pay for the ability. If the target is reduced to 0 [Stamina](../../../../rule/health/stamina.md) before the chosen ally has used their ability, the ally can pick a different target.
    - roll: Power Roll + Might
      tier1: 6 + M damage
      tier2: 10 + M damage
      tier3: 14 + M damage
feature_type: ability
flavor: You create an opening for an ally.
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 11 Focus
    distance: Melee 1 or ranged 5
    effect: One ally within 10 squares of you can use a heroic ability against the target as a free triggered action without spending any of their [Heroic Resource](../../../../rule/resource/heroic-resource.md), as long as they have enough [Heroic Resource](../../../../rule/resource/heroic-resource.md) to pay for the ability. If the target is reduced to 0 [Stamina](../../../../rule/health/stamina.md) before the chosen ally has used their ability, the ally can pick a different target.
    flavor: You create an opening for an ally.
    keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "8"
    name: I'll Open and You'll Close
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.tactician.level-8/ill-open-and-youll-close
    target: One creature
    tier1: 6 + M damage
    tier2: 10 + M damage
    tier3: 14 + M damage
    type: ability
name: I'll Open and You'll Close
target: One creature
type: feature
usage: Main action
```
