---
action_type: Free triggered
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: Ranged 10
effect: The target is unaffected by the strike and you become the target instead, even if you aren't a valid target for it. You take half the damage from the strike, and the target gains 3 [surges](scc:mcdm.heroes.v1/rule.resource/surge).
feature_type: ability
file_basename: intercede
file_dpath: feature/ability/censor/level-6
flavor: You take your ally's place.
item_id: intercede
item_name: Intercede
keywords:
    - Magic
    - Ranged
level: "6"
name: Intercede
scc: mcdm.heroes.v1/feature.ability.censor.level-6/intercede
source: mcdm.heroes.v1
subtype: triggered
target: One ally
trigger: A creature makes a strike against the target.
type: ability
---

```ds-feature
cost: 9 Wrath
distance: Ranged 10
effects:
    - effect: The target is unaffected by the strike and you become the target instead, even if you aren't a valid target for it. You take half the damage from the strike, and the target gains 3 [surges](scc:mcdm.heroes.v1/rule.resource/surge).
feature_type: ability
flavor: You take your ally's place.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Free triggered
    class: censor
    cost: 9 Wrath
    distance: Ranged 10
    effect: The target is unaffected by the strike and you become the target instead, even if you aren't a valid target for it. You take half the damage from the strike, and the target gains 3 [surges](scc:mcdm.heroes.v1/rule.resource/surge).
    flavor: You take your ally's place.
    keywords:
        - Magic
        - Ranged
    level: "6"
    name: Intercede
    scc: mcdm.heroes.v1/feature.ability.censor.level-6/intercede
    subtype: triggered
    target: One ally
    trigger: A creature makes a strike against the target.
    type: ability
name: Intercede
target: One ally
trigger: A creature makes a strike against the target.
type: feature
usage: Free triggered
```
