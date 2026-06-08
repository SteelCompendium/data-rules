---
equipment_text: You wear heavy armor and wield a shield and a medium weapon.
file_basename: shining-armor
file_dpath: kit
item_id: shining-armor
item_name: Shining Armor
name: Shining Armor
scc: mcdm.heroes.v1/kit/shining-armor
source: mcdm.heroes.v1
type: kit
---

The [Shining Armor](scc:mcdm.heroes.v1/kit/shining-armor) kit provides the most protection a kit can afford, providing you with the sword, shield, and armor necessary to play the prototypical knight.

##### Equipment

You wear heavy armor and wield a shield and a medium weapon.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +12 per [echelon](scc:mcdm.heroes.v1/rule.general/echelon)

**[Stability](scc:mcdm.heroes.v1/rule.character/stability) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Melee](scc:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2/+2/+2

##### Signature Ability

###### Protective Attack

*The strength of your assault makes it impossible for your foe to ignore you.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 5 + M or A damage
- **12-16:** 8 + M or A damage
- **17+:** 11 + M or A damage

**Effect:** The target is [taunted](scc:mcdm.heroes.v1/condition/taunted) until the end of their next [turn](scc:mcdm.heroes.v1/rule.combat/turn).

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: The target is [taunted](scc:mcdm.heroes.v1/condition/taunted) until the end of their next [turn](scc:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
flavor: The strength of your assault makes it impossible for your foe to ignore you.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: The target is [taunted](scc:mcdm.heroes.v1/condition/taunted) until the end of their next [turn](scc:mcdm.heroes.v1/rule.combat/turn).
    flavor: The strength of your assault makes it impossible for your foe to ignore you.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Protective Attack
    subtype: signature
    target: One creature
    type: ability
name: Protective Attack
target: One creature
type: feature
usage: Main action
```
