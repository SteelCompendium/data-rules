---
equipment_text: You wear no armor and wield a whip.
file_basename: whirlwind
file_dpath: kit
flavor: The Whirlwind kit makes effective use of whips, granting you mobility, damage, and reach. If you want to be a fast-moving warrior who lashes foes with a chain or whip, then this is the kit for you.
item_id: whirlwind
item_name: Whirlwind
name: Whirlwind
scc: mcdm.heroes.v1/kit/whirlwind
source: mcdm.heroes.v1
type: kit
---

The [Whirlwind](scc:mcdm.heroes.v1/kit/whirlwind) kit makes effective use of whips, granting you mobility, damage, and reach. If you want to be a fast-moving warrior who lashes foes with a chain or whip, then this is the kit for you.

##### Equipment

You wear no armor and wield a whip.

##### Kit Bonuses

**[Speed](scc:mcdm.heroes.v1/rule.character/speed) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +3

**[Melee](scc:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1/+1/+1

**[Melee](scc:mcdm.heroes.v1/rule.combat/melee) [Distance](scc:mcdm.heroes.v1/rule.combat/distance) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**Disengage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

##### Signature Ability

###### Extension of My Arm

*When you draw your whip back after an attack, your enemy is drawn ever closer.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3**            | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 + M or A damage; vertical pull 1
- **12-16:** 7 + M or A damage; vertical pull 2
- **17+:** 10 + M or A damage; vertical pull 3

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
effects:
    - effect: "*When you draw your whip back after an attack, your enemy is drawn ever closer.*\n\n| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3**            | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + M or A damage; vertical pull 1\n- **12-16:** 7 + M or A damage; vertical pull 2\n- **17+:** 10 + M or A damage; vertical pull 3"
feature_type: ability
flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 3'
    flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Extension of My Arm
    subtype: signature
    target: One creature
    type: ability
name: Extension of My Arm
target: One creature
type: feature
usage: Main action
```
