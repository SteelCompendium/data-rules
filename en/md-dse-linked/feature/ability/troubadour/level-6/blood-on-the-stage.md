---
action_type: Main action
class: troubadour
cost: 9 Drama
cost_amount: "9"
cost_resource: Drama
distance: Melee 1
feature_type: ability
file_basename: blood-on-the-stage
file_dpath: feature/ability/troubadour/level-6
flavor: It's love and blood or drama and blood. Either way, there's always blood.
item_id: blood-on-the-stage
item_name: Blood on the Stage
keywords:
    - Melee
    - Strike
    - Weapon
level: "6"
name: Blood on the Stage
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/blood-on-the-stage
source: mcdm.heroes.v1
target: One creature or object
tier1: 12 + A damage; M < WEAK, bleeding (save ends)
tier2: 18 + A damage; M < AVERAGE, bleeding (save ends)
tier3: 24 + A damage; bleeding (EoT), or if M < STRONG, bleeding (save ends)
type: ability
---

```ds-feature
cost: 9 Drama
distance: Melee 1
effects:
    - roll: Power Roll + Agility
      tier1: 12 + A damage; M < WEAK, bleeding (save ends)
      tier2: 18 + A damage; M < AVERAGE, bleeding (save ends)
      tier3: 24 + A damage; bleeding (EoT), or if M < STRONG, bleeding (save ends)
feature_type: ability
flavor: It's love and blood or drama and blood. Either way, there's always blood.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 9 Drama
    distance: Melee 1
    flavor: It's love and blood or drama and blood. Either way, there's always blood.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "6"
    name: Blood on the Stage
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/blood-on-the-stage
    target: One creature or object
    tier1: 12 + A damage; M < WEAK, bleeding (save ends)
    tier2: 18 + A damage; M < AVERAGE, bleeding (save ends)
    tier3: 24 + A damage; bleeding (EoT), or if M < STRONG, bleeding (save ends)
    type: ability
name: Blood on the Stage
target: One creature or object
type: feature
usage: Main action
```
