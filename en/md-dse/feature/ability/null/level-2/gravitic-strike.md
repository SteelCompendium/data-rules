---
action_type: Main action
class: "null"
cost: 5 Discipline
cost_amount: "5"
cost_resource: Discipline
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
feature_type: ability
file_basename: gravitic-strike
file_dpath: feature/ability/null/level-2
flavor: Your fist emanates gravitic force that pulls a distant enemy closer.
item_id: gravitic-strike
item_name: Gravitic Strike
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: Gravitic Strike
power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-2/gravitic-strike
source: mcdm.heroes.v1
target: One creature
tier1: 8 + A psychic damage; vertical pull 3
tier2: 12 + A psychic damage; vertical pull 5
tier3: 16 + A psychic damage; vertical pull 7
type: ability
---

```ds-feature
cost: 5 Discipline
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
effects:
    - roll: Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility)
      tier1: 8 + A psychic damage; vertical pull 3
      tier2: 12 + A psychic damage; vertical pull 5
      tier3: 16 + A psychic damage; vertical pull 7
feature_type: ability
flavor: Your fist emanates gravitic force that pulls a distant enemy closer.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 5 Discipline
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
    flavor: Your fist emanates gravitic force that pulls a distant enemy closer.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: Gravitic Strike
    power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-2/gravitic-strike
    target: One creature
    tier1: 8 + A psychic damage; vertical pull 3
    tier2: 12 + A psychic damage; vertical pull 5
    tier3: 16 + A psychic damage; vertical pull 7
    type: ability
name: Gravitic Strike
target: One creature
type: feature
usage: Main action
```
