---
action_type: Main action
class: elementalist
distance: Ranged 10
feature_type: ability
file_basename: ray-of-agonizing-self-reflection
file_dpath: feature/ability/elementalist/level-1
flavor: You inflict pain and doubt in equal measure.
item_id: ray-of-agonizing-self-reflection
item_name: Ray of Agonizing Self-Reflection
keywords:
    - Magic
    - Ranged
    - Strike
    - Void
level: "1"
name: Ray of Agonizing Self-Reflection
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/ray-of-agonizing-self-reflection
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 2 + R corruption damage; R < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 4 + R corruption damage; R < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 6 + R corruption damage; R < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - roll: Power Roll + Reason
      tier1: 2 + R corruption damage; R < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 4 + R corruption damage; R < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 6 + R corruption damage; R < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
feature_type: ability
flavor: You inflict pain and doubt in equal measure.
keywords:
    - Magic
    - Ranged
    - Strike
    - Void
metadata:
    action_type: Main action
    class: elementalist
    distance: Ranged 10
    flavor: You inflict pain and doubt in equal measure.
    keywords:
        - Magic
        - Ranged
        - Strike
        - Void
    level: "1"
    name: Ray of Agonizing Self-Reflection
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/ray-of-agonizing-self-reflection
    subtype: signature
    target: One creature or object
    tier1: 2 + R corruption damage; R < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 4 + R corruption damage; R < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
    tier3: 6 + R corruption damage; R < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
    type: ability
name: Ray of Agonizing Self-Reflection
target: One creature or object
type: feature
usage: Main action
```
