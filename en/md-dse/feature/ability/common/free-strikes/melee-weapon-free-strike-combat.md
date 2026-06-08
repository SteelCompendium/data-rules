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
scc: mcdm.heroes.v1/feature.ability.common.free-strikes/melee-weapon-free-strike-combat
source: mcdm.heroes.v1
subtype: free-strike
target: One creature or object
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: "| **Charge, [Melee](scc:mcdm.heroes.v1/rule.combat/melee), Stike, Weapon** |               **Main action** |\n| -------------------------------- | -----------------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**                   | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 2 + M or A damage\n- **12-16:** 5 + M or A damage\n- **17+:** 7 + M or A damage"
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
    scc: mcdm.heroes.v1/feature.ability.common.free-strikes/melee-weapon-free-strike-combat
    subtype: free-strike
    target: One creature or object
    type: ability
name: Melee Weapon Free Strike
target: One creature or object
type: feature
usage: Main action
```
