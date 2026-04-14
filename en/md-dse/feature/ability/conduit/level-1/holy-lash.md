---
action_type: Main action
class: conduit
distance: Ranged 10
feature_type: ability
file_basename: holy-lash
file_dpath: feature/ability/conduit/level-1
flavor: A tendril of divine energy shoots forth to draw in your foe.
item_id: holy-lash
item_name: Holy Lash
keywords:
    - Magic
    - Ranged
    - Strike
level: "1"
name: Holy Lash
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/holy-lash
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + I holy damage; vertical pull 2
tier2: 5 + I holy damage; vertical pull 3
tier3: 8 + I holy damage; vertical pull 4
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - roll: Power Roll + Intuition
      tier1: 3 + I holy damage; vertical pull 2
      tier2: 5 + I holy damage; vertical pull 3
      tier3: 8 + I holy damage; vertical pull 4
feature_type: ability
flavor: A tendril of divine energy shoots forth to draw in your foe.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    distance: Ranged 10
    flavor: A tendril of divine energy shoots forth to draw in your foe.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "1"
    name: Holy Lash
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/holy-lash
    subtype: signature
    target: One creature or object
    tier1: 3 + I holy damage; vertical pull 2
    tier2: 5 + I holy damage; vertical pull 3
    tier3: 8 + I holy damage; vertical pull 4
    type: ability
name: Holy Lash
target: One creature or object
type: feature
usage: Main action
```
