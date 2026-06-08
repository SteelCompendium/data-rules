---
action_type: Triggered
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: Ranged 10
effect: The target takes their turn after the triggering hero, and immediately removes all conditions and negative effects on themself. During their turn, the target has a double [edge](scc:mcdm.heroes.v1/rule.dice/edge) on [power rolls](scc:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
file_basename: fulfill-your-destiny
file_dpath: feature/ability/censor/level-9
flavor: You have looked at various futures, and only this one works.
item_id: fulfill-your-destiny
item_name: Fulfill Your Destiny
keywords:
    - Magic
    - Ranged
level: "9"
name: Fulfill Your Destiny
scc: mcdm.heroes.v1/feature.ability.censor.level-9/fulfill-your-destiny
source: mcdm.heroes.v1
subtype: triggered
target: One ally
trigger: You or another hero ends their turn.
type: ability
---

```ds-feature
cost: 11 Wrath
distance: Ranged 10
effects:
    - effect: The target takes their turn after the triggering hero, and immediately removes all conditions and negative effects on themself. During their turn, the target has a double [edge](scc:mcdm.heroes.v1/rule.dice/edge) on [power rolls](scc:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
flavor: You have looked at various futures, and only this one works.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Triggered
    class: censor
    cost: 11 Wrath
    distance: Ranged 10
    effect: The target takes their turn after the triggering hero, and immediately removes all conditions and negative effects on themself. During their turn, the target has a double [edge](scc:mcdm.heroes.v1/rule.dice/edge) on [power rolls](scc:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: You have looked at various futures, and only this one works.
    keywords:
        - Magic
        - Ranged
    level: "9"
    name: Fulfill Your Destiny
    scc: mcdm.heroes.v1/feature.ability.censor.level-9/fulfill-your-destiny
    subtype: triggered
    target: One ally
    trigger: You or another hero ends their turn.
    type: ability
name: Fulfill Your Destiny
target: One ally
trigger: You or another hero ends their turn.
type: feature
usage: Triggered
```
