---
action_type: Main action
class: fury
distance: Melee 1
feature_type: ability
file_basename: brutal-slam
file_dpath: feature/ability/fury/level-1
flavor: The heavy impact of your weapon attacks drives your foes ever back.
item_id: brutal-slam
item_name: Brutal Slam
keywords:
    - Melee
    - Strike
    - Weapon
level: "1"
name: Brutal Slam
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-1/brutal-slam
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + M damage; push 1
tier2: 6 + M damage; push 2
tier3: 9 + M damage; push 4
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 3 + M damage; push 1
      tier2: 6 + M damage; push 2
      tier3: 9 + M damage; push 4
feature_type: ability
flavor: The heavy impact of your weapon attacks drives your foes ever back.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: fury
    distance: Melee 1
    flavor: The heavy impact of your weapon attacks drives your foes ever back.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Brutal Slam
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/brutal-slam
    subtype: signature
    target: One creature or object
    tier1: 3 + M damage; push 1
    tier2: 6 + M damage; push 2
    tier3: 9 + M damage; push 4
    type: ability
name: Brutal Slam
target: One creature or object
type: feature
usage: Main action
```
