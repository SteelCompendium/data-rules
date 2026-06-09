---
action_type: Main action
class: "null"
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
feature_type: ability
file_basename: magnetic-strike
file_dpath: feature/ability/null/level-1
flavor: The force of your blow extends past the limits of your body, pulling your enemy closer.
item_id: magnetic-strike
item_name: Magnetic Strike
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Magnetic Strike
power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/magnetic-strike
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 5 + A psychic damage; vertical pull 1
tier2: 8 + A psychic damage; vertical pull 2
tier3: 11 + A psychic damage; vertical pull 3
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - roll: Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + A psychic damage; vertical pull 1
      tier2: 8 + A psychic damage; vertical pull 2
      tier3: 11 + A psychic damage; vertical pull 3
feature_type: ability
flavor: The force of your blow extends past the limits of your body, pulling your enemy closer.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
    flavor: The force of your blow extends past the limits of your body, pulling your enemy closer.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Magnetic Strike
    power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-1/magnetic-strike
    subtype: signature
    target: One creature
    tier1: 5 + A psychic damage; vertical pull 1
    tier2: 8 + A psychic damage; vertical pull 2
    tier3: 11 + A psychic damage; vertical pull 3
    type: ability
name: Magnetic Strike
target: One creature
type: feature
usage: Main action
```
