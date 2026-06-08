---
action_type: Maneuver
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: battle-cry
file_dpath: feature/ability/tactician/level-1
flavor: You shout a phrase that galvanizes your team.
item_id: battle-cry
item_name: Battle Cry
keywords:
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Battle Cry
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/battle-cry
source: mcdm.heroes.v1
target: Three allies
type: ability
---

```ds-feature
cost: 3 Focus
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: "\n*You shout a phrase that galvanizes your team.*\n\n| **[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)**       |        **Maneuver** |\n|------------------|--------------------:|\n| **\U0001F4CF [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10** | **\U0001F3AF Three allies** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**\n\n- **≤11:** Each target gains 1 [surge](scc:mcdm.heroes.v1/rule.resource/surge).\n- **12-16:** Each target gains 2 [surges](scc:mcdm.heroes.v1/rule.resource/surge).\n- **17+:** Each target gains 3 [surges](scc:mcdm.heroes.v1/rule.resource/surge)."
feature_type: ability
flavor: You shout a phrase that galvanizes your team.
keywords:
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Maneuver
    class: tactician
    cost: 3 Focus
    distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You shout a phrase that galvanizes your team.
    keywords:
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
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
