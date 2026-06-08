---
action_type: Main action
class: troubadour
cost: 3 Drama
cost_amount: "3"
cost_resource: Drama
distance: 3 cube within 10
effect: The area is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain) for enemies.
feature_type: ability
file_basename: quick-rewrite
file_dpath: feature/ability/troubadour/level-1
flavor: You write something unexpected into the scene that hinders your enemy.
item_id: quick-rewrite
item_name: Quick Rewrite
keywords:
    - Area
    - Magic
    - Ranged
level: "1"
name: Quick Rewrite
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/quick-rewrite
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 3 Drama
distance: 3 cube within 10
effects:
    - effect: The area is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain) for enemies.
feature_type: ability
flavor: You write something unexpected into the scene that hinders your enemy.
keywords:
    - Area
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: troubadour
    cost: 3 Drama
    distance: 3 cube within 10
    effect: The area is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain) for enemies.
    flavor: You write something unexpected into the scene that hinders your enemy.
    keywords:
        - Area
        - Magic
        - Ranged
    level: "1"
    name: Quick Rewrite
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/quick-rewrite
    target: Each enemy in the area
    type: ability
name: Quick Rewrite
target: Each enemy in the area
type: feature
usage: Main action
```
