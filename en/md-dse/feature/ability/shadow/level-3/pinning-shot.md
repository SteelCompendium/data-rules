---
action_type: Main action
class: shadow
cost: 7 Insight
cost_amount: "7"
cost_resource: Insight
distance: Ranged 5
feature_type: ability
file_basename: pinning-shot
file_dpath: feature/ability/shadow/level-3
flavor: One missile—placed well and placed hard.
item_id: pinning-shot
item_name: Pinning Shot
keywords:
    - Ranged
    - Strike
    - Weapon
level: "3"
name: Pinning Shot
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-3/pinning-shot
source: mcdm.heroes.v1
target: One creature
tier1: 8 + A damage; A < WEAK, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
tier2: 12 + A damage; A < AVERAGE, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
tier3: 16 + A damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---

```ds-feature
cost: 7 Insight
distance: Ranged 5
effects:
    - roll: Power Roll + Agility
      tier1: 8 + A damage; A < WEAK, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
      tier2: 12 + A damage; A < AVERAGE, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
      tier3: 16 + A damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
feature_type: ability
flavor: One missile—placed well and placed hard.
keywords:
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 7 Insight
    distance: Ranged 5
    flavor: One missile—placed well and placed hard.
    keywords:
        - Ranged
        - Strike
        - Weapon
    level: "3"
    name: Pinning Shot
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-3/pinning-shot
    target: One creature
    tier1: 8 + A damage; A < WEAK, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
    tier2: 12 + A damage; A < AVERAGE, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
    tier3: 16 + A damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
    type: ability
name: Pinning Shot
target: One creature
type: feature
usage: Main action
```
