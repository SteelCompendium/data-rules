---
action_type: Main action
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: Ranged 5
effect: One ally adjacent to the target can spend a Recovery.
feature_type: ability
file_basename: ive-got-your-back
file_dpath: feature/ability/tactician/level-2
flavor: Your enemy will think twice about attacking your friend.
item_id: ive-got-your-back
item_name: I've Got Your Back
keywords:
    - Ranged
    - Strike
    - Weapon
level: "2"
name: I've Got Your Back
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/ive-got-your-back
source: mcdm.heroes.v1
target: One creature
tier1: 5 + R damage; taunted (EoT)
tier2: 9 + R damage; taunted (EoT)
tier3: 12 + R damage; taunted (EoT)
type: ability
---

```ds-feature
cost: 5 Focus
distance: Ranged 5
effects:
    - effect: One ally adjacent to the target can spend a Recovery.
    - roll: Power Roll + Reason
      tier1: 5 + R damage; taunted (EoT)
      tier2: 9 + R damage; taunted (EoT)
      tier3: 12 + R damage; taunted (EoT)
feature_type: ability
flavor: Your enemy will think twice about attacking your friend.
keywords:
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 5 Focus
    distance: Ranged 5
    effect: One ally adjacent to the target can spend a Recovery.
    flavor: Your enemy will think twice about attacking your friend.
    keywords:
        - Ranged
        - Strike
        - Weapon
    level: "2"
    name: I've Got Your Back
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/ive-got-your-back
    target: One creature
    tier1: 5 + R damage; taunted (EoT)
    tier2: 9 + R damage; taunted (EoT)
    tier3: 12 + R damage; taunted (EoT)
    type: ability
name: I've Got Your Back
target: One creature
type: feature
usage: Main action
```
