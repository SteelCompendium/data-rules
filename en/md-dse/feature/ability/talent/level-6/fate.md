---
action_type: Main action
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: Melee 2
effect: The target has damage weakness 5 until the end of your next turn. Whenever the target takes damage while they have this weakness, they are [knocked prone](scc:mcdm.heroes.v1/condition/prone).
feature_type: ability
file_basename: fate
file_dpath: feature/ability/talent/level-6
flavor: Your foe gets a glimpse of how it will end for them.
item_id: fate
item_name: Fate
keywords:
    - Chronopathy
    - Psionic
    - Melee
level: "6"
name: Fate
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.talent.level-6/fate
source: mcdm.heroes.v1
target: One enemy
tier1: 8 + P psychic damage
tier2: 13 + P psychic damage
tier3: 17 + P psychic damage
type: ability
---

```ds-feature
cost: 9 Clarity
distance: Melee 2
effects:
    - effect: The target has damage weakness 5 until the end of your next turn. Whenever the target takes damage while they have this weakness, they are [knocked prone](scc:mcdm.heroes.v1/condition/prone).
    - roll: Power Roll + Presence
      tier1: 8 + P psychic damage
      tier2: 13 + P psychic damage
      tier3: 17 + P psychic damage
feature_type: ability
flavor: Your foe gets a glimpse of how it will end for them.
keywords:
    - Chronopathy
    - Psionic
    - Melee
metadata:
    action_type: Main action
    class: talent
    cost: 9 Clarity
    distance: Melee 2
    effect: The target has damage weakness 5 until the end of your next turn. Whenever the target takes damage while they have this weakness, they are [knocked prone](scc:mcdm.heroes.v1/condition/prone).
    flavor: Your foe gets a glimpse of how it will end for them.
    keywords:
        - Chronopathy
        - Psionic
        - Melee
    level: "6"
    name: Fate
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.talent.level-6/fate
    target: One enemy
    tier1: 8 + P psychic damage
    tier2: 13 + P psychic damage
    tier3: 17 + P psychic damage
    type: ability
name: Fate
target: One enemy
type: feature
usage: Main action
```
