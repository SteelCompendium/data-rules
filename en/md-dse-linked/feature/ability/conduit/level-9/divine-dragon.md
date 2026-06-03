---
action_type: Main action
class: conduit
cost: 11 Piety
cost_amount: "11"
cost_resource: Piety
distance: Ranged 10
effect: You conjure a size 4 dragon that appears in an unoccupied space within distance. The dragon has speed 6 and can [fly](../../../../movement/fly.md), stability 4, 100 Stamina, immunity all to fire damage, and uses your characteristics. The dragon disappears at the end of the encounter, if their Stamina drops to 0, or if you are dying.
feature_type: ability
file_basename: divine-dragon
file_dpath: feature/ability/conduit/level-9
flavor: From nothing but divine will, you create a powerful ally.
item_id: divine-dragon
item_name: Divine Dragon
keywords:
    - Magic
    - Ranged
level: "9"
name: Divine Dragon
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-9/divine-dragon
source: mcdm.heroes.v1
target: Special
tier1: 5 fire damage
tier2: 9 fire damage
tier3: 12 fire damage
type: ability
---

```ds-feature
cost: 11 Piety
distance: Ranged 10
effects:
    - effect: You conjure a size 4 dragon that appears in an unoccupied space within distance. The dragon has speed 6 and can [fly](../../../../movement/fly.md), stability 4, 100 Stamina, immunity all to fire damage, and uses your characteristics. The dragon disappears at the end of the encounter, if their Stamina drops to 0, or if you are dying.
    - roll: Power Roll + Intuition
      tier1: 5 fire damage
      tier2: 9 fire damage
      tier3: 12 fire damage
feature_type: ability
flavor: From nothing but divine will, you create a powerful ally.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: conduit
    cost: 11 Piety
    distance: Ranged 10
    effect: You conjure a size 4 dragon that appears in an unoccupied space within distance. The dragon has speed 6 and can [fly](../../../../movement/fly.md), stability 4, 100 Stamina, immunity all to fire damage, and uses your characteristics. The dragon disappears at the end of the encounter, if their Stamina drops to 0, or if you are dying.
    flavor: From nothing but divine will, you create a powerful ally.
    keywords:
        - Magic
        - Ranged
    level: "9"
    name: Divine Dragon
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-9/divine-dragon
    target: Special
    tier1: 5 fire damage
    tier2: 9 fire damage
    tier3: 12 fire damage
    type: ability
name: Divine Dragon
target: Special
type: feature
usage: Main action
```
