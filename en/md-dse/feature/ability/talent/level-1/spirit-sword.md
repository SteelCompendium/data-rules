---
action_type: Main action
class: talent
distance: Melee 2
effect: You gain 1 surge.
feature_type: ability
file_basename: spirit-sword
file_dpath: feature/ability/talent/level-1
flavor: You form a blade of mind energy and stab your target, invigorating yourself.
item_id: spirit-sword
item_name: Spirit Sword
keywords:
    - Animapathy
    - Melee
    - Psionic
    - Strike
level: "1"
name: Spirit Sword
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.talent.level-1/spirit-sword
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + P damage
tier2: 6 + P damage
tier3: 9 + P damage
type: ability
---

```ds-feature
distance: Melee 2
effects:
    - effect: You gain 1 surge.
    - roll: Power Roll + Presence
      tier1: 3 + P damage
      tier2: 6 + P damage
      tier3: 9 + P damage
feature_type: ability
flavor: You form a blade of mind energy and stab your target, invigorating yourself.
keywords:
    - Animapathy
    - Melee
    - Psionic
    - Strike
metadata:
    action_type: Main action
    class: talent
    distance: Melee 2
    effect: You gain 1 surge.
    flavor: You form a blade of mind energy and stab your target, invigorating yourself.
    keywords:
        - Animapathy
        - Melee
        - Psionic
        - Strike
    level: "1"
    name: Spirit Sword
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/spirit-sword
    subtype: signature
    target: One creature or object
    tier1: 3 + P damage
    tier2: 6 + P damage
    tier3: 9 + P damage
    type: ability
name: Spirit Sword
target: One creature or object
type: feature
usage: Main action
```
