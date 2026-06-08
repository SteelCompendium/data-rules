---
action_type: Main action
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: Melee 1
effect: Until the end of the encounter or until you are [dying](scc:mcdm.heroes.v1/rule.health/dying), the target has damage weakness 10.
feature_type: ability
file_basename: apostate
file_dpath: feature/ability/censor/level-9
flavor: You channel holy energy to seal an enemy's fate.
item_id: apostate
item_name: Apostate
keywords:
    - Melee
    - Strike
    - Weapon
level: "9"
name: Apostate
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.censor.level-9/apostate
source: mcdm.heroes.v1
target: One creature
tier1: 13 + M holy damage
tier2: 19 + M holy damage
tier3: 26 + M holy damage
type: ability
---

```ds-feature
cost: 11 Wrath
distance: Melee 1
effects:
    - effect: Until the end of the encounter or until you are [dying](scc:mcdm.heroes.v1/rule.health/dying), the target has damage weakness 10.
    - roll: Power Roll + Might
      tier1: 13 + M holy damage
      tier2: 19 + M holy damage
      tier3: 26 + M holy damage
feature_type: ability
flavor: You channel holy energy to seal an enemy's fate.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 11 Wrath
    distance: Melee 1
    effect: Until the end of the encounter or until you are [dying](scc:mcdm.heroes.v1/rule.health/dying), the target has damage weakness 10.
    flavor: You channel holy energy to seal an enemy's fate.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "9"
    name: Apostate
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.censor.level-9/apostate
    target: One creature
    tier1: 13 + M holy damage
    tier2: 19 + M holy damage
    tier3: 26 + M holy damage
    type: ability
name: Apostate
target: One creature
type: feature
usage: Main action
```
