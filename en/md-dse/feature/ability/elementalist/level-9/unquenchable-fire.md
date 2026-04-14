---
action_type: Main action
class: elementalist
cost: 11 Essence
cost_amount: "11"
cost_resource: Essence
distance: Ranged 10
effect: This damage ignores immunity.
feature_type: ability
file_basename: unquenchable-fire
file_dpath: feature/ability/elementalist/level-9
flavor: You let fly a fiery missile braided with pure primal energy.
item_id: unquenchable-fire
item_name: Unquenchable Fire
keywords:
    - Fire
    - Magic
    - Ranged
    - Strike
level: "9"
name: Unquenchable Fire
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.elementalist.level-9/unquenchable-fire
source: mcdm.heroes.v1
target: One enemy or object
tier1: 13 + R fire damage; I < WEAK, dazed (save ends)
tier2: 18 + R fire damage; I < AVERAGE, dazed (save ends)
tier3: 25 + R fire damage; I < STRONG, dazed (save ends)
type: ability
---

```ds-feature
cost: 11 Essence
distance: Ranged 10
effects:
    - effect: This damage ignores immunity.
    - roll: Power Roll + Reason
      tier1: 13 + R fire damage; I < WEAK, dazed (save ends)
      tier2: 18 + R fire damage; I < AVERAGE, dazed (save ends)
      tier3: 25 + R fire damage; I < STRONG, dazed (save ends)
feature_type: ability
flavor: You let fly a fiery missile braided with pure primal energy.
keywords:
    - Fire
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: elementalist
    cost: 11 Essence
    distance: Ranged 10
    effect: This damage ignores immunity.
    flavor: You let fly a fiery missile braided with pure primal energy.
    keywords:
        - Fire
        - Magic
        - Ranged
        - Strike
    level: "9"
    name: Unquenchable Fire
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-9/unquenchable-fire
    target: One enemy or object
    tier1: 13 + R fire damage; I < WEAK, dazed (save ends)
    tier2: 18 + R fire damage; I < AVERAGE, dazed (save ends)
    tier3: 25 + R fire damage; I < STRONG, dazed (save ends)
    type: ability
name: Unquenchable Fire
target: One enemy or object
type: feature
usage: Main action
```
