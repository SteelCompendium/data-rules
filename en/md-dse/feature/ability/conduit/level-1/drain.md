---
action_type: Main action
class: conduit
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You or one ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: drain
file_dpath: feature/ability/conduit/level-1
flavor: You drain the energy from your target to revitalize yourself or an ally.
item_id: drain
item_name: Drain
keywords:
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Drain
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/drain
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You or one ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
flavor: You drain the energy from your target to revitalize yourself or an ally.
keywords:
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You or one ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
    flavor: You drain the energy from your target to revitalize yourself or an ally.
    keywords:
        - Magic
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Drain
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/drain
    subtype: signature
    target: One creature
    type: ability
name: Drain
target: One creature
type: feature
usage: Main action
```
