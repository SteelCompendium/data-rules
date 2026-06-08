---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
feature_type: ability
file_basename: nature-judges-thee
file_dpath: feature/ability/conduit/level-2
flavor: Mystical thorned vines appear at your bidding and bind your foes.
item_id: nature-judges-thee
item_name: Nature Judges Thee
keywords:
    - Area
    - Magic
    - Ranged
level: "2"
name: Nature Judges Thee
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/nature-judges-thee
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 5 Piety
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: "\n*Mystical thorned vines appear at your bidding and bind your foes.*\n\n| **Area, Magic, Ranged**  |               **Main action** |\n|--------------------------|------------------------------:|\n| **\U0001F4CF 3 [cube](../../../../rule/combat/cube.md) within 10**  | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Intuition](../../../../rule/character/intuition.md):**\n\n- **≤11:** 2 damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)\n- **12-16:** 3 damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)\n- **17+:** 7 damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)"
feature_type: ability
flavor: Mystical thorned vines appear at your bidding and bind your foes.
keywords:
    - Area
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: 3 [cube](../../../../rule/combat/cube.md) within 10
    flavor: Mystical thorned vines appear at your bidding and bind your foes.
    keywords:
        - Area
        - Magic
        - Ranged
    level: "2"
    name: Nature Judges Thee
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/nature-judges-thee
    target: Each enemy in the area
    type: ability
name: Nature Judges Thee
target: Each enemy in the area
type: feature
usage: Main action
```
