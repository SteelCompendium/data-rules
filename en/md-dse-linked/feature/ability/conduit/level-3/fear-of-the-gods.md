---
action_type: Main action
class: conduit
cost: 7 Piety
cost_amount: "7"
cost_resource: Piety
distance: 5 cube within 10
effect: Each target is frightened of you or a creature you choose within distance.
feature_type: ability
file_basename: fear-of-the-gods
file_dpath: feature/ability/conduit/level-3
flavor: Your divine magic makes a creature appear as what your enemies fear most.
item_id: fear-of-the-gods
item_name: Fear of the Gods
keywords:
    - Area
    - Magic
    - Ranged
level: "3"
name: Fear of the Gods
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-3/fear-of-the-gods
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 6 psychic damage; I < WEAK, frightened (save ends)
tier2: 9 psychic damage; I < AVERAGE, frightened (save ends)
tier3: 13 psychic damage; I < STRONG, frightened (save ends)
type: ability
---

```ds-feature
cost: 7 Piety
distance: 5 cube within 10
effects:
    - effect: Each target is frightened of you or a creature you choose within distance.
    - roll: Power Roll + Intuition
      tier1: 6 psychic damage; I < WEAK, frightened (save ends)
      tier2: 9 psychic damage; I < AVERAGE, frightened (save ends)
      tier3: 13 psychic damage; I < STRONG, frightened (save ends)
feature_type: ability
flavor: Your divine magic makes a creature appear as what your enemies fear most.
keywords:
    - Area
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: conduit
    cost: 7 Piety
    distance: 5 cube within 10
    effect: Each target is frightened of you or a creature you choose within distance.
    flavor: Your divine magic makes a creature appear as what your enemies fear most.
    keywords:
        - Area
        - Magic
        - Ranged
    level: "3"
    name: Fear of the Gods
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-3/fear-of-the-gods
    target: Each enemy in the area
    tier1: 6 psychic damage; I < WEAK, frightened (save ends)
    tier2: 9 psychic damage; I < AVERAGE, frightened (save ends)
    tier3: 13 psychic damage; I < STRONG, frightened (save ends)
    type: ability
name: Fear of the Gods
target: Each enemy in the area
type: feature
usage: Main action
```
