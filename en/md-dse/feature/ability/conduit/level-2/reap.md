---
action_type: Maneuver
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: Ranged 10
effect: Until the start of your next turn, each time a target kills an enemy, they regain [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to 5 + your [Intuition](scc:mcdm.heroes.v1/rule.character/intuition) score.
feature_type: ability
file_basename: reap
file_dpath: feature/ability/conduit/level-2
flavor: The gods reward those who smite their foes.
item_id: reap
item_name: Reap
keywords:
    - Magic
    - Ranged
level: "2"
name: Reap
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/reap
source: mcdm.heroes.v1
target: Each ally
type: ability
---

```ds-feature
cost: 5 Piety
distance: Ranged 10
effects:
    - effect: Until the start of your next turn, each time a target kills an enemy, they regain [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to 5 + your [Intuition](scc:mcdm.heroes.v1/rule.character/intuition) score.
feature_type: ability
flavor: The gods reward those who smite their foes.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Maneuver
    class: conduit
    cost: 5 Piety
    distance: Ranged 10
    effect: Until the start of your next turn, each time a target kills an enemy, they regain [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to 5 + your [Intuition](scc:mcdm.heroes.v1/rule.character/intuition) score.
    flavor: The gods reward those who smite their foes.
    keywords:
        - Magic
        - Ranged
    level: "2"
    name: Reap
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/reap
    target: Each ally
    type: ability
name: Reap
target: Each ally
type: feature
usage: Maneuver
```
