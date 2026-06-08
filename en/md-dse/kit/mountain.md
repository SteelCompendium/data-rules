---
equipment_text: You wear heavy armor and wield a heavy weapon.
file_basename: mountain
file_dpath: kit
item_id: mountain
item_name: Mountain
name: Mountain
scc: mcdm.heroes.v1/kit/mountain
source: mcdm.heroes.v1
type: kit
---

The [Mountain](scc:mcdm.heroes.v1/kit/mountain) kit does exactly what it says on the tin. You don heavy armor and raise a heavy weapon to stand strong against your foes, quickly demolishing them when it's your turn to strike.

##### Equipment

You wear heavy armor and wield a heavy weapon.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +9 per [echelon](scc:mcdm.heroes.v1/rule.general/echelon)

**[Stability](scc:mcdm.heroes.v1/rule.character/stability) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2

**[Melee](scc:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +0/+0/+4

##### Signature Ability

###### Pain for Pain

*An enemy who tagged you will pay for that.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 + M or A damage
- **12-16:** 5 + M or A damage
- **17+:** 13 + M or A damage

**Effect:** If the target dealt damage to you since the end of your last [turn](scc:mcdm.heroes.v1/rule.combat/turn), this [strike](scc:mcdm.heroes.v1/rule.combat/strike) deals additional damage equal to your [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility) score (your choice).

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: If the target dealt damage to you since the end of your last [turn](scc:mcdm.heroes.v1/rule.combat/turn), this [strike](scc:mcdm.heroes.v1/rule.combat/strike) deals additional damage equal to your [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility) score (your choice).
feature_type: ability
flavor: An enemy who tagged you will pay for that.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: If the target dealt damage to you since the end of your last [turn](scc:mcdm.heroes.v1/rule.combat/turn), this [strike](scc:mcdm.heroes.v1/rule.combat/strike) deals additional damage equal to your [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility) score (your choice).
    flavor: An enemy who tagged you will pay for that.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Pain for Pain
    subtype: signature
    target: One creature
    type: ability
name: Pain for Pain
target: One creature
type: feature
usage: Main action
```
