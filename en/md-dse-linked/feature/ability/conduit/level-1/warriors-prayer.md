---
action_type: Main action
class: conduit
distance: Ranged 10
effect: You or one ally within distance gains [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to your Intuition score.
feature_type: ability
file_basename: warriors-prayer
file_dpath: feature/ability/conduit/level-1
flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in melee.
item_id: warriors-prayer
item_name: Warrior's Prayer
keywords:
    - Magic
    - Ranged
    - Strike
level: "1"
name: Warrior's Prayer
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/warriors-prayer
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + I holy damage
tier2: 6 + I holy damage
tier3: 9 + I holy damage
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: You or one ally within distance gains [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to your Intuition score.
    - roll: Power Roll + Intuition
      tier1: 3 + I holy damage
      tier2: 6 + I holy damage
      tier3: 9 + I holy damage
feature_type: ability
flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in melee.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    distance: Ranged 10
    effect: You or one ally within distance gains [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to your Intuition score.
    flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in melee.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "1"
    name: Warrior's Prayer
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/warriors-prayer
    subtype: signature
    target: One creature
    tier1: 3 + I holy damage
    tier2: 6 + I holy damage
    tier3: 9 + I holy damage
    type: ability
name: Warrior's Prayer
target: One creature
type: feature
usage: Main action
```
