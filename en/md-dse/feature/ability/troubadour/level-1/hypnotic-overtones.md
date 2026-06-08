---
action_type: Main action
class: troubadour
cost: 3 Drama
cost_amount: "3"
cost_resource: Drama
distance: 2 burst
feature_type: ability
file_basename: hypnotic-overtones
file_dpath: feature/ability/troubadour/level-1
flavor: You produce an entrancing note that twists the senses in a spectacular fashion.
item_id: hypnotic-overtones
item_name: Hypnotic Overtones
keywords:
    - Area
    - Magic
level: "1"
name: Hypnotic Overtones
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/hypnotic-overtones
source: mcdm.heroes.v1
spend: '2+ Drama: The size of the burst increases by 1 for every 2 drama spent.'
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 3 Drama
distance: 2 burst
effects:
    - effect: '2+ Drama: The size of the burst increases by 1 for every 2 drama spent.'
      name: Spend
feature_type: ability
flavor: You produce an entrancing note that twists the senses in a spectacular fashion.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: troubadour
    cost: 3 Drama
    distance: 2 burst
    flavor: You produce an entrancing note that twists the senses in a spectacular fashion.
    keywords:
        - Area
        - Magic
    level: "1"
    name: Hypnotic Overtones
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/hypnotic-overtones
    spend: '2+ Drama: The size of the burst increases by 1 for every 2 drama spent.'
    target: Each enemy in the area
    type: ability
name: Hypnotic Overtones
target: Each enemy in the area
type: feature
usage: Main action
```
