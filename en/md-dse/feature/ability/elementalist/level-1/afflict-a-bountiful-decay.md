---
action_type: Main action
class: elementalist
distance: Ranged 10
effect: Choose yourself or one ally within distance. That character can end one effect on them that is ended by a saving throw or that ends at the end of their turn.
feature_type: ability
file_basename: afflict-a-bountiful-decay
file_dpath: feature/ability/elementalist/level-1
flavor: Your curse causes your foe's flesh to rot off as spores that aid your allies.
item_id: afflict-a-bountiful-decay
item_name: Afflict a Bountiful Decay
keywords:
    - Green
    - Magic
    - Ranged
    - Rot
    - Strike
level: "1"
name: Afflict a Bountiful Decay
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/afflict-a-bountiful-decay
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + R corruption damage
tier2: 4 + R corruption damage
tier3: 6 + R corruption damage
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: Choose yourself or one ally within distance. That character can end one effect on them that is ended by a saving throw or that ends at the end of their turn.
    - roll: Power Roll + Reason
      tier1: 2 + R corruption damage
      tier2: 4 + R corruption damage
      tier3: 6 + R corruption damage
feature_type: ability
flavor: Your curse causes your foe's flesh to rot off as spores that aid your allies.
keywords:
    - Green
    - Magic
    - Ranged
    - Rot
    - Strike
metadata:
    action_type: Main action
    class: elementalist
    distance: Ranged 10
    effect: Choose yourself or one ally within distance. That character can end one effect on them that is ended by a saving throw or that ends at the end of their turn.
    flavor: Your curse causes your foe's flesh to rot off as spores that aid your allies.
    keywords:
        - Green
        - Magic
        - Ranged
        - Rot
        - Strike
    level: "1"
    name: Afflict a Bountiful Decay
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/afflict-a-bountiful-decay
    subtype: signature
    target: One creature
    tier1: 2 + R corruption damage
    tier2: 4 + R corruption damage
    tier3: 6 + R corruption damage
    type: ability
name: Afflict a Bountiful Decay
target: One creature
type: feature
usage: Main action
```
