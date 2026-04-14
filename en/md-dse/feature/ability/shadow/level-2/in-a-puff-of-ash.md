---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: in-a-puff-of-ash
file_dpath: feature/ability/shadow/level-2
flavor: You enchant a strike with your teleportation magic.
item_id: in-a-puff-of-ash
item_name: In a Puff of Ash
keywords:
    - Magic
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "2"
name: In a Puff of Ash
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-2/in-a-puff-of-ash
source: mcdm.heroes.v1
target: One creature
tier1: 6 + A damage; you can teleport the target 1 square
tier2: 10 + A damage; you can teleport the target up to 3 squares
tier3: 14 + A damage; you can teleport the target up to 5 squares
type: ability
---

```ds-feature
cost: 5 Insight
distance: Melee 1 or ranged 5
effects:
    - roll: Power Roll + Agility
      tier1: 6 + A damage; you can teleport the target 1 square
      tier2: 10 + A damage; you can teleport the target up to 3 squares
      tier3: 14 + A damage; you can teleport the target up to 5 squares
feature_type: ability
flavor: You enchant a strike with your teleportation magic.
keywords:
    - Magic
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 5 Insight
    distance: Melee 1 or ranged 5
    flavor: You enchant a strike with your teleportation magic.
    keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "2"
    name: In a Puff of Ash
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-2/in-a-puff-of-ash
    target: One creature
    tier1: 6 + A damage; you can teleport the target 1 square
    tier2: 10 + A damage; you can teleport the target up to 3 squares
    tier3: 14 + A damage; you can teleport the target up to 5 squares
    type: ability
name: In a Puff of Ash
target: One creature
type: feature
usage: Main action
```
