---
action_type: Main action
class: "null"
distance: Melee 1
feature_type: ability
file_basename: pressure-points
file_dpath: feature/ability/null/level-1
flavor: You strike at key nerve clusters to leave your foe staggered.
item_id: pressure-points
item_name: Pressure Points
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
level: "1"
name: Pressure Points
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.null.level-1/pressure-points
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 4 + A damage; A < WEAK, weakened (save ends)
tier2: 7 + A damage; A < AVERAGE, weakened (save ends)
tier3: 9 + A damage; A < STRONG, weakened (save ends)
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - roll: Power Roll + Agility
      tier1: 4 + A damage; A < WEAK, weakened (save ends)
      tier2: 7 + A damage; A < AVERAGE, weakened (save ends)
      tier3: 9 + A damage; A < STRONG, weakened (save ends)
feature_type: ability
flavor: You strike at key nerve clusters to leave your foe staggered.
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: Melee 1
    flavor: You strike at key nerve clusters to leave your foe staggered.
    keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
    level: "1"
    name: Pressure Points
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.null.level-1/pressure-points
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage; A < WEAK, weakened (save ends)
    tier2: 7 + A damage; A < AVERAGE, weakened (save ends)
    tier3: 9 + A damage; A < STRONG, weakened (save ends)
    type: ability
name: Pressure Points
target: One creature or object
type: feature
usage: Main action
```
