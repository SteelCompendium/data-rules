---
action_type: Main action
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Melee 1
feature_type: ability
file_basename: to-the-uttermost-end
file_dpath: feature/ability/fury/level-1
flavor: You gut your life force to ensure a foe's demise.
item_id: to-the-uttermost-end
item_name: To the Uttermost End
keywords:
    - Melee
    - Strike
    - Weapon
level: "1"
name: To the Uttermost End
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-1/to-the-uttermost-end
source: mcdm.heroes.v1
spend: '1+ Ferocity: While you are winded, this ability deals an extra 1d6 damage for each ferocity spent. While you are dying, it deals an extra 1d10 damage for each ferocity spent. In either case, you lose 1d6 Stamina after making this strike.'
target: One creature
tier1: 7 + M damage
tier2: 11 + M damage
tier3: 16 + M damage
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 7 + M damage
      tier2: 11 + M damage
      tier3: 16 + M damage
    - effect: '1+ Ferocity: While you are winded, this ability deals an extra 1d6 damage for each ferocity spent. While you are dying, it deals an extra 1d10 damage for each ferocity spent. In either case, you lose 1d6 Stamina after making this strike.'
      name: Spend
feature_type: ability
flavor: You gut your life force to ensure a foe's demise.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 5 Ferocity
    distance: Melee 1
    flavor: You gut your life force to ensure a foe's demise.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: To the Uttermost End
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/to-the-uttermost-end
    spend: '1+ Ferocity: While you are winded, this ability deals an extra 1d6 damage for each ferocity spent. While you are dying, it deals an extra 1d10 damage for each ferocity spent. In either case, you lose 1d6 Stamina after making this strike.'
    target: One creature
    tier1: 7 + M damage
    tier2: 11 + M damage
    tier3: 16 + M damage
    type: ability
name: To the Uttermost End
target: One creature
type: feature
usage: Main action
```
