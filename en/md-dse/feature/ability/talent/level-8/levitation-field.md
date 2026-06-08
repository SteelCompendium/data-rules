---
action_type: Maneuver
class: talent
distance: 3 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
effect: Each target can [fly](scc:mcdm.heroes.v1/movement/fly) until the start of your next [turn](scc:mcdm.heroes.v1/rule.combat/turn), and can immediately [shift](scc:mcdm.heroes.v1/movement/shifting) up to their [speed](scc:mcdm.heroes.v1/rule.character/speed). You can also [shift](scc:mcdm.heroes.v1/movement/shifting) up to your [speed](scc:mcdm.heroes.v1/rule.character/speed). While [flying](scc:mcdm.heroes.v1/movement/fly), a target's [stability](scc:mcdm.heroes.v1/rule.character/stability) is reduced to 0 and can't be increased.
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
distance: 3 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each target can [fly](scc:mcdm.heroes.v1/movement/fly) until the start of your next [turn](scc:mcdm.heroes.v1/rule.combat/turn), and can immediately [shift](scc:mcdm.heroes.v1/movement/shifting) up to their [speed](scc:mcdm.heroes.v1/rule.character/speed). You can also [shift](scc:mcdm.heroes.v1/movement/shifting) up to your [speed](scc:mcdm.heroes.v1/rule.character/speed). While [flying](scc:mcdm.heroes.v1/movement/fly), a target's [stability](scc:mcdm.heroes.v1/rule.character/stability) is reduced to 0 and can't be increased.
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
    distance: 3 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
    effect: Each target can [fly](scc:mcdm.heroes.v1/movement/fly) until the start of your next [turn](scc:mcdm.heroes.v1/rule.combat/turn), and can immediately [shift](scc:mcdm.heroes.v1/movement/shifting) up to their [speed](scc:mcdm.heroes.v1/rule.character/speed). You can also [shift](scc:mcdm.heroes.v1/movement/shifting) up to your [speed](scc:mcdm.heroes.v1/rule.character/speed). While [flying](scc:mcdm.heroes.v1/movement/fly), a target's [stability](scc:mcdm.heroes.v1/rule.character/stability) is reduced to 0 and can't be increased.
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
