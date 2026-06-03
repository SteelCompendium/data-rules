---
action_type: Main action
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: Melee 3
effect: This ability can't obtain better than a tier 2 outcome unless the target is at maximum distance. If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 surges that you can use immediately.
feature_type: ability
file_basename: expert-fencer
file_dpath: feature/ability/troubadour/level-9
flavor: If you can land the strike, the crowd goes wild.
item_id: expert-fencer
item_name: Expert Fencer
keywords:
    - Charge
    - Melee
    - Strike
    - Weapon
level: "9"
name: Expert Fencer
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/expert-fencer
source: mcdm.heroes.v1
target: One creature or object
tier1: 15 + A damage
tier2: 21 + A damage
tier3: 28 + A damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Drama
distance: Melee 3
effects:
    - effect: This ability can't obtain better than a tier 2 outcome unless the target is at maximum distance. If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 surges that you can use immediately.
    - roll: Power Roll + Agility
      tier1: 15 + A damage
      tier2: 21 + A damage
      tier3: 28 + A damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
feature_type: ability
flavor: If you can land the strike, the crowd goes wild.
keywords:
    - Charge
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 11 Drama
    distance: Melee 3
    effect: This ability can't obtain better than a tier 2 outcome unless the target is at maximum distance. If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 surges that you can use immediately.
    flavor: If you can land the strike, the crowd goes wild.
    keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
    level: "9"
    name: Expert Fencer
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/expert-fencer
    target: One creature or object
    tier1: 15 + A damage
    tier2: 21 + A damage
    tier3: 28 + A damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    type: ability
name: Expert Fencer
target: One creature or object
type: feature
usage: Main action
```
