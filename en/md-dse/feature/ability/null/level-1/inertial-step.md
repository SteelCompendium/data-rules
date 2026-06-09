---
action_type: Main action
class: "null"
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to half your [speed](scc:mcdm.heroes.v1/rule.character/speed) before or after you make this [strike](scc:mcdm.heroes.v1/rule.combat/strike).
feature_type: ability
file_basename: inertial-step
file_dpath: feature/ability/null/level-1
flavor: You flit about the battlefield and take an opportunistic strike.
item_id: inertial-step
item_name: Inertial Step
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Inertial Step
power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/inertial-step
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 5 + A damage
tier2: 7 + A damage
tier3: 10 + A damage
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to half your [speed](scc:mcdm.heroes.v1/rule.character/speed) before or after you make this [strike](scc:mcdm.heroes.v1/rule.combat/strike).
    - roll: Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + A damage
      tier2: 7 + A damage
      tier3: 10 + A damage
feature_type: ability
flavor: You flit about the battlefield and take an opportunistic strike.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to half your [speed](scc:mcdm.heroes.v1/rule.character/speed) before or after you make this [strike](scc:mcdm.heroes.v1/rule.combat/strike).
    flavor: You flit about the battlefield and take an opportunistic strike.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Inertial Step
    power_roll_characteristic: '[Agility](scc:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-1/inertial-step
    subtype: signature
    target: One creature or object
    tier1: 5 + A damage
    tier2: 7 + A damage
    tier3: 10 + A damage
    type: ability
name: Inertial Step
target: One creature or object
type: feature
usage: Main action
```
