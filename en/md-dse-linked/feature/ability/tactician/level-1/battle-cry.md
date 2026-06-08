---
action_type: Maneuver
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: Ranged 10
feature_type: ability
file_basename: battle-cry
file_dpath: feature/ability/tactician/level-1
flavor: You shout a phrase that galvanizes your team.
item_id: battle-cry
item_name: Battle Cry
keywords:
    - Ranged
level: "1"
name: Battle Cry
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/battle-cry
source: mcdm.heroes.v1
target: Three allies
type: ability
---

```ds-feature
cost: 3 Focus
distance: Ranged 10
effects:
    - effect: "\n*You shout a phrase that galvanizes your team.*\n\n| **Ranged**       |        **Maneuver** |\n|------------------|--------------------:|\n| **\U0001F4CF Ranged 10** | **\U0001F3AF Three allies** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Reason](../../../../rule/character/reason.md):**\n\n- **≤11:** Each target gains 1 [surge](../../../../rule/resource/surge.md).\n- **12-16:** Each target gains 2 [surges](../../../../rule/resource/surge.md).\n- **17+:** Each target gains 3 [surges](../../../../rule/resource/surge.md)."
feature_type: ability
flavor: You shout a phrase that galvanizes your team.
keywords:
    - Ranged
metadata:
    action_type: Maneuver
    class: tactician
    cost: 3 Focus
    distance: Ranged 10
    flavor: You shout a phrase that galvanizes your team.
    keywords:
        - Ranged
    level: "1"
    name: Battle Cry
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/battle-cry
    target: Three allies
    type: ability
name: Battle Cry
target: Three allies
type: feature
usage: Maneuver
```
