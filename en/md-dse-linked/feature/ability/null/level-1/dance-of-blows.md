---
action_type: Main action
class: "null"
distance: 1 burst
effect: You can slide one adjacent enemy up to a number of squares equal to your Intuition score.
feature_type: ability
file_basename: dance-of-blows
file_dpath: feature/ability/null/level-1
flavor: You strike everywhere at once, tricking an enemy into moving out of position.
item_id: dance-of-blows
item_name: Dance of Blows
keywords:
    - Area
    - Psionic
    - Weapon
level: "1"
name: Dance of Blows
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.null.level-1/dance-of-blows
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 3 damage
tier2: 4 damage
tier3: 5 damage
type: ability
---

```ds-feature
distance: 1 burst
effects:
    - effect: You can slide one adjacent enemy up to a number of squares equal to your Intuition score.
    - roll: Power Roll + Agility
      tier1: 3 damage
      tier2: 4 damage
      tier3: 5 damage
feature_type: ability
flavor: You strike everywhere at once, tricking an enemy into moving out of position.
keywords:
    - Area
    - Psionic
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: 1 burst
    effect: You can slide one adjacent enemy up to a number of squares equal to your Intuition score.
    flavor: You strike everywhere at once, tricking an enemy into moving out of position.
    keywords:
        - Area
        - Psionic
        - Weapon
    level: "1"
    name: Dance of Blows
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.null.level-1/dance-of-blows
    subtype: signature
    target: Each enemy in the area
    tier1: 3 damage
    tier2: 4 damage
    tier3: 5 damage
    type: ability
name: Dance of Blows
target: Each enemy in the area
type: feature
usage: Main action
```
