---
action_type: Main action
class: shadow
cost: 3 Insight
cost_amount: "3"
cost_resource: Insight
distance: Melee 1
effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) into any square the target leaves when you slide them.
feature_type: ability
file_basename: disorienting-strike
file_dpath: feature/ability/shadow/level-1
flavor: Your attack leaves them reeling, allowing you to follow up.
item_id: disorienting-strike
item_name: Disorienting Strike
keywords:
    - Melee
    - Strike
    - Weapon
level: "1"
name: Disorienting Strike
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/disorienting-strike
source: mcdm.heroes.v1
target: One creature
tier1: 4 + A damage; slide 2
tier2: 6 + A damage; slide 3
tier3: 10 + A damage; slide 5
type: ability
---

```ds-feature
cost: 3 Insight
distance: Melee 1
effects:
    - effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) into any square the target leaves when you slide them.
    - roll: Power Roll + Agility
      tier1: 4 + A damage; slide 2
      tier2: 6 + A damage; slide 3
      tier3: 10 + A damage; slide 5
feature_type: ability
flavor: Your attack leaves them reeling, allowing you to follow up.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 3 Insight
    distance: Melee 1
    effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) into any square the target leaves when you slide them.
    flavor: Your attack leaves them reeling, allowing you to follow up.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Disorienting Strike
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/disorienting-strike
    target: One creature
    tier1: 4 + A damage; slide 2
    tier2: 6 + A damage; slide 3
    tier3: 10 + A damage; slide 5
    type: ability
name: Disorienting Strike
target: One creature
type: feature
usage: Main action
```
