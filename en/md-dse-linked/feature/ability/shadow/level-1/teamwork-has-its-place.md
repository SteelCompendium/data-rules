---
action_type: Main action
class: shadow
distance: Melee 1 or ranged 5
effect: If any ally is adjacent to the target, you gain 1 [surge](../../../../rule/resource/surge.md) before making the power roll.
feature_type: ability
file_basename: teamwork-has-its-place
file_dpath: feature/ability/shadow/level-1
flavor: You attack an enemy as an ally exposes their weakness.
item_id: teamwork-has-its-place
item_name: Teamwork Has Its Place
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "1"
name: Teamwork Has Its Place
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/teamwork-has-its-place
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + A damage
tier2: 6 + A damage
tier3: 9 + A damage
type: ability
---

```ds-feature
distance: Melee 1 or ranged 5
effects:
    - effect: If any ally is adjacent to the target, you gain 1 [surge](../../../../rule/resource/surge.md) before making the power roll.
    - roll: Power Roll + Agility
      tier1: 3 + A damage
      tier2: 6 + A damage
      tier3: 9 + A damage
feature_type: ability
flavor: You attack an enemy as an ally exposes their weakness.
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    distance: Melee 1 or ranged 5
    effect: If any ally is adjacent to the target, you gain 1 [surge](../../../../rule/resource/surge.md) before making the power roll.
    flavor: You attack an enemy as an ally exposes their weakness.
    keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "1"
    name: Teamwork Has Its Place
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/teamwork-has-its-place
    subtype: signature
    target: One creature or object
    tier1: 3 + A damage
    tier2: 6 + A damage
    tier3: 9 + A damage
    type: ability
name: Teamwork Has Its Place
target: One creature or object
type: feature
usage: Main action
```
