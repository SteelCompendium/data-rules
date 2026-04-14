---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: Ranged 10
feature_type: ability
file_basename: curse-of-terror
file_dpath: feature/ability/conduit/level-1
flavor: Fear of divine judgment overwhelms your foe.
item_id: curse-of-terror
item_name: Curse of Terror
keywords:
    - Magic
    - Ranged
    - Strike
level: "1"
name: Curse of Terror
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/curse-of-terror
source: mcdm.heroes.v1
target: One creature
tier1: 6 + I holy damage; I < WEAK, frightened (save ends)
tier2: 9 + I holy damage; I < AVERAGE, frightened (save ends)
tier3: 13 + I holy damage; I < STRONG, frightened (save ends)
type: ability
---

```ds-feature
cost: 5 Piety
distance: Ranged 10
effects:
    - roll: Power Roll + Intuition
      tier1: 6 + I holy damage; I < WEAK, frightened (save ends)
      tier2: 9 + I holy damage; I < AVERAGE, frightened (save ends)
      tier3: 13 + I holy damage; I < STRONG, frightened (save ends)
feature_type: ability
flavor: Fear of divine judgment overwhelms your foe.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: Ranged 10
    flavor: Fear of divine judgment overwhelms your foe.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "1"
    name: Curse of Terror
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/curse-of-terror
    target: One creature
    tier1: 6 + I holy damage; I < WEAK, frightened (save ends)
    tier2: 9 + I holy damage; I < AVERAGE, frightened (save ends)
    tier3: 13 + I holy damage; I < STRONG, frightened (save ends)
    type: ability
name: Curse of Terror
target: One creature
type: feature
usage: Main action
```
