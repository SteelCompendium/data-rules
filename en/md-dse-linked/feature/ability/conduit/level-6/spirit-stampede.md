---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: 10 x 2 line within 5
feature_type: ability
file_basename: spirit-stampede
file_dpath: feature/ability/conduit/level-6
flavor: Animal spirits run through the battlefield, trampling your foes.
item_id: spirit-stampede
item_name: Spirit Stampede
keywords:
    - Area
    - Magic
    - Ranged
level: "6"
name: Spirit Stampede
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/spirit-stampede
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 9 Piety
distance: 10 x 2 line within 5
effects:
    - effect: "\n*Animal spirits run through the battlefield, trampling your foes.*\n\n| **Area, Magic, Ranged**     |               **Main action** |\n|-----------------------------|------------------------------:|\n| **\U0001F4CF 10 x 2 line within 5** | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Intuition](../../../../rule/character/intuition.md):**\n\n- **≤11:** 5 damage; M < WEAK, [prone and](../../../../condition/prone.md) can't stand (save ends)\n- **12-16:** 8 damage; M < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)\n- **17+:** 11 damage; M < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)"
feature_type: ability
flavor: Animal spirits run through the battlefield, trampling your foes.
keywords:
    - Area
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: 10 x 2 line within 5
    flavor: Animal spirits run through the battlefield, trampling your foes.
    keywords:
        - Area
        - Magic
        - Ranged
    level: "6"
    name: Spirit Stampede
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/spirit-stampede
    target: Each enemy in the area
    type: ability
name: Spirit Stampede
target: Each enemy in the area
type: feature
usage: Main action
```
