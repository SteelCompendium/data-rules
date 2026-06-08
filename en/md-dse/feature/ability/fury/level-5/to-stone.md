---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effect: While the target is [slowed](scc:mcdm.heroes.v1/condition/slowed) this way, any other effect that would make the target [slowed](scc:mcdm.heroes.v1/condition/slowed) instead makes them [restrained](scc:mcdm.heroes.v1/condition/restrained) by this ability. Additionally, a creature who fails the [saving throw](scc:mcdm.heroes.v1/rule.general/saving-throw) while [restrained](scc:mcdm.heroes.v1/condition/restrained) this way is petrified until they are given a [supernatural](scc:mcdm.heroes.v1/rule.general/supernatural) cure or you choose to reverse the effect (no action required).
feature_type: ability
file_basename: to-stone
file_dpath: feature/ability/fury/level-5
flavor: You channel the Primordial Chaos into blows that petrify your foe... literally.
item_id: to-stone
item_name: To Stone!
keywords:
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "5"
name: To Stone!
scc: mcdm.heroes.v1/feature.ability.fury.level-5/to-stone
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: While the target is [slowed](scc:mcdm.heroes.v1/condition/slowed) this way, any other effect that would make the target [slowed](scc:mcdm.heroes.v1/condition/slowed) instead makes them [restrained](scc:mcdm.heroes.v1/condition/restrained) by this ability. Additionally, a creature who fails the [saving throw](scc:mcdm.heroes.v1/rule.general/saving-throw) while [restrained](scc:mcdm.heroes.v1/condition/restrained) this way is petrified until they are given a [supernatural](scc:mcdm.heroes.v1/rule.general/supernatural) cure or you choose to reverse the effect (no action required).
feature_type: ability
flavor: You channel the Primordial Chaos into blows that petrify your foe... literally.
keywords:
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: While the target is [slowed](scc:mcdm.heroes.v1/condition/slowed) this way, any other effect that would make the target [slowed](scc:mcdm.heroes.v1/condition/slowed) instead makes them [restrained](scc:mcdm.heroes.v1/condition/restrained) by this ability. Additionally, a creature who fails the [saving throw](scc:mcdm.heroes.v1/rule.general/saving-throw) while [restrained](scc:mcdm.heroes.v1/condition/restrained) this way is petrified until they are given a [supernatural](scc:mcdm.heroes.v1/rule.general/supernatural) cure or you choose to reverse the effect (no action required).
    flavor: You channel the Primordial Chaos into blows that petrify your foe... literally.
    keywords:
        - Magic
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "5"
    name: To Stone!
    scc: mcdm.heroes.v1/feature.ability.fury.level-5/to-stone
    target: One creature
    type: ability
name: To Stone!
target: One creature
type: feature
usage: Main action
```
