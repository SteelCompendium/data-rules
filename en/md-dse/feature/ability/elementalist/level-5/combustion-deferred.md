---
action_type: Main action
class: elementalist
cost: 9 Essence
cost_amount: "9"
cost_resource: Essence
distance: Ranged 10
effect: When the target ends their next turn, or if they drop to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) before then, each enemy adjacent to them takes fire damage equal to twice your Reason score. Each affected enemy then gains this same effect.
feature_type: ability
file_basename: combustion-deferred
file_dpath: feature/ability/elementalist/level-5
flavor: Your flames dance from kindling to kindling to kindling.
item_id: combustion-deferred
item_name: Combustion Deferred
keywords:
    - Fire
    - Magic
    - Ranged
    - Strike
level: "5"
name: Combustion Deferred
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.elementalist.level-5/combustion-deferred
source: mcdm.heroes.v1
target: One creature or object
tier1: 8 + R fire damage
tier2: 13 + R fire damage
tier3: 17 + R fire damage
type: ability
---

```ds-feature
cost: 9 Essence
distance: Ranged 10
effects:
    - effect: When the target ends their next turn, or if they drop to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) before then, each enemy adjacent to them takes fire damage equal to twice your Reason score. Each affected enemy then gains this same effect.
    - roll: Power Roll + Reason
      tier1: 8 + R fire damage
      tier2: 13 + R fire damage
      tier3: 17 + R fire damage
feature_type: ability
flavor: Your flames dance from kindling to kindling to kindling.
keywords:
    - Fire
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: elementalist
    cost: 9 Essence
    distance: Ranged 10
    effect: When the target ends their next turn, or if they drop to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) before then, each enemy adjacent to them takes fire damage equal to twice your Reason score. Each affected enemy then gains this same effect.
    flavor: Your flames dance from kindling to kindling to kindling.
    keywords:
        - Fire
        - Magic
        - Ranged
        - Strike
    level: "5"
    name: Combustion Deferred
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-5/combustion-deferred
    target: One creature or object
    tier1: 8 + R fire damage
    tier2: 13 + R fire damage
    tier3: 17 + R fire damage
    type: ability
name: Combustion Deferred
target: One creature or object
type: feature
usage: Main action
```
