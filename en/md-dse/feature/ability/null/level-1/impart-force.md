---
action_type: Maneuver
class: "null"
cost: 5 Discipline
cost_amount: "5"
cost_resource: Discipline
distance: Melee 1
effect: An object you target must be your size or smaller. You gain an edge on this ability. Additionally, for each square you push the target, they take 1 psychic damage.
feature_type: ability
file_basename: impart-force
file_dpath: feature/ability/null/level-1
flavor: A single touch from you, and your enemy flies backward.
item_id: impart-force
item_name: Impart Force
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
level: "1"
name: Impart Force
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.null.level-1/impart-force
source: mcdm.heroes.v1
target: One creature or object
tier1: Push 3
tier2: Push 5
tier3: Push 7
type: ability
---

```ds-feature
cost: 5 Discipline
distance: Melee 1
effects:
    - effect: An object you target must be your size or smaller. You gain an edge on this ability. Additionally, for each square you push the target, they take 1 psychic damage.
    - roll: Power Roll + Intuition
      tier1: Push 3
      tier2: Push 5
      tier3: Push 7
feature_type: ability
flavor: A single touch from you, and your enemy flies backward.
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
metadata:
    action_type: Maneuver
    class: "null"
    cost: 5 Discipline
    distance: Melee 1
    effect: An object you target must be your size or smaller. You gain an edge on this ability. Additionally, for each square you push the target, they take 1 psychic damage.
    flavor: A single touch from you, and your enemy flies backward.
    keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
    level: "1"
    name: Impart Force
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.null.level-1/impart-force
    target: One creature or object
    tier1: Push 3
    tier2: Push 5
    tier3: Push 7
    type: ability
name: Impart Force
target: One creature or object
type: feature
usage: Maneuver
```
