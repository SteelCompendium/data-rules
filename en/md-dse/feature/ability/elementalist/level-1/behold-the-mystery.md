---
action_type: Main action
class: elementalist
cost: 3 Essence
cost_amount: "3"
cost_resource: Essence
distance: 3 cube within 10
feature_type: ability
file_basename: behold-the-mystery
file_dpath: feature/ability/elementalist/level-1
flavor: You open a rift into the void to harry your foes.
item_id: behold-the-mystery
item_name: Behold the Mystery
keywords:
    - Area
    - Magic
    - Ranged
    - Void
level: "1"
name: Behold the Mystery
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/behold-the-mystery
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 3 Essence
distance: 3 cube within 10
effects:
    - effect: "\n*You open a rift into the void to harry your foes.*\n\n| **Area, Magic, Ranged, Void** |               **Main action** |\n|-------------------------------|------------------------------:|\n| **\U0001F4CF 3 cube within 10**       | **\U0001F3AF Each enemy in the area** |\n\n**Power Roll + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**\n\n- **≤11:** 2 psychic damage\n- **12-16:** 4 psychic damage\n- **17+:** 6 psychic damage\n\n**Persistent 1:** At the start of your turn, you can use a maneuver to use this ability again without spending essence."
feature_type: ability
flavor: You open a rift into the void to harry your foes.
keywords:
    - Area
    - Magic
    - Ranged
    - Void
metadata:
    action_type: Main action
    class: elementalist
    cost: 3 Essence
    distance: 3 cube within 10
    flavor: You open a rift into the void to harry your foes.
    keywords:
        - Area
        - Magic
        - Ranged
        - Void
    level: "1"
    name: Behold the Mystery
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/behold-the-mystery
    target: Each enemy in the area
    type: ability
name: Behold the Mystery
target: Each enemy in the area
type: feature
usage: Main action
```
