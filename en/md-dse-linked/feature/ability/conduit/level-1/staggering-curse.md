---
action_type: Main action
class: conduit
distance: Melee 1
feature_type: ability
file_basename: staggering-curse
file_dpath: feature/ability/conduit/level-1
flavor: A blast of judgment disorients your foe.
item_id: staggering-curse
item_name: Staggering Curse
keywords:
    - Magic
    - Melee
    - Strike
level: "1"
name: Staggering Curse
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/staggering-curse
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + I holy damage; slide 1
tier2: 5 + I holy damage; slide 2
tier3: 8 + I holy damage; slide 3
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - roll: Power Roll + Intuition
      tier1: 3 + I holy damage; slide 1
      tier2: 5 + I holy damage; slide 2
      tier3: 8 + I holy damage; slide 3
feature_type: ability
flavor: A blast of judgment disorients your foe.
keywords:
    - Magic
    - Melee
    - Strike
metadata:
    action_type: Main action
    class: conduit
    distance: Melee 1
    flavor: A blast of judgment disorients your foe.
    keywords:
        - Magic
        - Melee
        - Strike
    level: "1"
    name: Staggering Curse
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/staggering-curse
    subtype: signature
    target: One creature or object
    tier1: 3 + I holy damage; slide 1
    tier2: 5 + I holy damage; slide 2
    tier3: 8 + I holy damage; slide 3
    type: ability
name: Staggering Curse
target: One creature or object
type: feature
usage: Main action
```
