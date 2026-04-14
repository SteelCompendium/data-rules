---
action_type: Main action
class: conduit
distance: Ranged 10
feature_type: ability
file_basename: wither
file_dpath: feature/ability/conduit/level-1
flavor: A bolt of holy energy saps the life from a foe.
item_id: wither
item_name: Wither
keywords:
    - Magic
    - Ranged
    - Strike
level: "1"
name: Wither
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/wither
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + I corruption damage; P < WEAK, the target takes a bane on their next power roll
tier2: 5 + I corruption damage; P < AVERAGE, the target takes a bane on their next power roll
tier3: 8 + I corruption damage; P < STRONG, the target takes a bane on their next power roll
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - roll: Power Roll + Intuition
      tier1: 3 + I corruption damage; P < WEAK, the target takes a bane on their next power roll
      tier2: 5 + I corruption damage; P < AVERAGE, the target takes a bane on their next power roll
      tier3: 8 + I corruption damage; P < STRONG, the target takes a bane on their next power roll
feature_type: ability
flavor: A bolt of holy energy saps the life from a foe.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    distance: Ranged 10
    flavor: A bolt of holy energy saps the life from a foe.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "1"
    name: Wither
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/wither
    subtype: signature
    target: One creature or object
    tier1: 3 + I corruption damage; P < WEAK, the target takes a bane on their next power roll
    tier2: 5 + I corruption damage; P < AVERAGE, the target takes a bane on their next power roll
    tier3: 8 + I corruption damage; P < STRONG, the target takes a bane on their next power roll
    type: ability
name: Wither
target: One creature or object
type: feature
usage: Main action
```
