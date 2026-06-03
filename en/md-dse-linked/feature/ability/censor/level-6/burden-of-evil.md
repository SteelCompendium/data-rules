---
action_type: Maneuver
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: Ranged 10
feature_type: ability
file_basename: burden-of-evil
file_dpath: feature/ability/censor/level-6
flavor: You reveal a vision of your enemies' fate that causes them to scramble as it staggers them.
item_id: burden-of-evil
item_name: Burden of Evil
keywords:
    - Magic
    - Ranged
    - Strike
level: "6"
name: Burden of Evil
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.censor.level-6/burden-of-evil
source: mcdm.heroes.v1
target: Three enemies
tier1: Slide 3; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
tier2: Slide 5; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
tier3: Slide 7; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 9 Wrath
distance: Ranged 10
effects:
    - roll: Power Roll + Presence
      tier1: Slide 3; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: Slide 5; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: Slide 7; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: You reveal a vision of your enemies' fate that causes them to scramble as it staggers them.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Maneuver
    class: censor
    cost: 9 Wrath
    distance: Ranged 10
    flavor: You reveal a vision of your enemies' fate that causes them to scramble as it staggers them.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "6"
    name: Burden of Evil
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.censor.level-6/burden-of-evil
    target: Three enemies
    tier1: Slide 3; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
    tier2: Slide 5; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
    tier3: Slide 7; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Burden of Evil
target: Three enemies
type: feature
usage: Maneuver
```
