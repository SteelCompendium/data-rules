---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: Ranged 10
effect: If this damage kills the target, you and each ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: your-story-ends-here
file_dpath: feature/ability/conduit/level-6
flavor: You bend the fate of a foe, willing them to die.
item_id: your-story-ends-here
item_name: Your Story Ends Here
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "6"
name: Your Story Ends Here
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/your-story-ends-here
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 9 Piety
distance: Ranged 10
effects:
    - effect: If this damage kills the target, you and each ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
flavor: You bend the fate of a foe, willing them to die.
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: Ranged 10
    effect: If this damage kills the target, you and each ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
    flavor: You bend the fate of a foe, willing them to die.
    keywords:
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "6"
    name: Your Story Ends Here
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/your-story-ends-here
    target: One creature
    type: ability
name: Your Story Ends Here
target: One creature
type: feature
usage: Main action
```
