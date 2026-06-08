---
action_type: Triggered
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: Ranged 10
effect: You can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries) to allow the target to regain [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc:mcdm.heroes.v1/rule.health/recoveries). The target can then take their turn immediately before the triggering enemy.
feature_type: ability
file_basename: prescient-grace
file_dpath: feature/ability/censor/level-2
flavor: Gifted by a prescient vision, you warn an ally of an impending attack.
item_id: prescient-grace
item_name: Prescient Grace
keywords:
    - Magic
    - Ranged
level: "2"
name: Prescient Grace
scc: mcdm.heroes.v1/feature.ability.censor.level-2/prescient-grace
source: mcdm.heroes.v1
subtype: triggered
target: Self or one ally
trigger: An enemy within 10 squares starts their turn.
type: ability
---

```ds-feature
cost: 5 Wrath
distance: Ranged 10
effects:
    - effect: You can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries) to allow the target to regain [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc:mcdm.heroes.v1/rule.health/recoveries). The target can then take their turn immediately before the triggering enemy.
feature_type: ability
flavor: Gifted by a prescient vision, you warn an ally of an impending attack.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Triggered
    class: censor
    cost: 5 Wrath
    distance: Ranged 10
    effect: You can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries) to allow the target to regain [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc:mcdm.heroes.v1/rule.health/recoveries). The target can then take their turn immediately before the triggering enemy.
    flavor: Gifted by a prescient vision, you warn an ally of an impending attack.
    keywords:
        - Magic
        - Ranged
    level: "2"
    name: Prescient Grace
    scc: mcdm.heroes.v1/feature.ability.censor.level-2/prescient-grace
    subtype: triggered
    target: Self or one ally
    trigger: An enemy within 10 squares starts their turn.
    type: ability
name: Prescient Grace
target: Self or one ally
trigger: An enemy within 10 squares starts their turn.
type: feature
usage: Triggered
```
