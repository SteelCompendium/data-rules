---
action_type: Main action
class: "null"
cost: 9 Discipline
cost_amount: "9"
cost_resource: Discipline
distance: Melee 1
effect: While [grabbed](scc:mcdm.heroes.v1/condition/grabbed) this way, the target takes a bane on the [Escape Grab](scc:mcdm.heroes.v1/feature.trait.common.maneuvers/escape-grab) maneuver. Each time they use that maneuver, they take damage equal to twice your Agility score.
feature_type: ability
file_basename: iron-grip
file_dpath: feature/ability/null/level-5
flavor: You grab the target with supernatural force.
item_id: iron-grip
item_name: Iron Grip
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
level: "5"
name: Iron Grip
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.null.level-5/iron-grip
source: mcdm.heroes.v1
target: One creature
tier1: 10 + A damage; A < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
tier2: 14 + A damage; A < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
tier3: 18 + A damage; A < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
type: ability
---

```ds-feature
cost: 9 Discipline
distance: Melee 1
effects:
    - effect: While [grabbed](scc:mcdm.heroes.v1/condition/grabbed) this way, the target takes a bane on the [Escape Grab](scc:mcdm.heroes.v1/feature.trait.common.maneuvers/escape-grab) maneuver. Each time they use that maneuver, they take damage equal to twice your Agility score.
    - roll: Power Roll + Agility
      tier1: 10 + A damage; A < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
      tier2: 14 + A damage; A < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
      tier3: 18 + A damage; A < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
feature_type: ability
flavor: You grab the target with supernatural force.
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 9 Discipline
    distance: Melee 1
    effect: While [grabbed](scc:mcdm.heroes.v1/condition/grabbed) this way, the target takes a bane on the [Escape Grab](scc:mcdm.heroes.v1/feature.trait.common.maneuvers/escape-grab) maneuver. Each time they use that maneuver, they take damage equal to twice your Agility score.
    flavor: You grab the target with supernatural force.
    keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
    level: "5"
    name: Iron Grip
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.null.level-5/iron-grip
    target: One creature
    tier1: 10 + A damage; A < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
    tier2: 14 + A damage; A < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
    tier3: 18 + A damage; A < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
    type: ability
name: Iron Grip
target: One creature
type: feature
usage: Main action
```
