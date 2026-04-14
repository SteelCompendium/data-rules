---
action_type: Triggered
class: tactician
distance: Ranged 10
effect: At any time during the target's movement, one ally can make a free strike against them.
feature_type: ability
file_basename: overwatch
file_dpath: feature/ability/tactician/level-1
flavor: Under your direction, an ally waits for just the right moment to strike.
item_id: overwatch
item_name: Overwatch
keywords:
    - Ranged
level: "1"
name: Overwatch
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/overwatch
source: mcdm.heroes.v1
spend: '1 Focus: If the target has R < AVERAGE, they are slowed (EoT).'
subtype: triggered
target: One creature
trigger: The target moves.
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: At any time during the target's movement, one ally can make a free strike against them.
    - effect: '1 Focus: If the target has R < AVERAGE, they are slowed (EoT).'
      name: Spend
feature_type: ability
flavor: Under your direction, an ally waits for just the right moment to strike.
keywords:
    - Ranged
metadata:
    action_type: Triggered
    class: tactician
    distance: Ranged 10
    effect: At any time during the target's movement, one ally can make a free strike against them.
    flavor: Under your direction, an ally waits for just the right moment to strike.
    keywords:
        - Ranged
    level: "1"
    name: Overwatch
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/overwatch
    spend: '1 Focus: If the target has R < AVERAGE, they are slowed (EoT).'
    subtype: triggered
    target: One creature
    trigger: The target moves.
    type: ability
name: Overwatch
target: One creature
trigger: The target moves.
type: feature
usage: Triggered
```
