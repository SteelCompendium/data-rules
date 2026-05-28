---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Melee 1
effect: While [slowed](scc:mcdm.heroes.v1/condition/slowed) this way, the target takes 1 damage for every square they move, including from [forced movement](scc:mcdm.heroes.v1/movement/forced-movement).
feature_type: ability
file_basename: debilitating-strike
file_dpath: feature/ability/fury/level-5
flavor: You need just one blow to sabotage your target.
item_id: debilitating-strike
item_name: Debilitating Strike
keywords:
    - Melee
    - Strike
    - Weapon
level: "5"
name: Debilitating Strike
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-5/debilitating-strike
source: mcdm.heroes.v1
target: One creature
tier1: 10 + M damage; M < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 14 + M damage; M < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 20 + M damage; M < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Melee 1
effects:
    - effect: While [slowed](scc:mcdm.heroes.v1/condition/slowed) this way, the target takes 1 damage for every square they move, including from [forced movement](scc:mcdm.heroes.v1/movement/forced-movement).
    - roll: Power Roll + Might
      tier1: 10 + M damage; M < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 14 + M damage; M < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 20 + M damage; M < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
feature_type: ability
flavor: You need just one blow to sabotage your target.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 9 Ferocity
    distance: Melee 1
    effect: While [slowed](scc:mcdm.heroes.v1/condition/slowed) this way, the target takes 1 damage for every square they move, including from [forced movement](scc:mcdm.heroes.v1/movement/forced-movement).
    flavor: You need just one blow to sabotage your target.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "5"
    name: Debilitating Strike
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-5/debilitating-strike
    target: One creature
    tier1: 10 + M damage; M < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 14 + M damage; M < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
    tier3: 20 + M damage; M < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
    type: ability
name: Debilitating Strike
target: One creature
type: feature
usage: Main action
```
