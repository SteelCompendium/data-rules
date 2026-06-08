---
action_type: Maneuver
class: troubadour
cost: 7 Drama
cost_amount: "7"
cost_resource: Drama
distance: 4 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
effect: Instead of sliding a target, you can swap their location with another target as long as each can fit into the other's space. You can't slide targets into other creatures or objects using this ability.
feature_type: ability
file_basename: extensive-rewrites
file_dpath: feature/ability/troubadour/level-3
flavor: No, this isn't right. That foe was over there!
item_id: extensive-rewrites
item_name: Extensive Rewrites
keywords:
    - Area
    - Magic
level: "3"
name: Extensive Rewrites
scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/extensive-rewrites
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 7 Drama
distance: 4 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Instead of sliding a target, you can swap their location with another target as long as each can fit into the other's space. You can't slide targets into other creatures or objects using this ability.
feature_type: ability
flavor: No, this isn't right. That foe was over there!
keywords:
    - Area
    - Magic
metadata:
    action_type: Maneuver
    class: troubadour
    cost: 7 Drama
    distance: 4 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
    effect: Instead of sliding a target, you can swap their location with another target as long as each can fit into the other's space. You can't slide targets into other creatures or objects using this ability.
    flavor: No, this isn't right. That foe was over there!
    keywords:
        - Area
        - Magic
    level: "3"
    name: Extensive Rewrites
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/extensive-rewrites
    target: Each enemy in the area
    type: ability
name: Extensive Rewrites
target: Each enemy in the area
type: feature
usage: Maneuver
```
