---
action_type: Main action
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
feature_type: ability
file_basename: extension-of-my-arm
file_dpath: feature/ability/whirlwind
flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
item_id: extension-of-my-arm
item_name: Extension of My Arm
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: whirlwind
name: Extension of My Arm
power_roll_characteristic: '[Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.whirlwind/extension-of-my-arm
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 4 + M or A damage; vertical pull 1
tier2: 7 + M or A damage; vertical pull 2
tier3: 10 + M or A damage; vertical pull 3
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
effects:
    - roll: Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + M or A damage; vertical pull 1
      tier2: 7 + M or A damage; vertical pull 2
      tier3: 10 + M or A damage; vertical pull 3
feature_type: ability
flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
    flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: whirlwind
    name: Extension of My Arm
    power_roll_characteristic: '[Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.whirlwind/extension-of-my-arm
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage; vertical pull 1
    tier2: 7 + M or A damage; vertical pull 2
    tier3: 10 + M or A damage; vertical pull 3
    type: ability
name: Extension of My Arm
target: One creature
type: feature
usage: Main action
```
