---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: Melee 1
effect: When a target who is not a leader or solo creature is made winded by this ability, they are reduced to 0 Stamina.
feature_type: ability
file_basename: censored
file_dpath: feature/ability/censor/level-1
flavor: Judged and sentenced.
item_id: censored
item_name: Censored
keywords:
    - Melee
    - Strike
    - Weapon
level: "1"
name: Censored
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.censor.level-1/censored
source: mcdm.heroes.v1
target: One creature
tier1: 2 + M holy damage
tier2: 3 + M holy damage
tier3: 5 + M holy damage
type: ability
---

```ds-feature
cost: 5 Wrath
distance: Melee 1
effects:
    - effect: When a target who is not a leader or solo creature is made winded by this ability, they are reduced to 0 Stamina.
    - roll: Power Roll + Might
      tier1: 2 + M holy damage
      tier2: 3 + M holy damage
      tier3: 5 + M holy damage
feature_type: ability
flavor: Judged and sentenced.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 5 Wrath
    distance: Melee 1
    effect: When a target who is not a leader or solo creature is made winded by this ability, they are reduced to 0 Stamina.
    flavor: Judged and sentenced.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Censored
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/censored
    target: One creature
    tier1: 2 + M holy damage
    tier2: 3 + M holy damage
    tier3: 5 + M holy damage
    type: ability
name: Censored
target: One creature
type: feature
usage: Main action
```
