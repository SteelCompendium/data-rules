---
action_type: Main action
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: Melee 1 or ranged 10
effect: '[Forced movement](scc:mcdm.heroes.v1/movement/forced-movement) from this ability ignores stability.'
feature_type: ability
file_basename: melt-their-faces
file_dpath: feature/ability/troubadour/level-9
flavor: The power of music rips through the reality around the target and blows them away.
item_id: melt-their-faces
item_name: Melt Their Faces
keywords:
    - Magic
    - Melee
    - Ranged
    - Strike
level: "9"
name: Melt Their Faces
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/melt-their-faces
source: mcdm.heroes.v1
target: One creature or object
tier1: 12 + P sonic damage; push 5
tier2: 16 + P sonic damage; push 10
tier3: 22 + P sonic damage; push 15
type: ability
---

```ds-feature
cost: 11 Drama
distance: Melee 1 or ranged 10
effects:
    - effect: '[Forced movement](scc:mcdm.heroes.v1/movement/forced-movement) from this ability ignores stability.'
    - roll: Power Roll + Presence
      tier1: 12 + P sonic damage; push 5
      tier2: 16 + P sonic damage; push 10
      tier3: 22 + P sonic damage; push 15
feature_type: ability
flavor: The power of music rips through the reality around the target and blows them away.
keywords:
    - Magic
    - Melee
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: troubadour
    cost: 11 Drama
    distance: Melee 1 or ranged 10
    effect: '[Forced movement](scc:mcdm.heroes.v1/movement/forced-movement) from this ability ignores stability.'
    flavor: The power of music rips through the reality around the target and blows them away.
    keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
    level: "9"
    name: Melt Their Faces
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/melt-their-faces
    target: One creature or object
    tier1: 12 + P sonic damage; push 5
    tier2: 16 + P sonic damage; push 10
    tier3: 22 + P sonic damage; push 15
    type: ability
name: Melt Their Faces
target: One creature or object
type: feature
usage: Main action
```
