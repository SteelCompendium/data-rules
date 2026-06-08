---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: Melee 1
effect: When a target who is not a leader or solo creature is made [winded](scc:mcdm.heroes.v1/rule.health/winded) by this ability, they are reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).
feature_type: ability
file_basename: censored
file_dpath: feature/ability/censor/level-1
flavor: Judged and [sentenced](scc:mcdm.heroes.v1/feature.ability.censor.level-2/sentenced).
item_id: censored
item_name: Censored
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Censored
scc: mcdm.heroes.v1/feature.ability.censor.level-1/censored
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Wrath
distance: Melee 1
effects:
    - effect: When a target who is not a leader or solo creature is made [winded](scc:mcdm.heroes.v1/rule.health/winded) by this ability, they are reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).
feature_type: ability
flavor: Judged and [sentenced](scc:mcdm.heroes.v1/feature.ability.censor.level-2/sentenced).
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 5 Wrath
    distance: Melee 1
    effect: When a target who is not a leader or solo creature is made [winded](scc:mcdm.heroes.v1/rule.health/winded) by this ability, they are reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).
    flavor: Judged and [sentenced](scc:mcdm.heroes.v1/feature.ability.censor.level-2/sentenced).
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Censored
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/censored
    target: One creature
    type: ability
name: Censored
target: One creature
type: feature
usage: Main action
```
