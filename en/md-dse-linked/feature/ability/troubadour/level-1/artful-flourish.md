---
action_type: Main action
class: troubadour
distance: Melee 1
effect: You can shift up to 3 squares.
feature_type: ability
file_basename: artful-flourish
file_dpath: feature/ability/troubadour/level-1
flavor: And they said practicing fencing was a waste!
item_id: artful-flourish
item_name: Artful Flourish
keywords:
    - Melee
    - Strike
    - Weapon
level: "1"
name: Artful Flourish
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/artful-flourish
source: mcdm.heroes.v1
spend: '2+ Drama: You can target one additional creature or object for every 2 drama spent.'
subtype: signature
target: Two creatures or objects
tier1: 2 damage
tier2: 5 damage
tier3: 7 damage
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You can shift up to 3 squares.
    - roll: Power Roll + Agility
      tier1: 2 damage
      tier2: 5 damage
      tier3: 7 damage
    - effect: '2+ Drama: You can target one additional creature or object for every 2 drama spent.'
      name: Spend
feature_type: ability
flavor: And they said practicing fencing was a waste!
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    distance: Melee 1
    effect: You can shift up to 3 squares.
    flavor: And they said practicing fencing was a waste!
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Artful Flourish
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/artful-flourish
    spend: '2+ Drama: You can target one additional creature or object for every 2 drama spent.'
    subtype: signature
    target: Two creatures or objects
    tier1: 2 damage
    tier2: 5 damage
    tier3: 7 damage
    type: ability
name: Artful Flourish
target: Two creatures or objects
type: feature
usage: Main action
```
