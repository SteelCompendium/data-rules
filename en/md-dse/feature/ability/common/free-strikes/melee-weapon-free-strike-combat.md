---
action_type: Main action
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: melee-weapon-free-strike-combat
file_dpath: feature/ability/common/free-strikes
item_id: melee-weapon-free-strike-combat
item_name: Melee Weapon Free Strike
keywords:
    - Charge
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Stike
    - Weapon
name: Melee Weapon Free Strike
power_roll_characteristic: '[Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.common.free-strikes/melee-weapon-free-strike-combat
source: mcdm.heroes.v1
subtype: free-strike
target: One creature or object
tier1: 2 + M or A damage
tier2: 5 + M or A damage
tier3: 7 + M or A damage
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility)
      tier1: 2 + M or A damage
      tier2: 5 + M or A damage
      tier3: 7 + M or A damage
feature_type: ability
keywords:
    - Charge
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Stike
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    keywords:
        - Charge
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Stike
        - Weapon
    name: Melee Weapon Free Strike
    power_roll_characteristic: '[Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.common.free-strikes/melee-weapon-free-strike-combat
    subtype: free-strike
    target: One creature or object
    tier1: 2 + M or A damage
    tier2: 5 + M or A damage
    tier3: 7 + M or A damage
    type: ability
name: Melee Weapon Free Strike
target: One creature or object
type: feature
usage: Main action
```
