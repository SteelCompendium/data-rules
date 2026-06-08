---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: 4 [cube](../../../../rule/combat/cube.md) within 10
feature_type: ability
file_basename: penance
file_dpath: feature/ability/conduit/level-5
flavor: '"If you won''t kneel, the gods will make you."'
item_id: penance
item_name: Penance
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "5"
name: Penance
scc: mcdm.heroes.v1/feature.ability.conduit.level-5/penance
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 9 Piety
distance: 4 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: "\n*\"If you won't kneel, the gods will make you.\"*\n\n| **Area, Magic, [Ranged](../../../../rule/combat/ranged.md)**  |               **Main action** |\n|--------------------------|------------------------------:|\n| **\U0001F4CF 4 [cube](../../../../rule/combat/cube.md) within 10**  | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Intuition](../../../../rule/character/intuition.md):**\n\n- **≤11:** 4 corruption damage; I < WEAK, [prone and](../../../../condition/prone.md) can't stand (save ends)\n- **12-16:** 7 corruption damage; I < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)\n- **17+:** 11 corruption damage; I < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)"
feature_type: ability
flavor: '"If you won''t kneel, the gods will make you."'
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: 4 [cube](../../../../rule/combat/cube.md) within 10
    flavor: '"If you won''t kneel, the gods will make you."'
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "5"
    name: Penance
    scc: mcdm.heroes.v1/feature.ability.conduit.level-5/penance
    target: Each enemy in the area
    type: ability
name: Penance
target: Each enemy in the area
type: feature
usage: Main action
```
