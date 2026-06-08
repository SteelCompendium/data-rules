---
action_type: Main action
class: conduit
cost: 3 Piety
cost_amount: "3"
cost_resource: Piety
distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effect: You can push each willing ally in the area the same [distance](scc:mcdm.heroes.v1/rule.combat/distance), ignoring [stability](scc:mcdm.heroes.v1/rule.character/stability).
feature_type: ability
file_basename: call-the-thunder-down
file_dpath: feature/ability/conduit/level-1
flavor: You ask your saint for thunder and your prayer is answered.
item_id: call-the-thunder-down
item_name: Call the Thunder Down
keywords:
    - Area
    - Magic
    - Ranged
level: "1"
name: Call the Thunder Down
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/call-the-thunder-down
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 3 Piety
distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: You can push each willing ally in the area the same [distance](scc:mcdm.heroes.v1/rule.combat/distance), ignoring [stability](scc:mcdm.heroes.v1/rule.character/stability).
feature_type: ability
flavor: You ask your saint for thunder and your prayer is answered.
keywords:
    - Area
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: conduit
    cost: 3 Piety
    distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: You can push each willing ally in the area the same [distance](scc:mcdm.heroes.v1/rule.combat/distance), ignoring [stability](scc:mcdm.heroes.v1/rule.character/stability).
    flavor: You ask your saint for thunder and your prayer is answered.
    keywords:
        - Area
        - Magic
        - Ranged
    level: "1"
    name: Call the Thunder Down
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/call-the-thunder-down
    target: Each enemy in the area
    type: ability
name: Call the Thunder Down
target: Each enemy in the area
type: feature
usage: Main action
```
