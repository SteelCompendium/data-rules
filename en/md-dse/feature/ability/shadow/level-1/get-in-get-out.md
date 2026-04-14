---
action_type: Main action
class: shadow
cost: 3 Insight
cost_amount: "3"
cost_resource: Insight
distance: Melee 1
effect: You can shift up to your speed, dividing that movement before or after your strike as desired.
feature_type: ability
file_basename: get-in-get-out
file_dpath: feature/ability/shadow/level-1
flavor: Move unexpectedly, strike fast, and be gone!
item_id: get-in-get-out
item_name: Get In Get Out
keywords:
    - Melee
    - Strike
    - Weapon
level: "1"
name: Get In Get Out
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/get-in-get-out
source: mcdm.heroes.v1
target: One creature
tier1: 5 + A damage
tier2: 8 + A damage
tier3: 11 + A damage
type: ability
---

```ds-feature
cost: 3 Insight
distance: Melee 1
effects:
    - effect: You can shift up to your speed, dividing that movement before or after your strike as desired.
    - roll: Power Roll + Agility
      tier1: 5 + A damage
      tier2: 8 + A damage
      tier3: 11 + A damage
feature_type: ability
flavor: Move unexpectedly, strike fast, and be gone!
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 3 Insight
    distance: Melee 1
    effect: You can shift up to your speed, dividing that movement before or after your strike as desired.
    flavor: Move unexpectedly, strike fast, and be gone!
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Get In Get Out
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/get-in-get-out
    target: One creature
    tier1: 5 + A damage
    tier2: 8 + A damage
    tier3: 11 + A damage
    type: ability
name: Get In Get Out
target: One creature
type: feature
usage: Main action
```
