---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Melee 1
effect: You shift up to your speed.
feature_type: ability
file_basename: seek-and-destroy
file_dpath: feature/ability/fury/level-6
flavor: You break through the enemy lines to make an example.
item_id: seek-and-destroy
item_name: Seek and Destroy
keywords:
    - Melee
    - Strike
    - Weapon
level: "6"
name: Seek and Destroy
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-6/seek-and-destroy
source: mcdm.heroes.v1
target: One creature
tier1: 4 + M damage; P < WEAK, frightened (save ends)
tier2: 6 + M damage; P < AVERAGE, frightened (save ends)
tier3: 10 + M damage; P < STRONG, frightened (save ends)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Melee 1
effects:
    - effect: You shift up to your speed.
    - roll: Power Roll + Might
      tier1: 4 + M damage; P < WEAK, frightened (save ends)
      tier2: 6 + M damage; P < AVERAGE, frightened (save ends)
      tier3: 10 + M damage; P < STRONG, frightened (save ends)
feature_type: ability
flavor: You break through the enemy lines to make an example.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 9 Ferocity
    distance: Melee 1
    effect: You shift up to your speed.
    flavor: You break through the enemy lines to make an example.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "6"
    name: Seek and Destroy
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-6/seek-and-destroy
    target: One creature
    tier1: 4 + M damage; P < WEAK, frightened (save ends)
    tier2: 6 + M damage; P < AVERAGE, frightened (save ends)
    tier3: 10 + M damage; P < STRONG, frightened (save ends)
    type: ability
name: Seek and Destroy
target: One creature
type: feature
usage: Main action
```
