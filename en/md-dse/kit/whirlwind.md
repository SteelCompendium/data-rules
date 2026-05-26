---
disengage_bonus: "+1"
equipment_text: You wear no armor and wield a whip.
file_basename: whirlwind
file_dpath: kit
item_id: whirlwind
item_name: Whirlwind
melee_damage_bonus: +1/+1/+1
melee_distance_bonus: "+1"
name: Whirlwind
scc: mcdm.heroes.v1/kit/whirlwind
source: mcdm.heroes.v1
speed_bonus: "+3"
type: kit
---

The [Whirlwind](scc:mcdm.heroes.v1/kit/whirlwind) kit makes effective use of whips, granting you mobility, damage, and reach. If you want to be a fast-moving warrior who lashes foes with a chain or whip, then this is the kit for you.

##### Equipment

You wear no armor and wield a whip.

##### Kit Bonuses

**Speed Bonus:** +3

**Melee Damage Bonus:** +1/+1/+1

**Melee Distance Bonus:** +1

**Disengage Bonus:** +1

##### Signature Ability

###### Extension of My Arm

*When you draw your whip back after an attack, your enemy is drawn ever closer.*

| **Melee, Strike, Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 Melee 3**            | **🎯 One creature** |

**Power Roll + Might or Agility:**

- **≤11:** 4 + M or A damage; vertical pull 1
- **12-16:** 7 + M or A damage; vertical pull 2
- **17+:** 10 + M or A damage; vertical pull 3

```ds-feature
distance: Melee 3
effects:
    - effect: "*When you draw your whip back after an attack, your enemy is drawn ever closer.*\n\n| **Melee, Strike, Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF Melee 3**            | **\U0001F3AF One creature** |\n\n**Power Roll + Might or Agility:**\n\n- **≤11:** 4 + M or A damage; vertical pull 1\n- **12-16:** 7 + M or A damage; vertical pull 2\n- **17+:** 10 + M or A damage; vertical pull 3"
feature_type: ability
flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 3
    flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
    keywords:
        - Melee
        - Strike
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
