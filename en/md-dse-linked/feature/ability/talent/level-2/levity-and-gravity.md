---
action_type: Main action
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: Ranged 10
feature_type: ability
file_basename: levity-and-gravity
file_dpath: feature/ability/talent/level-2
flavor: You raise the target slightly into the air, then smother them against the ground.
item_id: levity-and-gravity
item_name: Levity and Gravity
keywords:
    - Psionic
    - Ranged
    - Strike
    - Telekinesis
level: "2"
name: Levity and Gravity
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.talent.level-2/levity-and-gravity
source: mcdm.heroes.v1
target: One creature or object
tier1: 6 + R damage; M < WEAK[, prone](scc:mcdm.heroes.v1/condition/prone)
tier2: 10 + R damage; M < AVERAGE[, prone](scc:mcdm.heroes.v1/condition/prone)
tier3: 14 + R damage; M < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)
type: ability
---

```ds-feature
cost: 5 Clarity
distance: Ranged 10
effects:
    - roll: Power Roll + Reason
      tier1: 6 + R damage; M < WEAK[, prone](scc:mcdm.heroes.v1/condition/prone)
      tier2: 10 + R damage; M < AVERAGE[, prone](scc:mcdm.heroes.v1/condition/prone)
      tier3: 14 + R damage; M < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)
feature_type: ability
flavor: You raise the target slightly into the air, then smother them against the ground.
keywords:
    - Psionic
    - Ranged
    - Strike
    - Telekinesis
metadata:
    action_type: Main action
    class: talent
    cost: 5 Clarity
    distance: Ranged 10
    flavor: You raise the target slightly into the air, then smother them against the ground.
    keywords:
        - Psionic
        - Ranged
        - Strike
        - Telekinesis
    level: "2"
    name: Levity and Gravity
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/levity-and-gravity
    target: One creature or object
    tier1: 6 + R damage; M < WEAK[, prone](scc:mcdm.heroes.v1/condition/prone)
    tier2: 10 + R damage; M < AVERAGE[, prone](scc:mcdm.heroes.v1/condition/prone)
    tier3: 14 + R damage; M < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)
    type: ability
name: Levity and Gravity
target: One creature or object
type: feature
usage: Main action
```
