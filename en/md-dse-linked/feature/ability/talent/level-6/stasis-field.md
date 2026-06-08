---
action_type: Main action
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: 4 cube within 10
effect: The area is frozen in time until the start of your next turn. Each object in the area is [restrained](../../../../condition/restrained.md) and can't fall until the effect ends. Until the effect ends, creatures in the area who are reduced to 0 [Stamina](../../../../rule/health/stamina.md) or would die stay alive, and objects in the area that are reduced to 0 [Stamina](../../../../rule/health/stamina.md) remain undestroyed.
feature_type: ability
file_basename: stasis-field
file_dpath: feature/ability/talent/level-6
flavor: Keep everything as it was. Ignore everything that will be.
item_id: stasis-field
item_name: Stasis Field
keywords:
    - Area
    - Chronopathy
    - Psionic
    - Ranged
level: "6"
name: Stasis Field
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.talent.level-6/stasis-field
source: mcdm.heroes.v1
target: Each creature and object in the area
tier1: P < WEAK, the target is [slowed](../../../../condition/slowed.md) until the effect ends
tier2: P < AVERAGE, the target's speed is 0 until the effect ends
tier3: P < STRONG, the target is [restrained](../../../../condition/restrained.md) until the effect ends
type: ability
---

```ds-feature
cost: 9 Clarity
distance: 4 cube within 10
effects:
    - effect: The area is frozen in time until the start of your next turn. Each object in the area is [restrained](../../../../condition/restrained.md) and can't fall until the effect ends. Until the effect ends, creatures in the area who are reduced to 0 [Stamina](../../../../rule/health/stamina.md) or would die stay alive, and objects in the area that are reduced to 0 [Stamina](../../../../rule/health/stamina.md) remain undestroyed.
    - roll: Power Roll + Presence
      tier1: P < WEAK, the target is [slowed](../../../../condition/slowed.md) until the effect ends
      tier2: P < AVERAGE, the target's speed is 0 until the effect ends
      tier3: P < STRONG, the target is [restrained](../../../../condition/restrained.md) until the effect ends
feature_type: ability
flavor: Keep everything as it was. Ignore everything that will be.
keywords:
    - Area
    - Chronopathy
    - Psionic
    - Ranged
metadata:
    action_type: Main action
    class: talent
    cost: 9 Clarity
    distance: 4 cube within 10
    effect: The area is frozen in time until the start of your next turn. Each object in the area is [restrained](../../../../condition/restrained.md) and can't fall until the effect ends. Until the effect ends, creatures in the area who are reduced to 0 [Stamina](../../../../rule/health/stamina.md) or would die stay alive, and objects in the area that are reduced to 0 [Stamina](../../../../rule/health/stamina.md) remain undestroyed.
    flavor: Keep everything as it was. Ignore everything that will be.
    keywords:
        - Area
        - Chronopathy
        - Psionic
        - Ranged
    level: "6"
    name: Stasis Field
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.talent.level-6/stasis-field
    target: Each creature and object in the area
    tier1: P < WEAK, the target is [slowed](../../../../condition/slowed.md) until the effect ends
    tier2: P < AVERAGE, the target's speed is 0 until the effect ends
    tier3: P < STRONG, the target is [restrained](../../../../condition/restrained.md) until the effect ends
    type: ability
name: Stasis Field
target: Each creature and object in the area
type: feature
usage: Main action
```
