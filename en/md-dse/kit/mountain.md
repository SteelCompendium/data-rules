---
equipment_text: You wear heavy armor and wield a heavy weapon.
file_basename: mountain
file_dpath: kit
item_id: mountain
item_name: Mountain
melee_damage_bonus: +0/+0/+4
name: Mountain
scc: mcdm.heroes.v1/kit/mountain
source: mcdm.heroes.v1
stability_bonus: "+2"
type: kit
---

The [Mountain](scc:mcdm.heroes.v1/kit/mountain) kit does exactly what it says on the tin. You don heavy armor and raise a heavy weapon to stand strong against your foes, quickly demolishing them when it's your turn to strike.

##### Equipment

You wear heavy armor and wield a heavy weapon.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) Bonus:** +9 per echelon

**Stability Bonus:** +2

**Melee Damage Bonus:** +0/+0/+4

##### Signature Ability

###### Pain for Pain

*An enemy who tagged you will pay for that.*

| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 Melee 1**            | **🎯 One creature** |

**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 + M or A damage
- **12-16:** 5 + M or A damage
- **17+:** 13 + M or A damage

**Effect:** If the target dealt damage to you since the end of your last turn, this [strike](scc:mcdm.heroes.v1/rule.combat/strike) deals additional damage equal to your [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility) score (your choice).

```ds-feature
distance: Melee 1
effects:
    - effect: If the target dealt damage to you since the end of your last turn, this [strike](scc:mcdm.heroes.v1/rule.combat/strike) deals additional damage equal to your [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility) score (your choice).
feature_type: ability
flavor: An enemy who tagged you will pay for that.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    effect: If the target dealt damage to you since the end of your last turn, this [strike](scc:mcdm.heroes.v1/rule.combat/strike) deals additional damage equal to your [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility) score (your choice).
    flavor: An enemy who tagged you will pay for that.
    keywords:
        - Melee
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
