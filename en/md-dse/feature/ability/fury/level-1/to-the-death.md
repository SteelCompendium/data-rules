---
action_type: Main action
class: fury
distance: Melee 1
effect: You gain 2 [surges](scc:mcdm.heroes.v1/rule.resource/surge), and the target can make an opportunity attack against you as a free triggered action.
feature_type: ability
file_basename: to-the-death
file_dpath: feature/ability/fury/level-1
flavor: Your reckless assault leaves you tactically vulnerable.
item_id: to-the-death
item_name: To the Death!
keywords:
    - Melee
    - Strike
    - Weapon
level: "1"
name: To the Death!
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-1/to-the-death
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + M damage
tier2: 6 + M damage
tier3: 9 + M damage
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You gain 2 [surges](scc:mcdm.heroes.v1/rule.resource/surge), and the target can make an opportunity attack against you as a free triggered action.
    - roll: Power Roll + Might
      tier1: 3 + M damage
      tier2: 6 + M damage
      tier3: 9 + M damage
feature_type: ability
flavor: Your reckless assault leaves you tactically vulnerable.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: fury
    distance: Melee 1
    effect: You gain 2 [surges](scc:mcdm.heroes.v1/rule.resource/surge), and the target can make an opportunity attack against you as a free triggered action.
    flavor: Your reckless assault leaves you tactically vulnerable.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: To the Death!
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/to-the-death
    subtype: signature
    target: One creature or object
    tier1: 3 + M damage
    tier2: 6 + M damage
    tier3: 9 + M damage
    type: ability
name: To the Death!
target: One creature or object
type: feature
usage: Main action
```
