---
action_type: Main action
class: fury
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: 1 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
feature_type: ability
file_basename: back
file_dpath: feature/ability/fury/level-1
flavor: You hew about you with your mighty weapon, hurling enemies backward.
item_id: back
item_name: Back!
keywords:
    - Area
    - Melee
    - Weapon
level: "1"
name: Back!
scc: mcdm.heroes.v1/feature.ability.fury.level-1/back
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: 1 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: "\n*You hew about you with your mighty weapon, hurling enemies backward.*\n\n| **Area, Melee, Weapon** |               **Main action** |\n|-------------------------|------------------------------:|\n| **\U0001F4CF 1 [burst](scc:mcdm.heroes.v1/rule.combat/burst)**          | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**\n\n- **≤11:** 5 damage\n- **12-16:** 8 damage; push 1\n- **17+:** 11 damage; push 3"
feature_type: ability
flavor: You hew about you with your mighty weapon, hurling enemies backward.
keywords:
    - Area
    - Melee
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 3 Ferocity
    distance: 1 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
    flavor: You hew about you with your mighty weapon, hurling enemies backward.
    keywords:
        - Area
        - Melee
        - Weapon
    level: "1"
    name: Back!
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/back
    target: Each enemy in the area
    type: ability
name: Back!
target: Each enemy in the area
type: feature
usage: Main action
```
