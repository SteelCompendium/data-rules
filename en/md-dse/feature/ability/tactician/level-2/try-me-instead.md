---
action_type: Main action
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: Self; see below
effect: You [shift](scc:mcdm.heroes.v1/movement/shifting) up to your [speed](scc:mcdm.heroes.v1/rule.character/speed) directly toward an ally, ending adjacent to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries), and you can make the following weapon [strike](scc:mcdm.heroes.v1/rule.combat/strike) with a [distance](scc:mcdm.heroes.v1/rule.combat/distance) of melee 1 against a creature.
feature_type: ability
file_basename: try-me-instead
file_dpath: feature/ability/tactician/level-2
flavor: '"Try picking on someone my [size](scc:mcdm.heroes.v1/rule.character/size)."'
item_id: try-me-instead
item_name: Try Me Instead
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: Try Me Instead
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/try-me-instead
source: mcdm.heroes.v1
target: Self
type: ability
---

```ds-feature
cost: 5 Focus
distance: Self; see below
effects:
    - effect: You [shift](scc:mcdm.heroes.v1/movement/shifting) up to your [speed](scc:mcdm.heroes.v1/rule.character/speed) directly toward an ally, ending adjacent to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries), and you can make the following weapon [strike](scc:mcdm.heroes.v1/rule.combat/strike) with a [distance](scc:mcdm.heroes.v1/rule.combat/distance) of melee 1 against a creature.
feature_type: ability
flavor: '"Try picking on someone my [size](scc:mcdm.heroes.v1/rule.character/size)."'
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 5 Focus
    distance: Self; see below
    effect: You [shift](scc:mcdm.heroes.v1/movement/shifting) up to your [speed](scc:mcdm.heroes.v1/rule.character/speed) directly toward an ally, ending adjacent to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries), and you can make the following weapon [strike](scc:mcdm.heroes.v1/rule.combat/strike) with a [distance](scc:mcdm.heroes.v1/rule.combat/distance) of melee 1 against a creature.
    flavor: '"Try picking on someone my [size](scc:mcdm.heroes.v1/rule.character/size)."'
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: Try Me Instead
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/try-me-instead
    target: Self
    type: ability
name: Try Me Instead
target: Self
type: feature
usage: Main action
```
