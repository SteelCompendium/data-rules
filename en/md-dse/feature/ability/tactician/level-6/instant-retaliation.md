---
action_type: Free triggered
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effect: The target takes half the damage. You then make a [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll) against the triggering creature.
feature_type: ability
file_basename: instant-retaliation
file_dpath: feature/ability/tactician/level-6
flavor: You [parry](scc:mcdm.heroes.v1/feature.ability.tactician.level-1/parry) with almost [supernatural](scc:mcdm.heroes.v1/rule.general/supernatural) [speed](scc:mcdm.heroes.v1/rule.character/speed).
item_id: instant-retaliation
item_name: Instant Retaliation
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "6"
name: Instant Retaliation
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/instant-retaliation
source: mcdm.heroes.v1
subtype: triggered
target: One ally
trigger: A creature deals damage to the target.
type: ability
---

```ds-feature
cost: 9 Focus
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: The target takes half the damage. You then make a [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll) against the triggering creature.
feature_type: ability
flavor: You [parry](scc:mcdm.heroes.v1/feature.ability.tactician.level-1/parry) with almost [supernatural](scc:mcdm.heroes.v1/rule.general/supernatural) [speed](scc:mcdm.heroes.v1/rule.character/speed).
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: Free triggered
    class: tactician
    cost: 9 Focus
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: The target takes half the damage. You then make a [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll) against the triggering creature.
    flavor: You [parry](scc:mcdm.heroes.v1/feature.ability.tactician.level-1/parry) with almost [supernatural](scc:mcdm.heroes.v1/rule.general/supernatural) [speed](scc:mcdm.heroes.v1/rule.character/speed).
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "6"
    name: Instant Retaliation
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/instant-retaliation
    subtype: triggered
    target: One ally
    trigger: A creature deals damage to the target.
    type: ability
name: Instant Retaliation
target: One ally
trigger: A creature deals damage to the target.
type: feature
usage: Free triggered
```
