---
action_type: Triggered
class: fury
distance: Melee 1
effect: You can select a new target of the same size or smaller within distance to be force moved instead. You become the source of the [forced movement](scc:mcdm.heroes.v1/movement/forced-movement), determine the new target's destination, and can push the target instead of using the original [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) type. Additionally, the [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) distance gains a bonus equal to your Might score.
feature_type: ability
file_basename: lines-of-force
file_dpath: feature/ability/fury/level-1
flavor: You redirect the energy of motion.
item_id: lines-of-force
item_name: Lines of Force
keywords:
    - Magic
    - Melee
level: "1"
name: Lines of Force
scc: mcdm.heroes.v1/feature.ability.fury.level-1/lines-of-force
source: mcdm.heroes.v1
spend: '1 Ferocity: The [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) distance gains a bonus equal to twice your Might score instead.'
subtype: triggered
target: Self or one creature
trigger: The target would be [force moved](scc:mcdm.heroes.v1/movement/forced-movement).
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You can select a new target of the same size or smaller within distance to be force moved instead. You become the source of the [forced movement](scc:mcdm.heroes.v1/movement/forced-movement), determine the new target's destination, and can push the target instead of using the original [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) type. Additionally, the [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) distance gains a bonus equal to your Might score.
    - effect: '1 Ferocity: The [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) distance gains a bonus equal to twice your Might score instead.'
      name: Spend
feature_type: ability
flavor: You redirect the energy of motion.
keywords:
    - Magic
    - Melee
metadata:
    action_type: Triggered
    class: fury
    distance: Melee 1
    effect: You can select a new target of the same size or smaller within distance to be force moved instead. You become the source of the [forced movement](scc:mcdm.heroes.v1/movement/forced-movement), determine the new target's destination, and can push the target instead of using the original [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) type. Additionally, the [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) distance gains a bonus equal to your Might score.
    flavor: You redirect the energy of motion.
    keywords:
        - Magic
        - Melee
    level: "1"
    name: Lines of Force
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/lines-of-force
    spend: '1 Ferocity: The [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) distance gains a bonus equal to twice your Might score instead.'
    subtype: triggered
    target: Self or one creature
    trigger: The target would be [force moved](scc:mcdm.heroes.v1/movement/forced-movement).
    type: ability
name: Lines of Force
target: Self or one creature
trigger: The target would be [force moved](scc:mcdm.heroes.v1/movement/forced-movement).
type: feature
usage: Triggered
```
