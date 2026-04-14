---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: Ranged 10
feature_type: ability
file_basename: corruptions-curse
file_dpath: feature/ability/conduit/level-1
flavor: Cursed by you, your enemy takes more damage from your allies.
item_id: corruptions-curse
item_name: Corruption's Curse
keywords:
    - Magic
    - Ranged
    - Strike
level: "1"
name: Corruption's Curse
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/corruptions-curse
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + I corruption damage; M < WEAK, damage weakness 5 (save ends)
tier2: 6 + I corruption damage; M < AVERAGE, damage weakness 5 (save ends)
tier3: 9 + I corruption damage; M < STRONG, damage weakness 5 (save ends)
type: ability
---

```ds-feature
cost: 5 Piety
distance: Ranged 10
effects:
    - roll: Power Roll + Intuition
      tier1: 3 + I corruption damage; M < WEAK, damage weakness 5 (save ends)
      tier2: 6 + I corruption damage; M < AVERAGE, damage weakness 5 (save ends)
      tier3: 9 + I corruption damage; M < STRONG, damage weakness 5 (save ends)
feature_type: ability
flavor: Cursed by you, your enemy takes more damage from your allies.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: Ranged 10
    flavor: Cursed by you, your enemy takes more damage from your allies.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "1"
    name: Corruption's Curse
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/corruptions-curse
    target: One creature or object
    tier1: 3 + I corruption damage; M < WEAK, damage weakness 5 (save ends)
    tier2: 6 + I corruption damage; M < AVERAGE, damage weakness 5 (save ends)
    tier3: 9 + I corruption damage; M < STRONG, damage weakness 5 (save ends)
    type: ability
name: Corruption's Curse
target: One creature or object
type: feature
usage: Main action
```
