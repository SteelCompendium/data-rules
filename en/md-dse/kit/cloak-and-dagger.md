---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield one or two light weapons.
file_basename: cloak-and-dagger
file_dpath: kit
item_id: cloak-and-dagger
item_name: Cloak and Dagger
melee_damage_bonus: +1/+1/+1
name: Cloak and Dagger
ranged_damage_bonus: +1/+1/+1
ranged_distance_bonus: "+5"
scc: mcdm.heroes.v1/kit/cloak-and-dagger
source: mcdm.heroes.v1
speed_bonus: "+2"
type: kit
---

Providing throwable light weapons and light armor easily concealed by a cloak to confuse your enemies, the [Cloak and Dagger](scc:mcdm.heroes.v1/kit/cloak-and-dagger) kit makes you more mobile while increasing the effectiveness of your short-range strikes.

##### Equipment

You wear light armor and wield one or two light weapons.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) Bonus:** +3 per echelon

**Speed Bonus:** +2

**Melee Damage Bonus:** +1/+1/+1

**Ranged Damage Bonus:** +1/+1/+1

**Ranged Distance Bonus:** +5

**Disengage Bonus:** +1

##### Signature Ability

###### Fade

*A stab, and a few quick, careful steps back.*

| **Melee, Ranged, Strike, Weapon** |     **Main action** |
|-----------------------------------|--------------------:|
| **📏 Melee 1 or ranged 10**       | **🎯 One creature** |

**Power Roll + Might or Agility:**

- **≤11:** 3 + M or A damage; you can [shift](scc:mcdm.heroes.v1/movement/shifting) 1 square
- **12-16:** 6 + M or A damage; you can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares
- **17+:** 8 + M or A damage; you can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 3 squares

```ds-feature
distance: Melee 1 or ranged 10
effects:
    - effect: "*A stab, and a few quick, careful steps back.*\n\n| **Melee, Ranged, Strike, Weapon** |     **Main action** |\n|-----------------------------------|--------------------:|\n| **\U0001F4CF Melee 1 or ranged 10**       | **\U0001F3AF One creature** |\n\n**Power Roll + Might or Agility:**\n\n- **≤11:** 3 + M or A damage; you can [shift](scc:mcdm.heroes.v1/movement/shifting) 1 square\n- **12-16:** 6 + M or A damage; you can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares\n- **17+:** 8 + M or A damage; you can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 3 squares"
feature_type: ability
flavor: A stab, and a few quick, careful steps back.
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1 or ranged 10
    flavor: A stab, and a few quick, careful steps back.
    keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
    name: Fade
    subtype: signature
    target: One creature
    type: ability
name: Fade
target: One creature
type: feature
usage: Main action
```
