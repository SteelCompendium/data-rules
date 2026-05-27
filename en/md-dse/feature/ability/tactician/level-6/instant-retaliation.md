---
action_type: Free triggered
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: Melee 1
effect: The target takes half the damage. You then make a power roll against the triggering creature.
feature_type: ability
file_basename: instant-retaliation
file_dpath: feature/ability/tactician/level-6
flavor: You [parry](scc:mcdm.heroes.v1/feature.ability.tactician.level-1/parry) with almost supernatural speed.
item_id: instant-retaliation
item_name: Instant Retaliation
keywords:
    - Melee
    - Weapon
level: "6"
name: Instant Retaliation
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/instant-retaliation
source: mcdm.heroes.v1
subtype: triggered
target: One ally
tier1: A < WEAK, dazed (save ends)
tier2: A < AVERAGE, dazed (save ends)
tier3: A < STRONG, dazed (save ends)
trigger: A creature deals damage to the target.
type: ability
---

```ds-feature
cost: 9 Focus
distance: Melee 1
effects:
    - effect: The target takes half the damage. You then make a power roll against the triggering creature.
    - roll: Power Roll + Might
      tier1: A < WEAK, dazed (save ends)
      tier2: A < AVERAGE, dazed (save ends)
      tier3: A < STRONG, dazed (save ends)
feature_type: ability
flavor: You [parry](scc:mcdm.heroes.v1/feature.ability.tactician.level-1/parry) with almost supernatural speed.
keywords:
    - Melee
    - Weapon
metadata:
    action_type: Free triggered
    class: tactician
    cost: 9 Focus
    distance: Melee 1
    effect: The target takes half the damage. You then make a power roll against the triggering creature.
    flavor: You [parry](scc:mcdm.heroes.v1/feature.ability.tactician.level-1/parry) with almost supernatural speed.
    keywords:
        - Melee
        - Weapon
    level: "6"
    name: Instant Retaliation
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/instant-retaliation
    subtype: triggered
    target: One ally
    tier1: A < WEAK, dazed (save ends)
    tier2: A < AVERAGE, dazed (save ends)
    tier3: A < STRONG, dazed (save ends)
    trigger: A creature deals damage to the target.
    type: ability
name: Instant Retaliation
target: One ally
trigger: A creature deals damage to the target.
type: feature
usage: Free triggered
```
