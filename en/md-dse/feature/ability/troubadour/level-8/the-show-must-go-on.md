---
action_type: Maneuver
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: 5 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effect: Each ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can't obtain lower than a tier 2 outcome on the next [test](scc:mcdm.heroes.v1/rule.test/test) they make before the start of your next turn.
feature_type: ability
file_basename: the-show-must-go-on
file_dpath: feature/ability/troubadour/level-8
flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
item_id: the-show-must-go-on
item_name: The Show Must Go On
keywords:
    - Area
    - Magic
    - Ranged
level: "8"
name: The Show Must Go On
scc: mcdm.heroes.v1/feature.ability.troubadour.level-8/the-show-must-go-on
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 11 Drama
distance: 5 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: Each ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can't obtain lower than a tier 2 outcome on the next [test](scc:mcdm.heroes.v1/rule.test/test) they make before the start of your next turn.
feature_type: ability
flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
keywords:
    - Area
    - Magic
    - Ranged
metadata:
    action_type: Maneuver
    class: troubadour
    cost: 11 Drama
    distance: 5 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: Each ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can't obtain lower than a tier 2 outcome on the next [test](scc:mcdm.heroes.v1/rule.test/test) they make before the start of your next turn.
    flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
    keywords:
        - Area
        - Magic
        - Ranged
    level: "8"
    name: The Show Must Go On
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-8/the-show-must-go-on
    target: Each enemy in the area
    type: ability
name: The Show Must Go On
target: Each enemy in the area
type: feature
usage: Maneuver
```
