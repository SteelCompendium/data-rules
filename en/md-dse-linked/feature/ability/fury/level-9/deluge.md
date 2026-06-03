---
action_type: Main action
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 5 cube within 10
effect: This ability deals your primordial damage type and ignores damage immunity.
feature_type: ability
file_basename: deluge
file_dpath: feature/ability/fury/level-9
flavor: You summon your [primordial storm](../../../trait/fury/primordial-storm.md).
item_id: deluge
item_name: Deluge
keywords:
    - Area
    - Magic
    - Ranged
level: "9"
name: Deluge
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-9/deluge
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 7 damage
tier2: 10 damage
tier3: 15 damage
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 5 cube within 10
effects:
    - effect: This ability deals your primordial damage type and ignores damage immunity.
    - roll: Power Roll + Might
      tier1: 7 damage
      tier2: 10 damage
      tier3: 15 damage
feature_type: ability
flavor: You summon your [primordial storm](../../../trait/fury/primordial-storm.md).
keywords:
    - Area
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: fury
    cost: 11 Ferocity
    distance: 5 cube within 10
    effect: This ability deals your primordial damage type and ignores damage immunity.
    flavor: You summon your [primordial storm](../../../trait/fury/primordial-storm.md).
    keywords:
        - Area
        - Magic
        - Ranged
    level: "9"
    name: Deluge
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-9/deluge
    target: Each enemy in the area
    tier1: 7 damage
    tier2: 10 damage
    tier3: 15 damage
    type: ability
name: Deluge
target: Each enemy in the area
type: feature
usage: Main action
```
