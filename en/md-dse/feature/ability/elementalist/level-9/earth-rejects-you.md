---
action_type: Main action
class: elementalist
cost: 11 Essence
cost_amount: "11"
cost_resource: Essence
distance: 5 cube within 10
feature_type: ability
file_basename: earth-rejects-you
file_dpath: feature/ability/elementalist/level-9
flavor: Everyone and everything gets blown away in an eruption of rocks and debris.
item_id: earth-rejects-you
item_name: Earth Rejects You
keywords:
    - Area
    - Earth
    - Magic
    - Ranged
level: "9"
name: Earth Rejects You
scc: mcdm.heroes.v1/feature.ability.elementalist.level-9/earth-rejects-you
source: mcdm.heroes.v1
target: Each enemy and object in the area
type: ability
---

```ds-feature
cost: 11 Essence
distance: 5 cube within 10
effects:
    - effect: "\n*Everyone and everything gets blown away in an eruption of rocks and debris.*\n\n| **Area, Earth, Magic, Ranged** |                          **Main action** |\n|--------------------------------|-----------------------------------------:|\n| **\U0001F4CF 5 cube within 10**        | **\U0001F3AF Each enemy and object in the area** |\n\n**Power Roll + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**\n\n- **≤11:** 6 damage\n- **12-16:** 9 damage\n- **17+:** 13 damage\n\n**Persistent 2:** At the start of your turn, you can use a maneuver to use this ability again without spending essence."
feature_type: ability
flavor: Everyone and everything gets blown away in an eruption of rocks and debris.
keywords:
    - Area
    - Earth
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: elementalist
    cost: 11 Essence
    distance: 5 cube within 10
    flavor: Everyone and everything gets blown away in an eruption of rocks and debris.
    keywords:
        - Area
        - Earth
        - Magic
        - Ranged
    level: "9"
    name: Earth Rejects You
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-9/earth-rejects-you
    target: Each enemy and object in the area
    type: ability
name: Earth Rejects You
target: Each enemy and object in the area
type: feature
usage: Main action
```
