---
action_type: Main action
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
effect: On a [critical hit](scc:mcdm.heroes.v1/rule.combat/critical-hit), the target is [grabbed](scc:mcdm.heroes.v1/condition/grabbed) by the demon and [pulled](scc:mcdm.heroes.v1/movement/forced-movement) through the portal before it closes, never to be seen again.
feature_type: ability
file_basename: demon-door
file_dpath: feature/ability/shadow/level-9
flavor: You create a temporary portal to allow a massive demonic hand to reach through.
item_id: demon-door
item_name: Demon Door
keywords:
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Demon Door
power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-9/demon-door
source: mcdm.heroes.v1
target: One creature
tier1: 13 + A corruption damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 3
tier2: 18 + A corruption damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 5
tier3: 25 + A corruption damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 7
type: ability
---

```ds-feature
cost: 11 Insight
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
effects:
    - effect: On a [critical hit](scc:mcdm.heroes.v1/rule.combat/critical-hit), the target is [grabbed](scc:mcdm.heroes.v1/condition/grabbed) by the demon and [pulled](scc:mcdm.heroes.v1/movement/forced-movement) through the portal before it closes, never to be seen again.
    - roll: Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility)
      tier1: 13 + A corruption damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 18 + A corruption damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 25 + A corruption damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 7
feature_type: ability
flavor: You create a temporary portal to allow a massive demonic hand to reach through.
keywords:
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 11 Insight
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
    effect: On a [critical hit](scc:mcdm.heroes.v1/rule.combat/critical-hit), the target is [grabbed](scc:mcdm.heroes.v1/condition/grabbed) by the demon and [pulled](scc:mcdm.heroes.v1/movement/forced-movement) through the portal before it closes, never to be seen again.
    flavor: You create a temporary portal to allow a massive demonic hand to reach through.
    keywords:
        - Magic
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: Demon Door
    power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-9/demon-door
    target: One creature
    tier1: 13 + A corruption damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 3
    tier2: 18 + A corruption damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 5
    tier3: 25 + A corruption damage; [push](scc:mcdm.heroes.v1/movement/forced-movement) 7
    type: ability
name: Demon Door
target: One creature
type: feature
usage: Main action
```
