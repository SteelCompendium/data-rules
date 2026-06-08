---
action_type: Main action
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: 3 burst
feature_type: ability
file_basename: begone
file_dpath: feature/ability/censor/level-6
flavor: You terrify your enemies into retreating, creating chaos in their ranks.
item_id: begone
item_name: Begone!
keywords:
    - Area
    - Magic
level: "6"
name: Begone!
scc: mcdm.heroes.v1/feature.ability.censor.level-6/begone
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 9 Wrath
distance: 3 burst
effects:
    - effect: "\n*You terrify your enemies into retreating, creating chaos in their ranks.*\n\n| **Area, Magic** |               **Main action** |\n|-----------------|------------------------------:|\n| **\U0001F4CF 3 burst**  | **\U0001F3AF Each enemy in the area** |\n\n**Power Roll + [Presence](../../../../rule/character/presence.md):**\n\n- **≤11:** 4 psychic damage; slide 3\n- **12-16:** 6 psychic damage; slide 5\n- **17+:** 8 psychic damage; slide 7"
feature_type: ability
flavor: You terrify your enemies into retreating, creating chaos in their ranks.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: censor
    cost: 9 Wrath
    distance: 3 burst
    flavor: You terrify your enemies into retreating, creating chaos in their ranks.
    keywords:
        - Area
        - Magic
    level: "6"
    name: Begone!
    scc: mcdm.heroes.v1/feature.ability.censor.level-6/begone
    target: Each enemy in the area
    type: ability
name: Begone!
target: Each enemy in the area
type: feature
usage: Main action
```
