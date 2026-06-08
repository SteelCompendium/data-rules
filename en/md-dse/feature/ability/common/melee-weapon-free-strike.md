---
action_type: Main action
distance: Melee 1
feature_type: ability
file_basename: melee-weapon-free-strike
file_dpath: feature/ability/common
item_id: melee-weapon-free-strike
item_name: Melee Weapon Free Strike
keywords:
    - Charge
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
name: Melee Weapon Free Strike
scc: mcdm.heroes.v1/feature.ability.common/melee-weapon-free-strike
source: mcdm.heroes.v1
subtype: free-strike
target: One creature or object
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: "| **Charge, Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon**  |               **Main action** |\n|------------------------------------|------------------------------:|\n| **\U0001F4CF Melee 1**                     | **\U0001F3AF One creature or object** |\n\n**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 2 + M or A damage\n- **12-16:** 5 + M or A damage\n- **17+:** 7 + M or A damage"
feature_type: ability
keywords:
    - Charge
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    keywords:
        - Charge
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Melee Weapon Free Strike
    scc: mcdm.heroes.v1/feature.ability.common/melee-weapon-free-strike
    subtype: free-strike
    target: One creature or object
    type: ability
name: Melee Weapon Free Strike
target: One creature or object
type: feature
usage: Main action
```
