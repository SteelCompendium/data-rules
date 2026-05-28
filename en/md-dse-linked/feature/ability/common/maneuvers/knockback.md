---
action_type: Maneuver
distance: Melee 1
effect: You can usually target only creatures of your size or smaller. If your Might score is 2 or higher, you can target any creature with a size equal to or less than your Might score.
feature_type: ability
file_basename: knockback
file_dpath: feature/ability/common/maneuvers
item_id: knockback
item_name: Knockback
keywords:
    - Melee
    - Weapon
name: Knockback
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.common.maneuvers/knockback
source: mcdm.heroes.v1
target: One creature
tier1: Push 1
tier2: Push 2
tier3: Push 3
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You can usually target only creatures of your size or smaller. If your Might score is 2 or higher, you can target any creature with a size equal to or less than your Might score.
    - roll: Power Roll + Might
      tier1: Push 1
      tier2: Push 2
      tier3: Push 3
feature_type: ability
keywords:
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    distance: Melee 1
    effect: You can usually target only creatures of your size or smaller. If your Might score is 2 or higher, you can target any creature with a size equal to or less than your Might score.
    keywords:
        - Melee
        - Weapon
    name: Knockback
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.common.maneuvers/knockback
    target: One creature
    tier1: Push 1
    tier2: Push 2
    tier3: Push 3
    type: ability
name: Knockback
target: One creature
type: feature
usage: Maneuver
```
