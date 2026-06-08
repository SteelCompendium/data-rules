---
action_type: Main action
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: 2 burst
feature_type: ability
file_basename: shadowgrasp
file_dpath: feature/ability/shadow/level-8
flavor: The shadows around you give way, allowing the shadow creature within you to grasp at your foes.
item_id: shadowgrasp
item_name: Shadowgrasp
keywords:
    - Area
    - Magic
level: "8"
name: Shadowgrasp
scc: mcdm.heroes.v1/feature.ability.shadow.level-8/shadowgrasp
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 11 Insight
distance: 2 burst
effects:
    - effect: "\n*The shadows around you give way, allowing the shadow creature within you to grasp at your foes.*\n\n| **Area, Magic** |               **Main action** |\n|-----------------|------------------------------:|\n| **\U0001F4CF 2 burst**  | **\U0001F3AF Each enemy in the area** |\n\n**Power Roll + [Agility](../../../../rule/character/agility.md):**\n\n- **≤11:** 11 corruption damage; A < WEAK, [restrained](../../../../condition/restrained.md) (save ends)\n- **12-16:** 16 corruption damage; A < AVERAGE, [restrained](../../../../condition/restrained.md) (save ends)\n- **17+:** 21 corruption damage; A < STRONG, [restrained](../../../../condition/restrained.md) (save ends)"
feature_type: ability
flavor: The shadows around you give way, allowing the shadow creature within you to grasp at your foes.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: shadow
    cost: 11 Insight
    distance: 2 burst
    flavor: The shadows around you give way, allowing the shadow creature within you to grasp at your foes.
    keywords:
        - Area
        - Magic
    level: "8"
    name: Shadowgrasp
    scc: mcdm.heroes.v1/feature.ability.shadow.level-8/shadowgrasp
    target: Each enemy in the area
    type: ability
name: Shadowgrasp
target: Each enemy in the area
type: feature
usage: Main action
```
