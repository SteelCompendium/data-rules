---
action_type: Main action
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: Melee 1
effect: This ability gains an edge against demons, [devils](../../../../ancestry/devil.md), undead, and creatures not native to your current world. If you know the target's true name, this ability has a double edge. While banished, the target is sent to another manifold in the timescape and removed from the encounter map. A banished target can do nothing but make saving throws, and takes 10 holy damage each time they do so. If the target is reduced to 0 Stamina while banished, they are lost to the timescape.
feature_type: ability
file_basename: banish
file_dpath: feature/ability/censor/level-9
flavor: You sever the target's tenuous connection to the world.
item_id: banish
item_name: Banish
keywords:
    - Melee
    - Strike
    - Weapon
level: "9"
name: Banish
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.censor.level-9/banish
source: mcdm.heroes.v1
target: One creature
tier1: 5 + M damage; P < WEAK, the target is banished (save ends)
tier2: 8 + M damage; P < AVERAGE, the target is banished (save ends)
tier3: 11 + M damage; P < STRONG, the target is banished (save ends)
type: ability
---

```ds-feature
cost: 11 Wrath
distance: Melee 1
effects:
    - effect: This ability gains an edge against demons, [devils](../../../../ancestry/devil.md), undead, and creatures not native to your current world. If you know the target's true name, this ability has a double edge. While banished, the target is sent to another manifold in the timescape and removed from the encounter map. A banished target can do nothing but make saving throws, and takes 10 holy damage each time they do so. If the target is reduced to 0 Stamina while banished, they are lost to the timescape.
    - roll: Power Roll + Might
      tier1: 5 + M damage; P < WEAK, the target is banished (save ends)
      tier2: 8 + M damage; P < AVERAGE, the target is banished (save ends)
      tier3: 11 + M damage; P < STRONG, the target is banished (save ends)
feature_type: ability
flavor: You sever the target's tenuous connection to the world.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 11 Wrath
    distance: Melee 1
    effect: This ability gains an edge against demons, [devils](../../../../ancestry/devil.md), undead, and creatures not native to your current world. If you know the target's true name, this ability has a double edge. While banished, the target is sent to another manifold in the timescape and removed from the encounter map. A banished target can do nothing but make saving throws, and takes 10 holy damage each time they do so. If the target is reduced to 0 Stamina while banished, they are lost to the timescape.
    flavor: You sever the target's tenuous connection to the world.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "9"
    name: Banish
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.censor.level-9/banish
    target: One creature
    tier1: 5 + M damage; P < WEAK, the target is banished (save ends)
    tier2: 8 + M damage; P < AVERAGE, the target is banished (save ends)
    tier3: 11 + M damage; P < STRONG, the target is banished (save ends)
    type: ability
name: Banish
target: One creature
type: feature
usage: Main action
```
