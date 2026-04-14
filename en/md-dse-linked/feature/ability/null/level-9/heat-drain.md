---
action_type: Maneuver
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: Melee 1
effect: While restrained this way, the target takes cold damage equal to your Intuition score at the start of each of your turns. Additionally, whenever the target damages another creature while restrained this way, any potency associated with the damage is reduced by 2.
feature_type: ability
file_basename: heat-drain
file_dpath: feature/ability/null/level-9
flavor: You drain all the heat from the target.
item_id: heat-drain
item_name: Heat Drain
keywords:
    - Melee
    - Psionic
    - Strike
level: "9"
name: Heat Drain
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.null.level-9/heat-drain
source: mcdm.heroes.v1
target: One creature
tier1: 8 + I cold damage; M < WEAK, restrained (save ends)
tier2: 11 + I cold damage; M < AVERAGE, restrained (save ends)
tier3: 15 + I cold damage; M < STRONG, restrained (save ends)
type: ability
---

```ds-feature
cost: 11 Discipline
distance: Melee 1
effects:
    - effect: While restrained this way, the target takes cold damage equal to your Intuition score at the start of each of your turns. Additionally, whenever the target damages another creature while restrained this way, any potency associated with the damage is reduced by 2.
    - roll: Power Roll + Intuition
      tier1: 8 + I cold damage; M < WEAK, restrained (save ends)
      tier2: 11 + I cold damage; M < AVERAGE, restrained (save ends)
      tier3: 15 + I cold damage; M < STRONG, restrained (save ends)
feature_type: ability
flavor: You drain all the heat from the target.
keywords:
    - Melee
    - Psionic
    - Strike
metadata:
    action_type: Maneuver
    class: "null"
    cost: 11 Discipline
    distance: Melee 1
    effect: While restrained this way, the target takes cold damage equal to your Intuition score at the start of each of your turns. Additionally, whenever the target damages another creature while restrained this way, any potency associated with the damage is reduced by 2.
    flavor: You drain all the heat from the target.
    keywords:
        - Melee
        - Psionic
        - Strike
    level: "9"
    name: Heat Drain
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.null.level-9/heat-drain
    target: One creature
    tier1: 8 + I cold damage; M < WEAK, restrained (save ends)
    tier2: 11 + I cold damage; M < AVERAGE, restrained (save ends)
    tier3: 15 + I cold damage; M < STRONG, restrained (save ends)
    type: ability
name: Heat Drain
target: One creature
type: feature
usage: Maneuver
```
