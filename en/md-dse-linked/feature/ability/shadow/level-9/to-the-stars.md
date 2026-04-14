---
action_type: Main action
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: Melee 1 or ranged 10
effect: The ground beneath a 3-cube area around the target's starting position is difficult terrain.
feature_type: ability
file_basename: to-the-stars
file_dpath: feature/ability/shadow/level-9
flavor: You attach your most potent explosive to your foe. Under less pressing circumstances, you're sure you could launch them into orbit.
item_id: to-the-stars
item_name: To the Stars
keywords:
    - Melee
    - Ranged
    - Strike
level: "9"
name: To the Stars
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-9/to-the-stars
source: mcdm.heroes.v1
target: One creature or object
tier1: 4 + A fire damage; vertical push 8
tier2: 7 + A fire damage; vertical push 10
tier3: 11 + A fire damage; vertical push 15
type: ability
---

```ds-feature
cost: 11 Insight
distance: Melee 1 or ranged 10
effects:
    - effect: The ground beneath a 3-cube area around the target's starting position is difficult terrain.
    - roll: Power Roll + Agility
      tier1: 4 + A fire damage; vertical push 8
      tier2: 7 + A fire damage; vertical push 10
      tier3: 11 + A fire damage; vertical push 15
feature_type: ability
flavor: You attach your most potent explosive to your foe. Under less pressing circumstances, you're sure you could launch them into orbit.
keywords:
    - Melee
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: shadow
    cost: 11 Insight
    distance: Melee 1 or ranged 10
    effect: The ground beneath a 3-cube area around the target's starting position is difficult terrain.
    flavor: You attach your most potent explosive to your foe. Under less pressing circumstances, you're sure you could launch them into orbit.
    keywords:
        - Melee
        - Ranged
        - Strike
    level: "9"
    name: To the Stars
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-9/to-the-stars
    target: One creature or object
    tier1: 4 + A fire damage; vertical push 8
    tier2: 7 + A fire damage; vertical push 10
    tier3: 11 + A fire damage; vertical push 15
    type: ability
name: To the Stars
target: One creature or object
type: feature
usage: Main action
```
