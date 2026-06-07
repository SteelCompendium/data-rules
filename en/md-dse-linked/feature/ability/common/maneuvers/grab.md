---
action_type: Maneuver
distance: Melee 1
effect: You can usually target only creatures of your size or smaller. If your Might score is 2 or higher, you can target any creature with a size equal to or less than your Might score.
feature_type: ability
file_basename: grab
file_dpath: feature/ability/common/maneuvers
item_id: grab
item_name: Grab
keywords:
    - Melee
    - Weapon
name: Grab
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.common.maneuvers/grab
source: mcdm.heroes.v1
target: One creature
tier1: No effect.
tier2: You can grab the target, but if you do, the target can make a melee [free strike](../../../trait/common/main-actions/free-strike.md) against you before they are [grabbed](../../../../condition/grabbed.md).
tier3: The target is [grabbed](../../../../condition/grabbed.md) by you.
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You can usually target only creatures of your size or smaller. If your Might score is 2 or higher, you can target any creature with a size equal to or less than your Might score.
    - roll: Power Roll + Might
      tier1: No effect.
      tier2: You can grab the target, but if you do, the target can make a melee [free strike](../../../trait/common/main-actions/free-strike.md) against you before they are [grabbed](../../../../condition/grabbed.md).
      tier3: The target is [grabbed](../../../../condition/grabbed.md) by you.
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
    name: Grab
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.common.maneuvers/grab
    target: One creature
    tier1: No effect.
    tier2: You can grab the target, but if you do, the target can make a melee [free strike](../../../trait/common/main-actions/free-strike.md) against you before they are [grabbed](../../../../condition/grabbed.md).
    tier3: The target is [grabbed](../../../../condition/grabbed.md) by you.
    type: ability
name: Grab
target: One creature
type: feature
usage: Maneuver
```
