---
action_type: Main action
class: "null"
distance: Melee 1
effect: You can deal damage equal to your Agility score to one creature or object adjacent to you.
feature_type: ability
file_basename: faster-than-the-eye
file_dpath: feature/ability/null/level-1
flavor: You strike so quickly that your hands become a blur.
item_id: faster-than-the-eye
item_name: Faster Than the Eye
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
level: "1"
name: Faster Than the Eye
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.null.level-1/faster-than-the-eye
source: mcdm.heroes.v1
subtype: signature
target: Two creatures or objects
tier1: 4 damage
tier2: 5 damage
tier3: 7 damage
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You can deal damage equal to your Agility score to one creature or object adjacent to you.
    - roll: Power Roll + Agility
      tier1: 4 damage
      tier2: 5 damage
      tier3: 7 damage
feature_type: ability
flavor: You strike so quickly that your hands become a blur.
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: Melee 1
    effect: You can deal damage equal to your Agility score to one creature or object adjacent to you.
    flavor: You strike so quickly that your hands become a blur.
    keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
    level: "1"
    name: Faster Than the Eye
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.null.level-1/faster-than-the-eye
    subtype: signature
    target: Two creatures or objects
    tier1: 4 damage
    tier2: 5 damage
    tier3: 7 damage
    type: ability
name: Faster Than the Eye
target: Two creatures or objects
type: feature
usage: Main action
```
