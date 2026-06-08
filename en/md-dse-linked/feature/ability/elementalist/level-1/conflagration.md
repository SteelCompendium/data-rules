---
action_type: Main action
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
feature_type: ability
file_basename: conflagration
file_dpath: feature/ability/elementalist/level-1
flavor: A storm of fire descends upon your enemies.
item_id: conflagration
item_name: Conflagration
keywords:
    - Area
    - Fire
    - Magic
    - Ranged
level: "1"
name: Conflagration
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/conflagration
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 5 Essence
distance: 3 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: "\n*A storm of fire descends upon your enemies.*\n\n| **Area, Fire, Magic, Ranged** |               **Main action** |\n|-------------------------------|------------------------------:|\n| **\U0001F4CF 3 [cube](../../../../rule/combat/cube.md) within 10**       | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Reason](../../../../rule/character/reason.md):**\n\n- **≤11:** 4 fire damage\n- **12-16:** 6 fire damage\n- **17+:** 10 fire damage\n\n**Persistent 2:** At the start of your turn, you can use a maneuver to use this ability again without spending essence."
feature_type: ability
flavor: A storm of fire descends upon your enemies.
keywords:
    - Area
    - Fire
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: elementalist
    cost: 5 Essence
    distance: 3 [cube](../../../../rule/combat/cube.md) within 10
    flavor: A storm of fire descends upon your enemies.
    keywords:
        - Area
        - Fire
        - Magic
        - Ranged
    level: "1"
    name: Conflagration
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/conflagration
    target: Each enemy in the area
    type: ability
name: Conflagration
target: Each enemy in the area
type: feature
usage: Main action
```
