---
action_type: Maneuver
class: talent
distance: 3 burst
effect: Each target can [fly](../../../../movement/fly.md) until the start of your next turn, and can immediately [shift](../../../../movement/shifting.md) up to their speed. You can also [shift](../../../../movement/shifting.md) up to your speed. While [flying](../../../../movement/fly.md), a target's stability is reduced to 0 and can't be increased.
feature_type: ability
file_basename: levitation-field
file_dpath: feature/ability/talent/level-8
flavor: You manipulate the air around your allies so they can move as freely through the sky as you can.
item_id: levitation-field
item_name: Levitation Field
keywords:
    - Area
    - Psionic
level: "8"
name: Levitation Field
scc: mcdm.heroes.v1/feature.ability.talent.level-8/levitation-field
source: mcdm.heroes.v1
spend: '5 Clarity: The effects last for 1 hour instead.'
target: Each ally in the area
type: ability
---

```ds-feature
distance: 3 burst
effects:
    - effect: Each target can [fly](../../../../movement/fly.md) until the start of your next turn, and can immediately [shift](../../../../movement/shifting.md) up to their speed. You can also [shift](../../../../movement/shifting.md) up to your speed. While [flying](../../../../movement/fly.md), a target's stability is reduced to 0 and can't be increased.
    - effect: '5 Clarity: The effects last for 1 hour instead.'
      name: Spend
feature_type: ability
flavor: You manipulate the air around your allies so they can move as freely through the sky as you can.
keywords:
    - Area
    - Psionic
metadata:
    action_type: Maneuver
    class: talent
    distance: 3 burst
    effect: Each target can [fly](../../../../movement/fly.md) until the start of your next turn, and can immediately [shift](../../../../movement/shifting.md) up to their speed. You can also [shift](../../../../movement/shifting.md) up to your speed. While [flying](../../../../movement/fly.md), a target's stability is reduced to 0 and can't be increased.
    flavor: You manipulate the air around your allies so they can move as freely through the sky as you can.
    keywords:
        - Area
        - Psionic
    level: "8"
    name: Levitation Field
    scc: mcdm.heroes.v1/feature.ability.talent.level-8/levitation-field
    spend: '5 Clarity: The effects last for 1 hour instead.'
    target: Each ally in the area
    type: ability
name: Levitation Field
target: Each ally in the area
type: feature
usage: Maneuver
```
