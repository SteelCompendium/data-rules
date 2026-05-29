---
action_type: Main action
class: censor
cost: 3 Wrath
cost_amount: "3"
cost_resource: Wrath
distance: Ranged 10
feature_type: ability
file_basename: repent
file_dpath: feature/ability/censor/level-1
flavor: You conjure memories of their sins to harry your foes.
item_id: repent
item_name: Repent!
keywords:
    - Magic
    - Ranged
    - Strike
level: "1"
name: Repent!
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.censor.level-1/repent
source: mcdm.heroes.v1
target: One creature
tier1: 5 + P holy damage; I < WEAK, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: 8 + P holy damage; I < AVERAGE, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: 11 + P holy damage; I < STRONG, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---

```ds-feature
cost: 3 Wrath
distance: Ranged 10
effects:
    - roll: Power Roll + Presence
      tier1: 5 + P holy damage; I < WEAK, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 8 + P holy damage; I < AVERAGE, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 11 + P holy damage; I < STRONG, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
feature_type: ability
flavor: You conjure memories of their sins to harry your foes.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: censor
    cost: 3 Wrath
    distance: Ranged 10
    flavor: You conjure memories of their sins to harry your foes.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "1"
    name: Repent!
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/repent
    target: One creature
    tier1: 5 + P holy damage; I < WEAK, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
    tier2: 8 + P holy damage; I < AVERAGE, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
    tier3: 11 + P holy damage; I < STRONG, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
    type: ability
name: Repent!
target: One creature
type: feature
usage: Main action
```
