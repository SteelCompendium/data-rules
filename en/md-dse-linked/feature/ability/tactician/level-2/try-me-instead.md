---
action_type: Main action
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: Self; see below
effect: You shift up to your speed directly toward an ally, ending adjacent to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a Recovery, and you can make the following weapon strike with a distance of melee 1 against a creature.
feature_type: ability
file_basename: try-me-instead
file_dpath: feature/ability/tactician/level-2
flavor: '"Try picking on someone my size."'
item_id: try-me-instead
item_name: Try Me Instead
keywords:
    - Melee
    - Strike
    - Weapon
level: "2"
name: Try Me Instead
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/try-me-instead
source: mcdm.heroes.v1
target: Self
tier1: 2 + R damage; R < WEAK, frightened (save ends)
tier2: 3 + R damage; R < AVERAGE, frightened (save ends)
tier3: 4 + R damage; R < STRONG, frightened (save ends)
type: ability
---

```ds-feature
cost: 5 Focus
distance: Self; see below
effects:
    - effect: You shift up to your speed directly toward an ally, ending adjacent to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a Recovery, and you can make the following weapon strike with a distance of melee 1 against a creature.
    - roll: Power Roll + Reason
      tier1: 2 + R damage; R < WEAK, frightened (save ends)
      tier2: 3 + R damage; R < AVERAGE, frightened (save ends)
      tier3: 4 + R damage; R < STRONG, frightened (save ends)
feature_type: ability
flavor: '"Try picking on someone my size."'
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 5 Focus
    distance: Self; see below
    effect: You shift up to your speed directly toward an ally, ending adjacent to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a Recovery, and you can make the following weapon strike with a distance of melee 1 against a creature.
    flavor: '"Try picking on someone my size."'
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "2"
    name: Try Me Instead
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/try-me-instead
    target: Self
    tier1: 2 + R damage; R < WEAK, frightened (save ends)
    tier2: 3 + R damage; R < AVERAGE, frightened (save ends)
    tier3: 4 + R damage; R < STRONG, frightened (save ends)
    type: ability
name: Try Me Instead
target: Self
type: feature
usage: Main action
```
