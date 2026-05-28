---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: Ranged 5
feature_type: ability
file_basename: blade-of-the-heavens
file_dpath: feature/ability/conduit/level-6
flavor: A greatsword streams down from the sky, threatening to pin your foe.
item_id: blade-of-the-heavens
item_name: Blade of the Heavens
keywords:
    - Magic
    - Ranged
    - Strike
level: "6"
name: Blade of the Heavens
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/blade-of-the-heavens
source: mcdm.heroes.v1
target: One creature
tier1: 8 + I damage; A < WEAK, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
tier2: 12 + I damage; A < AVERAGE, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
tier3: 16 + I damage; A < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---

```ds-feature
cost: 9 Piety
distance: Ranged 5
effects:
    - roll: Power Roll + Intuition
      tier1: 8 + I damage; A < WEAK, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
      tier2: 12 + I damage; A < AVERAGE, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
      tier3: 16 + I damage; A < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
feature_type: ability
flavor: A greatsword streams down from the sky, threatening to pin your foe.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: Ranged 5
    flavor: A greatsword streams down from the sky, threatening to pin your foe.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "6"
    name: Blade of the Heavens
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/blade-of-the-heavens
    target: One creature
    tier1: 8 + I damage; A < WEAK, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
    tier2: 12 + I damage; A < AVERAGE, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
    tier3: 16 + I damage; A < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)
    type: ability
name: Blade of the Heavens
target: One creature
type: feature
usage: Main action
```
