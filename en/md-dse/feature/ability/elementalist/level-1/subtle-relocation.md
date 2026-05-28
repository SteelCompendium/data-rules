---
action_type: Triggered
class: elementalist
distance: Ranged 10
effect: You [teleport](scc:mcdm.heroes.v1/movement/teleport) the target up to a number of squares equal to your Reason score. If the target moves to trigger this ability, you can [teleport](scc:mcdm.heroes.v1/movement/teleport) them at any point during the move.
feature_type: ability
file_basename: subtle-relocation
file_dpath: feature/ability/elementalist/level-1
flavor: You call on the void to swallow and spit out an ally.
item_id: subtle-relocation
item_name: Subtle Relocation
keywords:
    - Magic
    - Ranged
    - Void
level: "1"
name: Subtle Relocation
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/subtle-relocation
source: mcdm.heroes.v1
spend: '1 Essence: You [teleport](scc:mcdm.heroes.v1/movement/teleport) the target up to a number of squares equal to twice your Reason score instead.'
subtype: triggered
target: Self or one ally
trigger: The target starts their turn, moves, or is [force moved](scc:mcdm.heroes.v1/movement/forced-movement).
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: You [teleport](scc:mcdm.heroes.v1/movement/teleport) the target up to a number of squares equal to your Reason score. If the target moves to trigger this ability, you can [teleport](scc:mcdm.heroes.v1/movement/teleport) them at any point during the move.
    - effect: '1 Essence: You [teleport](scc:mcdm.heroes.v1/movement/teleport) the target up to a number of squares equal to twice your Reason score instead.'
      name: Spend
feature_type: ability
flavor: You call on the void to swallow and spit out an ally.
keywords:
    - Magic
    - Ranged
    - Void
metadata:
    action_type: Triggered
    class: elementalist
    distance: Ranged 10
    effect: You [teleport](scc:mcdm.heroes.v1/movement/teleport) the target up to a number of squares equal to your Reason score. If the target moves to trigger this ability, you can [teleport](scc:mcdm.heroes.v1/movement/teleport) them at any point during the move.
    flavor: You call on the void to swallow and spit out an ally.
    keywords:
        - Magic
        - Ranged
        - Void
    level: "1"
    name: Subtle Relocation
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/subtle-relocation
    spend: '1 Essence: You [teleport](scc:mcdm.heroes.v1/movement/teleport) the target up to a number of squares equal to twice your Reason score instead.'
    subtype: triggered
    target: Self or one ally
    trigger: The target starts their turn, moves, or is [force moved](scc:mcdm.heroes.v1/movement/forced-movement).
    type: ability
name: Subtle Relocation
target: Self or one ally
trigger: The target starts their turn, moves, or is [force moved](scc:mcdm.heroes.v1/movement/forced-movement).
type: feature
usage: Triggered
```
