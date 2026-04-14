---
action_type: Main action
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Self; see below
effect: You shift up to your speed and make one power roll that targets up to three enemies you move adjacent to during this shift.
feature_type: ability
file_basename: phalanx-breaker
file_dpath: feature/ability/fury/level-2
flavor: Organizing your forces like feckless creatures of Law. Pitiful.
item_id: phalanx-breaker
item_name: Phalanx-Breaker
keywords:
    - Melee
    - Weapon
level: "2"
name: Phalanx-Breaker
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-2/phalanx-breaker
source: mcdm.heroes.v1
target: Self
tier1: 2 damage; A < WEAK, dazed (save ends)
tier2: 4 damage; A < AVERAGE, dazed (save ends)
tier3: 6 damage; A < STRONG, dazed (save ends)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Self; see below
effects:
    - effect: You shift up to your speed and make one power roll that targets up to three enemies you move adjacent to during this shift.
    - roll: Power Roll + Might
      tier1: 2 damage; A < WEAK, dazed (save ends)
      tier2: 4 damage; A < AVERAGE, dazed (save ends)
      tier3: 6 damage; A < STRONG, dazed (save ends)
feature_type: ability
flavor: Organizing your forces like feckless creatures of Law. Pitiful.
keywords:
    - Melee
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 5 Ferocity
    distance: Self; see below
    effect: You shift up to your speed and make one power roll that targets up to three enemies you move adjacent to during this shift.
    flavor: Organizing your forces like feckless creatures of Law. Pitiful.
    keywords:
        - Melee
        - Weapon
    level: "2"
    name: Phalanx-Breaker
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-2/phalanx-breaker
    target: Self
    tier1: 2 damage; A < WEAK, dazed (save ends)
    tier2: 4 damage; A < AVERAGE, dazed (save ends)
    tier3: 6 damage; A < STRONG, dazed (save ends)
    type: ability
name: Phalanx-Breaker
target: Self
type: feature
usage: Main action
```
