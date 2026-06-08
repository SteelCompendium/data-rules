---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: 4 burst
feature_type: ability
file_basename: invocation-of-undoing
file_dpath: feature/ability/conduit/level-6
flavor: You utter a secret word of destruction known only to deities.
item_id: invocation-of-undoing
item_name: Invocation of Undoing
keywords:
    - Area
    - Magic
level: "6"
name: Invocation of Undoing
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/invocation-of-undoing
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 9 Piety
distance: 4 burst
effects:
    - effect: "\n*You utter a secret word of destruction known only to deities.*\n\n| **Area, Magic**  |               **Main action** |\n|------------------|------------------------------:|\n| **\U0001F4CF 4 burst**   | **\U0001F3AF Each enemy in the area** |\n\n**Power Roll + [Intuition](../../../../rule/character/intuition.md):**\n\n- **≤11:** 3 sonic damage; push 3\n- **12-16:** 6 sonic damage; push 5\n- **17+:** 9 sonic damage; push 7\n\n**Special:** You can choose to have this ability deal damage to and push objects, and to deal damage to buildings."
feature_type: ability
flavor: You utter a secret word of destruction known only to deities.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: 4 burst
    flavor: You utter a secret word of destruction known only to deities.
    keywords:
        - Area
        - Magic
    level: "6"
    name: Invocation of Undoing
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/invocation-of-undoing
    target: Each enemy in the area
    type: ability
name: Invocation of Undoing
target: Each enemy in the area
type: feature
usage: Main action
```
