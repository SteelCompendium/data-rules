---
action_type: Main action
class: talent
distance: Ranged 10
feature_type: ability
file_basename: hoarfrost
file_dpath: feature/ability/talent/level-1
flavor: You blast a foe with a pulse of cold energy.
item_id: hoarfrost
item_name: Hoarfrost
keywords:
    - Cryokinesis
    - Psionic
    - Ranged
    - Strike
level: "1"
name: Hoarfrost
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.talent.level-1/hoarfrost
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + R cold damage; M < WEAK, slowed (EoT)
tier2: 4 + R cold damage; M < AVERAGE, slowed (EoT)
tier3: 6 + R cold damage; M < STRONG, slowed (EoT)
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - roll: Power Roll + Reason
      tier1: 2 + R cold damage; M < WEAK, slowed (EoT)
      tier2: 4 + R cold damage; M < AVERAGE, slowed (EoT)
      tier3: 6 + R cold damage; M < STRONG, slowed (EoT)
feature_type: ability
flavor: You blast a foe with a pulse of cold energy.
keywords:
    - Cryokinesis
    - Psionic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: talent
    distance: Ranged 10
    flavor: You blast a foe with a pulse of cold energy.
    keywords:
        - Cryokinesis
        - Psionic
        - Ranged
        - Strike
    level: "1"
    name: Hoarfrost
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/hoarfrost
    subtype: signature
    target: One creature
    tier1: 2 + R cold damage; M < WEAK, slowed (EoT)
    tier2: 4 + R cold damage; M < AVERAGE, slowed (EoT)
    tier3: 6 + R cold damage; M < STRONG, slowed (EoT)
    type: ability
name: Hoarfrost
target: One creature
type: feature
usage: Main action
```
