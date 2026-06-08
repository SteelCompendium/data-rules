---
action_type: Main action
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: inspiring-strike
file_dpath: feature/ability/tactician/level-1
flavor: Your attack gives an ally hope.
item_id: inspiring-strike
item_name: Inspiring Strike
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "1"
name: Inspiring Strike
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/inspiring-strike
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries)
tier2: 5 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries)
tier3: 8 + M damage; you and one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries), and each of you gains an edge on the next ability roll you make during the encounter
type: ability
---

```ds-feature
cost: 3 Focus
distance: Melee 1 or ranged 5
effects:
    - roll: Power Roll + Might
      tier1: 3 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries)
      tier2: 5 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries)
      tier3: 8 + M damage; you and one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries), and each of you gains an edge on the next ability roll you make during the encounter
feature_type: ability
flavor: Your attack gives an ally hope.
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 3 Focus
    distance: Melee 1 or ranged 5
    flavor: Your attack gives an ally hope.
    keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "1"
    name: Inspiring Strike
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/inspiring-strike
    target: One creature or object
    tier1: 3 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries)
    tier2: 5 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries)
    tier3: 8 + M damage; you and one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries), and each of you gains an edge on the next ability roll you make during the encounter
    type: ability
name: Inspiring Strike
target: One creature or object
type: feature
usage: Main action
```
