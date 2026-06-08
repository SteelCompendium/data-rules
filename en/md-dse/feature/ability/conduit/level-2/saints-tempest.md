---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
feature_type: ability
file_basename: saints-tempest
file_dpath: feature/ability/conduit/level-2
flavor: A raging storm appears, striking your foes with lightning and throwing them around with wind.
item_id: saints-tempest
item_name: Saint's Tempest
keywords:
    - Area
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Saint's Tempest
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/saints-tempest
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 5 Piety
distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: "\n*A raging storm appears, striking your foes with lightning and throwing them around with wind.*\n\n| **Area, Magic, [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)**  |               **Main action** |\n|--------------------------|------------------------------:|\n| **\U0001F4CF 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10**  | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc:mcdm.heroes.v1/rule.character/intuition):**\n\n- **≤11:** 2 lightning damage; vertical slide 1\n- **12-16:** 5 lightning damage; vertical slide 2\n- **17+:** 7 lightning damage; vertical slide 3"
feature_type: ability
flavor: A raging storm appears, striking your foes with lightning and throwing them around with wind.
keywords:
    - Area
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
    flavor: A raging storm appears, striking your foes with lightning and throwing them around with wind.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Saint's Tempest
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/saints-tempest
    target: Each enemy in the area
    type: ability
name: Saint's Tempest
target: Each enemy in the area
type: feature
usage: Main action
```
