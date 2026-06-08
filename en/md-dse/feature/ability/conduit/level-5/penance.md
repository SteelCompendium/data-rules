---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: 4 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
feature_type: ability
file_basename: penance
file_dpath: feature/ability/conduit/level-5
flavor: '"If you won''t kneel, the gods will make you."'
item_id: penance
item_name: Penance
keywords:
    - Area
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
level: "5"
name: Penance
scc: mcdm.heroes.v1/feature.ability.conduit.level-5/penance
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 9 Piety
distance: 4 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: "\n*\"If you won't kneel, the gods will make you.\"*\n\n| **Area, Magic, [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)**  |               **Main action** |\n|--------------------------|------------------------------:|\n| **\U0001F4CF 4 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10**  | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc:mcdm.heroes.v1/rule.character/intuition):**\n\n- **≤11:** 4 corruption damage; I < WEAK, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)\n- **12-16:** 7 corruption damage; I < AVERAGE, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)\n- **17+:** 11 corruption damage; I < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)"
feature_type: ability
flavor: '"If you won''t kneel, the gods will make you."'
keywords:
    - Area
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: 4 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
    flavor: '"If you won''t kneel, the gods will make you."'
    keywords:
        - Area
        - Magic
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
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
