---
action_type: Main action
class: conduit
cost: 3 Piety
cost_amount: "3"
cost_resource: Piety
distance: Ranged 10
feature_type: ability
file_basename: judgments-hammer
file_dpath: feature/ability/conduit/level-1
flavor: Your divine [fury](scc:mcdm.heroes.v1/class/fury) is a hammer that crashes down upon the unrighteous.
item_id: judgments-hammer
item_name: Judgment's Hammer
keywords:
    - Magic
    - Ranged
    - Strike
level: "1"
name: Judgment's Hammer
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/judgments-hammer
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + I holy damage; A < WEAK, prone
tier2: 6 + I holy damage; A < AVERAGE, prone
tier3: 9 + I holy damage; A < STRONG, prone and can't stand (save ends)
type: ability
---

```ds-feature
cost: 3 Piety
distance: Ranged 10
effects:
    - roll: Power Roll + Intuition
      tier1: 3 + I holy damage; A < WEAK, prone
      tier2: 6 + I holy damage; A < AVERAGE, prone
      tier3: 9 + I holy damage; A < STRONG, prone and can't stand (save ends)
feature_type: ability
flavor: Your divine [fury](scc:mcdm.heroes.v1/class/fury) is a hammer that crashes down upon the unrighteous.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    cost: 3 Piety
    distance: Ranged 10
    flavor: Your divine [fury](scc:mcdm.heroes.v1/class/fury) is a hammer that crashes down upon the unrighteous.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "1"
    name: Judgment's Hammer
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/judgments-hammer
    target: One creature or object
    tier1: 3 + I holy damage; A < WEAK, prone
    tier2: 6 + I holy damage; A < AVERAGE, prone
    tier3: 9 + I holy damage; A < STRONG, prone and can't stand (save ends)
    type: ability
name: Judgment's Hammer
target: One creature or object
type: feature
usage: Main action
```
