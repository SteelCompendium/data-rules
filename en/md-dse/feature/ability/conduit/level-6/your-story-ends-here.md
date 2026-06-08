---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: Ranged 10
effect: If this damage kills the target, you and each ally within distance can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: your-story-ends-here
file_dpath: feature/ability/conduit/level-6
flavor: You bend the fate of a foe, willing them to die.
item_id: your-story-ends-here
item_name: Your Story Ends Here
keywords:
    - Magic
    - Ranged
    - Strike
level: "6"
name: Your Story Ends Here
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/your-story-ends-here
source: mcdm.heroes.v1
target: One creature
tier1: 9 + I corruption damage; R < WEAK, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 14 + I corruption damage; R < AVERAGE, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 19 + I corruption damage; R < STRONG, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---

```ds-feature
cost: 9 Piety
distance: Ranged 10
effects:
    - effect: If this damage kills the target, you and each ally within distance can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
    - roll: Power Roll + Intuition
      tier1: 9 + I corruption damage; R < WEAK, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 14 + I corruption damage; R < AVERAGE, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 19 + I corruption damage; R < STRONG, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
feature_type: ability
flavor: You bend the fate of a foe, willing them to die.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: Ranged 10
    effect: If this damage kills the target, you and each ally within distance can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries).
    flavor: You bend the fate of a foe, willing them to die.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "6"
    name: Your Story Ends Here
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/your-story-ends-here
    target: One creature
    tier1: 9 + I corruption damage; R < WEAK, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
    tier2: 14 + I corruption damage; R < AVERAGE, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 19 + I corruption damage; R < STRONG, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)
    type: ability
name: Your Story Ends Here
target: One creature
type: feature
usage: Main action
```
