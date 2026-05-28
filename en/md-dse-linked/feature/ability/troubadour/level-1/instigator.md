---
action_type: Main action
class: troubadour
distance: Melee 1
effect: The target is [taunted](scc:mcdm.heroes.v1/condition/taunted) by you or a willing ally adjacent to you until the end of the target's next turn.
feature_type: ability
file_basename: instigator
file_dpath: feature/ability/troubadour/level-1
flavor: I didn't do it! What?
item_id: instigator
item_name: Instigator
keywords:
    - Melee
    - Strike
    - Weapon
level: "1"
name: Instigator
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/instigator
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + P damage
tier2: 6 + P damage
tier3: 9 + P damage
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target is [taunted](scc:mcdm.heroes.v1/condition/taunted) by you or a willing ally adjacent to you until the end of the target's next turn.
    - roll: Power Roll + Presence
      tier1: 3 + P damage
      tier2: 6 + P damage
      tier3: 9 + P damage
feature_type: ability
flavor: I didn't do it! What?
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    distance: Melee 1
    effect: The target is [taunted](scc:mcdm.heroes.v1/condition/taunted) by you or a willing ally adjacent to you until the end of the target's next turn.
    flavor: I didn't do it! What?
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Instigator
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/instigator
    subtype: signature
    target: One creature
    tier1: 3 + P damage
    tier2: 6 + P damage
    tier3: 9 + P damage
    type: ability
name: Instigator
target: One creature
type: feature
usage: Main action
```
