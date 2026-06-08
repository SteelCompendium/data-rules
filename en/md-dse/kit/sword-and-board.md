---
equipment_text: You wear medium armor and wield a shield and a medium weapon.
file_basename: sword-and-board
file_dpath: kit
flavor: The Sword and Board kit doesn't just give you a shield—it makes the shield part of your offensive arsenal. With a medium weapon in one hand and a block of steel or solid oak in the other, you protect yourself while you control the battlefield.
item_id: sword-and-board
item_name: Sword and Board
name: Sword and Board
scc: mcdm.heroes.v1/kit/sword-and-board
source: mcdm.heroes.v1
type: kit
---

The [Sword and Board](scc:mcdm.heroes.v1/kit/sword-and-board) kit doesn't just give you a shield—it makes the shield part of your offensive arsenal. With a medium weapon in one hand and a block of steel or solid oak in the other, you protect yourself while you control the battlefield.

##### Equipment

You wear medium armor and wield a shield and a medium weapon.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +9 per [echelon](scc:mcdm.heroes.v1/rule.general/echelon)

**[Stability](scc:mcdm.heroes.v1/rule.character/stability) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Melee](scc:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2/+2/+2

**Disengage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

##### Signature Ability

###### Shield Bash

*In your hands, a shield isn't just for protection.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 + M or A damage; push 1
- **12-16:** 7 + M or A damage; push 2
- **17+:** 9 + M or A damage; push 3; M < STRONG[, prone](scc:mcdm.heroes.v1/condition/prone)

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: "*In your hands, a shield isn't just for protection.*\n\n| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + M or A damage; push 1\n- **12-16:** 7 + M or A damage; push 2\n- **17+:** 9 + M or A damage; push 3; M < STRONG[, prone](scc:mcdm.heroes.v1/condition/prone)"
feature_type: ability
flavor: In your hands, a shield isn't just for protection.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: In your hands, a shield isn't just for protection.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Shield Bash
    subtype: signature
    target: One creature
    type: ability
name: Shield Bash
target: One creature
type: feature
usage: Main action
```
