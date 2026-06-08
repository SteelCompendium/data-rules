---
action_type: Main action
class: troubadour
cost: 9 Drama
cost_amount: "9"
cost_resource: Drama
distance: 3 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
effect: Unless you score a [critical hit](scc:mcdm.heroes.v1/rule.combat/critical-hit), this ability can't reduce a non-minion target below 1 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).
feature_type: ability
file_basename: action-hero
file_dpath: feature/ability/troubadour/level-5
flavor: You wield your weapon at blistering [speed](scc:mcdm.heroes.v1/rule.character/speed), leaving everyone around you fighting for their lives.
item_id: action-hero
item_name: Action Hero
keywords:
    - Area
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "5"
name: Action Hero
scc: mcdm.heroes.v1/feature.ability.troubadour.level-5/action-hero
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 9 Drama
distance: 3 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Unless you score a [critical hit](scc:mcdm.heroes.v1/rule.combat/critical-hit), this ability can't reduce a non-minion target below 1 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).
feature_type: ability
flavor: You wield your weapon at blistering [speed](scc:mcdm.heroes.v1/rule.character/speed), leaving everyone around you fighting for their lives.
keywords:
    - Area
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 9 Drama
    distance: 3 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
    effect: Unless you score a [critical hit](scc:mcdm.heroes.v1/rule.combat/critical-hit), this ability can't reduce a non-minion target below 1 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina).
    flavor: You wield your weapon at blistering [speed](scc:mcdm.heroes.v1/rule.character/speed), leaving everyone around you fighting for their lives.
    keywords:
        - Area
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "5"
    name: Action Hero
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-5/action-hero
    target: Each enemy in the area
    type: ability
name: Action Hero
target: Each enemy in the area
type: feature
usage: Main action
```
