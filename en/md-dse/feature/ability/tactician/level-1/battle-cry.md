---
action_type: Maneuver
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: Ranged 10
feature_type: ability
file_basename: battle-cry
file_dpath: feature/ability/tactician/level-1
flavor: You shout a phrase that galvanizes your team.
item_id: battle-cry
item_name: Battle Cry
keywords:
    - Ranged
level: "1"
name: Battle Cry
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/battle-cry
source: mcdm.heroes.v1
target: Three allies
tier1: Each target gains 1 surge.
tier2: Each target gains 2 surges.
tier3: Each target gains 3 surges.
type: ability
---

```ds-feature
cost: 3 Focus
distance: Ranged 10
effects:
    - roll: Power Roll + Reason
      tier1: Each target gains 1 surge.
      tier2: Each target gains 2 surges.
      tier3: Each target gains 3 surges.
feature_type: ability
flavor: You shout a phrase that galvanizes your team.
keywords:
    - Ranged
metadata:
    action_type: Maneuver
    class: tactician
    cost: 3 Focus
    distance: Ranged 10
    flavor: You shout a phrase that galvanizes your team.
    keywords:
        - Ranged
    level: "1"
    name: Battle Cry
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/battle-cry
    target: Three allies
    tier1: Each target gains 1 surge.
    tier2: Each target gains 2 surges.
    tier3: Each target gains 3 surges.
    type: ability
name: Battle Cry
target: Three allies
type: feature
usage: Maneuver
```
