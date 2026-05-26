---
action_type: Main action
class: shadow
cost: 9 Insight
cost_amount: "9"
cost_resource: Insight
distance: Melee 1
effect: You and the target are removed from the encounter map until the start of your next turn. You reappear in the spaces you left or the nearest unoccupied spaces. Make a power roll upon your return.
feature_type: ability
file_basename: into-the-shadows-scc-mcdm-heroes-v1-class-shadow
file_dpath: feature/ability/shadow/level-5
flavor: You sweep your foe off their feet and plunge them into absolute darkness.
item_id: into-the-shadows-scc-mcdm-heroes-v1-class-shadow
item_name: Into the [Shadows](scc:mcdm.heroes.v1/class/shadow)
keywords:
    - Magic
    - Melee
    - Strike
    - Weapon
level: "5"
name: Into the [Shadows](scc:mcdm.heroes.v1/class/shadow)
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-5/into-the-shadows-scc-mcdm-heroes-v1-class-shadow
source: mcdm.heroes.v1
target: One creature or object
tier1: 8 + A corruption damage
tier2: 13 + A corruption damage
tier3: 17 + A corruption damage
type: ability
---

```ds-feature
cost: 9 Insight
distance: Melee 1
effects:
    - effect: You and the target are removed from the encounter map until the start of your next turn. You reappear in the spaces you left or the nearest unoccupied spaces. Make a power roll upon your return.
    - roll: Power Roll + Agility
      tier1: 8 + A corruption damage
      tier2: 13 + A corruption damage
      tier3: 17 + A corruption damage
feature_type: ability
flavor: You sweep your foe off their feet and plunge them into absolute darkness.
keywords:
    - Magic
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 9 Insight
    distance: Melee 1
    effect: You and the target are removed from the encounter map until the start of your next turn. You reappear in the spaces you left or the nearest unoccupied spaces. Make a power roll upon your return.
    flavor: You sweep your foe off their feet and plunge them into absolute darkness.
    keywords:
        - Magic
        - Melee
        - Strike
        - Weapon
    level: "5"
    name: Into the [Shadows](scc:mcdm.heroes.v1/class/shadow)
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-5/into-the-shadows-scc-mcdm-heroes-v1-class-shadow
    target: One creature or object
    tier1: 8 + A corruption damage
    tier2: 13 + A corruption damage
    tier3: 17 + A corruption damage
    type: ability
name: Into the [Shadows](scc:mcdm.heroes.v1/class/shadow)
target: One creature or object
type: feature
usage: Main action
```
