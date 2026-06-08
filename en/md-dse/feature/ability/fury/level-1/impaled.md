---
action_type: Main action
class: fury
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: impaled
file_dpath: feature/ability/fury/level-1
flavor: You skewer your enemy like a boar upon a spit.
item_id: impaled
item_name: Impaled!
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Impaled!
scc: mcdm.heroes.v1/feature.ability.fury.level-1/impaled
source: mcdm.heroes.v1
subtype: signature
target: One creature of your [size](scc:mcdm.heroes.v1/rule.character/size) or smaller
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: "\n*You skewer your enemy like a boar upon a spit.*\n\n| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |                             **Main action** |\n|---------------------------|--------------------------------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **\U0001F3AF One creature of your [size](scc:mcdm.heroes.v1/rule.character/size) or smaller** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**\n\n- **≤11:** 2 + M damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)\n- **12-16:** 5 + M damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)\n- **17+:** 7 + M damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)"
feature_type: ability
flavor: You skewer your enemy like a boar upon a spit.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: You skewer your enemy like a boar upon a spit.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Impaled!
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/impaled
    subtype: signature
    target: One creature of your [size](scc:mcdm.heroes.v1/rule.character/size) or smaller
    type: ability
name: Impaled!
target: One creature of your [size](scc:mcdm.heroes.v1/rule.character/size) or smaller
type: feature
usage: Main action
```
