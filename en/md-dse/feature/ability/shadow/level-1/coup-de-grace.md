---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: coup-de-grace
file_dpath: feature/ability/shadow/level-1
flavor: Your blade might be the last thing they see.
item_id: coup-de-grace
item_name: Coup de Grace
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "1"
name: Coup de Grace
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/coup-de-grace
source: mcdm.heroes.v1
target: One creature
tier1: 2d6 + 7 + A damage
tier2: 2d6 + 11 + A damage
tier3: 2d6 + 16 + A damage
type: ability
---

```ds-feature
cost: 5 Insight
distance: Melee 1 or ranged 5
effects:
    - roll: Power Roll + Agility
      tier1: 2d6 + 7 + A damage
      tier2: 2d6 + 11 + A damage
      tier3: 2d6 + 16 + A damage
feature_type: ability
flavor: Your blade might be the last thing they see.
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 5 Insight
    distance: Melee 1 or ranged 5
    flavor: Your blade might be the last thing they see.
    keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "1"
    name: Coup de Grace
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/coup-de-grace
    target: One creature
    tier1: 2d6 + 7 + A damage
    tier2: 2d6 + 11 + A damage
    tier3: 2d6 + 16 + A damage
    type: ability
name: Coup de Grace
target: One creature
type: feature
usage: Main action
```
