---
action_type: Main action
class: fury
distance: '[Melee](../../../../rule/combat/melee.md) 1'
feature_type: ability
file_basename: impaled
file_dpath: feature/ability/fury/level-1
flavor: You skewer your enemy like a boar upon a spit.
item_id: impaled
item_name: Impaled!
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Impaled!
scc: mcdm.heroes.v1/feature.ability.fury.level-1/impaled
source: mcdm.heroes.v1
subtype: signature
target: One creature of your [size](../../../../rule/character/size.md) or smaller
type: ability
---

```ds-feature
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: "\n*You skewer your enemy like a boar upon a spit.*\n\n| **[Melee](../../../../rule/combat/melee.md), [Strike](../../../../rule/combat/strike.md), Weapon** |                             **Main action** |\n|---------------------------|--------------------------------------------:|\n| **\U0001F4CF [Melee](../../../../rule/combat/melee.md) 1**            | **\U0001F3AF One creature of your [size](../../../../rule/character/size.md) or smaller** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Might](../../../../rule/character/might.md):**\n\n- **≤11:** 2 + M damage; M < WEAK, [grabbed](../../../../condition/grabbed.md)\n- **12-16:** 5 + M damage; M < AVERAGE, [grabbed](../../../../condition/grabbed.md)\n- **17+:** 7 + M damage; M < STRONG, [grabbed](../../../../condition/grabbed.md)"
feature_type: ability
flavor: You skewer your enemy like a boar upon a spit.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    flavor: You skewer your enemy like a boar upon a spit.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Impaled!
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/impaled
    subtype: signature
    target: One creature of your [size](../../../../rule/character/size.md) or smaller
    type: ability
name: Impaled!
target: One creature of your [size](../../../../rule/character/size.md) or smaller
type: feature
usage: Main action
```
