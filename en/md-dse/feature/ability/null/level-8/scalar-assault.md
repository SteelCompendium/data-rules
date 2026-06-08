---
action_type: Main action
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: 3 cube within 1
feature_type: ability
file_basename: scalar-assault
file_dpath: feature/ability/null/level-8
flavor: You warp reality to grow a limb for just a moment and make a single devastating attack.
item_id: scalar-assault
item_name: Scalar Assault
keywords:
    - Area
    - Psionic
level: "8"
name: Scalar Assault
scc: mcdm.heroes.v1/feature.ability.null.level-8/scalar-assault
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 11 Discipline
distance: 3 cube within 1
effects:
    - effect: "\n*You warp reality to grow a limb for just a moment and make a single devastating attack.*\n\n| **Area, Psionic**      |               **Main action** |\n|------------------------|------------------------------:|\n| **\U0001F4CF 3 cube within 1** | **\U0001F3AF Each enemy in the area** |\n\n**Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 12 psychic damage; push 3\n- **12-16:** 17 psychic damage; push 5\n- **17+:** 23 psychic damage; push 7"
feature_type: ability
flavor: You warp reality to grow a limb for just a moment and make a single devastating attack.
keywords:
    - Area
    - Psionic
metadata:
    action_type: Main action
    class: "null"
    cost: 11 Discipline
    distance: 3 cube within 1
    flavor: You warp reality to grow a limb for just a moment and make a single devastating attack.
    keywords:
        - Area
        - Psionic
    level: "8"
    name: Scalar Assault
    scc: mcdm.heroes.v1/feature.ability.null.level-8/scalar-assault
    target: Each enemy in the area
    type: ability
name: Scalar Assault
target: Each enemy in the area
type: feature
usage: Main action
```
