---
action_type: Main action
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: concussive-strike
file_dpath: feature/ability/tactician/level-1
flavor: Your precise strike leaves your foe struggling to respond.
item_id: concussive-strike
item_name: Concussive Strike
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "1"
name: Concussive Strike
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/concussive-strike
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + M damage; M < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
tier2: 5 + M damage; M < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
tier3: 8 + M damage; M < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 3 Focus
distance: Melee 1 or ranged 5
effects:
    - roll: Power Roll + Might
      tier1: 3 + M damage; M < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: 5 + M damage; M < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: 8 + M damage; M < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: Your precise strike leaves your foe struggling to respond.
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 3 Focus
    distance: Melee 1 or ranged 5
    flavor: Your precise strike leaves your foe struggling to respond.
    keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "1"
    name: Concussive Strike
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/concussive-strike
    target: One creature or object
    tier1: 3 + M damage; M < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
    tier2: 5 + M damage; M < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
    tier3: 8 + M damage; M < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Concussive Strike
target: One creature or object
type: feature
usage: Main action
```
