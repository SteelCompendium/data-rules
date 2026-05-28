---
action_type: Main action
class: "null"
distance: Melee 1
effect: Before the push is resolved, you [teleport](scc:mcdm.heroes.v1/movement/teleport) the target to a square adjacent to you and opposite the one they started in. If the target can't be [teleport](scc:mcdm.heroes.v1/movement/teleport)ed this way, you can't push them.
feature_type: ability
file_basename: phase-inversion-strike
file_dpath: feature/ability/null/level-1
flavor: You step momentarily out of phase as you pull an enemy through you.
item_id: phase-inversion-strike
item_name: Phase Inversion Strike
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
level: "1"
name: Phase Inversion Strike
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.null.level-1/phase-inversion-strike
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 4 + A damage; push 2
tier2: 6 + A damage; push 4
tier3: 8 + A damage; push 6
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: Before the push is resolved, you [teleport](scc:mcdm.heroes.v1/movement/teleport) the target to a square adjacent to you and opposite the one they started in. If the target can't be [teleport](scc:mcdm.heroes.v1/movement/teleport)ed this way, you can't push them.
    - roll: Power Roll + Agility
      tier1: 4 + A damage; push 2
      tier2: 6 + A damage; push 4
      tier3: 8 + A damage; push 6
feature_type: ability
flavor: You step momentarily out of phase as you pull an enemy through you.
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: Melee 1
    effect: Before the push is resolved, you [teleport](scc:mcdm.heroes.v1/movement/teleport) the target to a square adjacent to you and opposite the one they started in. If the target can't be [teleport](scc:mcdm.heroes.v1/movement/teleport)ed this way, you can't push them.
    flavor: You step momentarily out of phase as you pull an enemy through you.
    keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
    level: "1"
    name: Phase Inversion Strike
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.null.level-1/phase-inversion-strike
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage; push 2
    tier2: 6 + A damage; push 4
    tier3: 8 + A damage; push 6
    type: ability
name: Phase Inversion Strike
target: One creature or object
type: feature
usage: Main action
```
