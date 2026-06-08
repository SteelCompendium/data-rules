---
action_type: Main action
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: Melee 1
effect: If the target is hit with two or more strikes as part of this ability and they have R < STRONG, they are [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends). If the target is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) before one or both allies has made their [strike](scc:mcdm.heroes.v1/rule.combat/strike), the ally or allies can pick a different target.
feature_type: ability
file_basename: to-me-squad
file_dpath: feature/ability/tactician/level-6
flavor: You lead your allies in a charge.
item_id: to-me-squad
item_name: To Me Squad!
keywords:
    - Charge
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: To Me Squad!
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/to-me-squad
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 9 Focus
distance: Melee 1
effects:
    - effect: If the target is hit with two or more strikes as part of this ability and they have R < STRONG, they are [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends). If the target is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) before one or both allies has made their [strike](scc:mcdm.heroes.v1/rule.combat/strike), the ally or allies can pick a different target.
feature_type: ability
flavor: You lead your allies in a charge.
keywords:
    - Charge
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 9 Focus
    distance: Melee 1
    effect: If the target is hit with two or more strikes as part of this ability and they have R < STRONG, they are [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends). If the target is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) before one or both allies has made their [strike](scc:mcdm.heroes.v1/rule.combat/strike), the ally or allies can pick a different target.
    flavor: You lead your allies in a charge.
    keywords:
        - Charge
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "6"
    name: To Me Squad!
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/to-me-squad
    target: One creature
    type: ability
name: To Me Squad!
target: One creature
type: feature
usage: Main action
```
