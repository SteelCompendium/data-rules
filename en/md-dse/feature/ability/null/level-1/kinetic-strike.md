---
action_type: Main action
class: "null"
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: kinetic-strike
file_dpath: feature/ability/null/level-1
flavor: Your opponent staggers. They cannot ignore you.
item_id: kinetic-strike
item_name: Kinetic Strike
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Kinetic Strike
power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/kinetic-strike
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 4 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
tier2: 5 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)), slide 1
tier3: 6 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)), slide 2
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier2: 5 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)), slide 1
      tier3: 6 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)), slide 2
feature_type: ability
flavor: Your opponent staggers. They cannot ignore you.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: Your opponent staggers. They cannot ignore you.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Kinetic Strike
    power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-1/kinetic-strike
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier2: 5 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)), slide 1
    tier3: 6 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)), slide 2
    type: ability
name: Kinetic Strike
target: One creature or object
type: feature
usage: Main action
```
