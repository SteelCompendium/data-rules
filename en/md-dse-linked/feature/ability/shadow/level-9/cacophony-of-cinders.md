---
action_type: Main action
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: Self; see below
effect: You shift up to twice your speed, making one power roll that targets each creature you come adjacent to during the shift.
feature_type: ability
file_basename: cacophony-of-cinders
file_dpath: feature/ability/shadow/level-9
flavor: You tumble through the battle, stabbing foes and teleporting allies.
item_id: cacophony-of-cinders
item_name: Cacophony of Cinders
keywords:
    - Magic
    - Melee
    - Weapon
level: "9"
name: Cacophony of Cinders
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-9/cacophony-of-cinders
source: mcdm.heroes.v1
target: Self
tier1: An enemy takes 6 damage; an ally can teleport up to 3 squares.
tier2: An enemy takes 10 damage; an ally can teleport up to 5 squares.
tier3: An enemy takes 14 damage; an ally can teleport up to 7 squares.
type: ability
---

```ds-feature
cost: 11 Insight
distance: Self; see below
effects:
    - effect: You shift up to twice your speed, making one power roll that targets each creature you come adjacent to during the shift.
    - roll: Power Roll + Agility
      tier1: An enemy takes 6 damage; an ally can teleport up to 3 squares.
      tier2: An enemy takes 10 damage; an ally can teleport up to 5 squares.
      tier3: An enemy takes 14 damage; an ally can teleport up to 7 squares.
feature_type: ability
flavor: You tumble through the battle, stabbing foes and teleporting allies.
keywords:
    - Magic
    - Melee
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 11 Insight
    distance: Self; see below
    effect: You shift up to twice your speed, making one power roll that targets each creature you come adjacent to during the shift.
    flavor: You tumble through the battle, stabbing foes and teleporting allies.
    keywords:
        - Magic
        - Melee
        - Weapon
    level: "9"
    name: Cacophony of Cinders
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-9/cacophony-of-cinders
    target: Self
    tier1: An enemy takes 6 damage; an ally can teleport up to 3 squares.
    tier2: An enemy takes 10 damage; an ally can teleport up to 5 squares.
    tier3: An enemy takes 14 damage; an ally can teleport up to 7 squares.
    type: ability
name: Cacophony of Cinders
target: Self
type: feature
usage: Main action
```
