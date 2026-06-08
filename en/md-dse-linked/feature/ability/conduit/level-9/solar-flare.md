---
action_type: Main action
class: conduit
cost: 11 Piety
cost_amount: "11"
cost_resource: Piety
distance: 5 [cube](../../../../rule/combat/cube.md) within 10
feature_type: ability
file_basename: solar-flare
file_dpath: feature/ability/conduit/level-9
flavor: You call down a sphere of fire that burns your foes to ash.
item_id: solar-flare
item_name: Solar Flare
keywords:
    - Area
    - Magic
    - Ranged
level: "9"
name: Solar Flare
scc: mcdm.heroes.v1/feature.ability.conduit.level-9/solar-flare
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 11 Piety
distance: 5 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: "\n*You call down a sphere of fire that burns your foes to ash.*\n\n| **Area, Magic, Ranged** |               **Main action** |\n|-------------------------|------------------------------:|\n| **\U0001F4CF 5 [cube](../../../../rule/combat/cube.md) within 10** | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Intuition](../../../../rule/character/intuition.md):**\n\n- **≤11:** 9 fire damage\n- **12-16:** 14 fire damage\n- **17+:** 19 fire damage"
feature_type: ability
flavor: You call down a sphere of fire that burns your foes to ash.
keywords:
    - Area
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: conduit
    cost: 11 Piety
    distance: 5 [cube](../../../../rule/combat/cube.md) within 10
    flavor: You call down a sphere of fire that burns your foes to ash.
    keywords:
        - Area
        - Magic
        - Ranged
    level: "9"
    name: Solar Flare
    scc: mcdm.heroes.v1/feature.ability.conduit.level-9/solar-flare
    target: Each enemy in the area
    type: ability
name: Solar Flare
target: Each enemy in the area
type: feature
usage: Main action
```
