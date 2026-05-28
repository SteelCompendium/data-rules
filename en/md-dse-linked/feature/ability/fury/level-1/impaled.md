---
action_type: Main action
class: fury
distance: Melee 1
feature_type: ability
file_basename: impaled
file_dpath: feature/ability/fury/level-1
flavor: You skewer your enemy like a boar upon a spit.
item_id: impaled
item_name: Impaled!
keywords:
    - Melee
    - Strike
    - Weapon
level: "1"
name: Impaled!
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-1/impaled
source: mcdm.heroes.v1
subtype: signature
target: One creature of your size or smaller
tier1: 2 + M damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
tier2: 5 + M damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
tier3: 7 + M damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 2 + M damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
      tier2: 5 + M damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
      tier3: 7 + M damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
feature_type: ability
flavor: You skewer your enemy like a boar upon a spit.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: fury
    distance: Melee 1
    flavor: You skewer your enemy like a boar upon a spit.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Impaled!
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/impaled
    subtype: signature
    target: One creature of your size or smaller
    tier1: 2 + M damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
    tier2: 5 + M damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
    tier3: 7 + M damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
    type: ability
name: Impaled!
target: One creature of your size or smaller
type: feature
usage: Main action
```
