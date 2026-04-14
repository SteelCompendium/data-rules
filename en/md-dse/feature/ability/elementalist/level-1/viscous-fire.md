---
action_type: Main action
class: elementalist
distance: Ranged 10
feature_type: ability
file_basename: viscous-fire
file_dpath: feature/ability/elementalist/level-1
flavor: A jet of heavy fire erupts where you strike.
item_id: viscous-fire
item_name: Viscous Fire
keywords:
    - Fire
    - Magic
    - Ranged
    - Strike
level: "1"
name: Viscous Fire
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/viscous-fire
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 2 + R fire damage; push 2
tier2: 5 + R fire damage; push 3
tier3: 7 + R fire damage; push 4
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - roll: Power Roll + Reason
      tier1: 2 + R fire damage; push 2
      tier2: 5 + R fire damage; push 3
      tier3: 7 + R fire damage; push 4
feature_type: ability
flavor: A jet of heavy fire erupts where you strike.
keywords:
    - Fire
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: elementalist
    distance: Ranged 10
    flavor: A jet of heavy fire erupts where you strike.
    keywords:
        - Fire
        - Magic
        - Ranged
        - Strike
    level: "1"
    name: Viscous Fire
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/viscous-fire
    subtype: signature
    target: One creature or object
    tier1: 2 + R fire damage; push 2
    tier2: 5 + R fire damage; push 3
    tier3: 7 + R fire damage; push 4
    type: ability
name: Viscous Fire
target: One creature or object
type: feature
usage: Main action
```
