---
action_type: Main action
class: "null"
distance: Melee 1
feature_type: ability
file_basename: joint-lock
file_dpath: feature/ability/null/level-1
flavor: You contort your enemy's body into a stance they struggle to escape from.
item_id: joint-lock
item_name: Joint Lock
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
level: "1"
name: Joint Lock
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.null.level-1/joint-lock
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 4 + A damage; A < WEAK, grabbed
tier2: 7 + A damage; A < AVERAGE, grabbed
tier3: 9 + A damage; A < STRONG, grabbed
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - roll: Power Roll + Agility
      tier1: 4 + A damage; A < WEAK, grabbed
      tier2: 7 + A damage; A < AVERAGE, grabbed
      tier3: 9 + A damage; A < STRONG, grabbed
feature_type: ability
flavor: You contort your enemy's body into a stance they struggle to escape from.
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: Melee 1
    flavor: You contort your enemy's body into a stance they struggle to escape from.
    keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
    level: "1"
    name: Joint Lock
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.null.level-1/joint-lock
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage; A < WEAK, grabbed
    tier2: 7 + A damage; A < AVERAGE, grabbed
    tier3: 9 + A damage; A < STRONG, grabbed
    type: ability
name: Joint Lock
target: One creature or object
type: feature
usage: Main action
```
