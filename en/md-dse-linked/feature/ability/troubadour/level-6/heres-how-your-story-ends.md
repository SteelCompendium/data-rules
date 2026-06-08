---
action_type: Main action
class: troubadour
cost: 9 Drama
cost_amount: "9"
cost_resource: Drama
distance: 5 burst
feature_type: ability
file_basename: heres-how-your-story-ends
file_dpath: feature/ability/troubadour/level-6
flavor: You give away the ending of this battle, and it's not great for them.
item_id: heres-how-your-story-ends
item_name: Here's How Your Story Ends
keywords:
    - Area
    - Magic
level: "6"
name: Here's How Your Story Ends
scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/heres-how-your-story-ends
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 9 Drama
distance: 5 burst
effects:
    - effect: "\n*You give away the ending of this battle, and it's not great for them.*\n\n| **Area, Magic** |               **Main action** |\n|-----------------|------------------------------:|\n| **\U0001F4CF 5 burst**  | **\U0001F3AF Each enemy in the area** |\n\n**Power Roll + [Presence](../../../../rule/character/presence.md):**\n\n- **≤11:** 2 psychic damage; P < WEAK, [frightened](../../../../condition/frightened.md) (save ends)\n- **12-16:** 5 psychic damage; P < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)\n- **17+:** 7 psychic damage; P < STRONG, [frightened](../../../../condition/frightened.md) (save ends)"
feature_type: ability
flavor: You give away the ending of this battle, and it's not great for them.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: troubadour
    cost: 9 Drama
    distance: 5 burst
    flavor: You give away the ending of this battle, and it's not great for them.
    keywords:
        - Area
        - Magic
    level: "6"
    name: Here's How Your Story Ends
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/heres-how-your-story-ends
    target: Each enemy in the area
    type: ability
name: Here's How Your Story Ends
target: Each enemy in the area
type: feature
usage: Main action
```
