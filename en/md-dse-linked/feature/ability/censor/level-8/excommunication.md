---
action_type: Main action
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: Melee 1
effect: At the end of each of your turns, a target [weakened](../../../../condition/weakened.md) this way deals holy damage equal to twice your Presence score to each enemy within 2 squares of them. Additionally, a target [weakened](../../../../condition/weakened.md) this way can't be targeted by their allies' abilities.
feature_type: ability
file_basename: excommunication
file_dpath: feature/ability/censor/level-8
flavor: You curse your foe to become a bane to their allies.
item_id: excommunication
item_name: Excommunication
keywords:
    - Melee
    - Strike
    - Weapon
level: "8"
name: Excommunication
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.censor.level-8/excommunication
source: mcdm.heroes.v1
target: One creature
tier1: 9 + M damage; I < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
tier2: 13 + M damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
tier3: 18 + M damage; I < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Wrath
distance: Melee 1
effects:
    - effect: At the end of each of your turns, a target [weakened](../../../../condition/weakened.md) this way deals holy damage equal to twice your Presence score to each enemy within 2 squares of them. Additionally, a target [weakened](../../../../condition/weakened.md) this way can't be targeted by their allies' abilities.
    - roll: Power Roll + Might
      tier1: 9 + M damage; I < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 13 + M damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 18 + M damage; I < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
feature_type: ability
flavor: You curse your foe to become a bane to their allies.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 11 Wrath
    distance: Melee 1
    effect: At the end of each of your turns, a target [weakened](../../../../condition/weakened.md) this way deals holy damage equal to twice your Presence score to each enemy within 2 squares of them. Additionally, a target [weakened](../../../../condition/weakened.md) this way can't be targeted by their allies' abilities.
    flavor: You curse your foe to become a bane to their allies.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "8"
    name: Excommunication
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.censor.level-8/excommunication
    target: One creature
    tier1: 9 + M damage; I < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
    tier2: 13 + M damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 18 + M damage; I < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
    type: ability
name: Excommunication
target: One creature
type: feature
usage: Main action
```
