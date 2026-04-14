---
action_type: Main action
class: troubadour
cost: 7 Drama
cost_amount: "7"
cost_resource: Drama
distance: 3 burst
effect: Each ally in the area can shift up to 2 squares.
feature_type: ability
file_basename: infernal-gavotte
file_dpath: feature/ability/troubadour/level-3
flavor: A spicy performance lights a fire under your allies' feet.
item_id: infernal-gavotte
item_name: Infernal Gavotte
keywords:
    - Area
    - Magic
    - Melee
    - Weapon
level: "3"
name: Infernal Gavotte
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/infernal-gavotte
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 5 fire damage; A < WEAK, weakened (save ends)
tier2: 7 fire damage; A < AVERAGE, weakened (save ends)
tier3: 10 fire damage; A < STRONG, weakened (save ends)
type: ability
---

```ds-feature
cost: 7 Drama
distance: 3 burst
effects:
    - effect: Each ally in the area can shift up to 2 squares.
    - roll: Power Roll + Presence
      tier1: 5 fire damage; A < WEAK, weakened (save ends)
      tier2: 7 fire damage; A < AVERAGE, weakened (save ends)
      tier3: 10 fire damage; A < STRONG, weakened (save ends)
feature_type: ability
flavor: A spicy performance lights a fire under your allies' feet.
keywords:
    - Area
    - Magic
    - Melee
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 7 Drama
    distance: 3 burst
    effect: Each ally in the area can shift up to 2 squares.
    flavor: A spicy performance lights a fire under your allies' feet.
    keywords:
        - Area
        - Magic
        - Melee
        - Weapon
    level: "3"
    name: Infernal Gavotte
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/infernal-gavotte
    target: Each enemy in the area
    tier1: 5 fire damage; A < WEAK, weakened (save ends)
    tier2: 7 fire damage; A < AVERAGE, weakened (save ends)
    tier3: 10 fire damage; A < STRONG, weakened (save ends)
    type: ability
name: Infernal Gavotte
target: Each enemy in the area
type: feature
usage: Main action
```
