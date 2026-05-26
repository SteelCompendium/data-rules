---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield a polearm.
file_basename: stick-and-robe
file_dpath: kit
item_id: stick-and-robe
item_name: Stick and Robe
melee_damage_bonus: +1/+1/+1
melee_distance_bonus: "+1"
name: Stick and Robe
scc: mcdm.heroes.v1/kit/stick-and-robe
source: mcdm.heroes.v1
speed_bonus: "+2"
stamina_bonus: +3 per echelon
type: kit
---

Armed with a simple reach weapon, often a quarterstaff, a character using the [Stick and Robe](scc:mcdm.heroes.v1/kit/stick-and-robe) kit is highly mobile thanks to their light armor. This allows your hero to make maximum use of their weapon's length.

##### Equipment

You wear light armor and wield a polearm.

##### Kit Bonuses

**Stamina Bonus:** +3 per echelon

**Speed Bonus:** +2

**Melee Damage Bonus:** +1/+1/+1

**Melee Distance Bonus:** +1

**Disengage Bonus:** +1

##### Signature Ability

###### Where I Want You

*When your stick speaks, your enemy moves.*

| **Melee, Strike, Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 Melee 2**            | **🎯 One creature** |

**Power Roll + Might or Agility:**

- **≤11:** 4 + M or A damage
- **12-16:** 7 + M or A damage; slide 1
- **17+:** 10 + M or A damage; slide 3

```ds-feature
distance: Melee 2
effects:
    - effect: "*When your stick speaks, your enemy moves.*\n\n| **Melee, Strike, Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF Melee 2**            | **\U0001F3AF One creature** |\n\n**Power Roll + Might or Agility:**\n\n- **≤11:** 4 + M or A damage\n- **12-16:** 7 + M or A damage; slide 1\n- **17+:** 10 + M or A damage; slide 3"
feature_type: ability
flavor: When your stick speaks, your enemy moves.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 2
    flavor: When your stick speaks, your enemy moves.
    keywords:
        - Melee
        - Strike
        - Weapon
    name: Where I Want You
    subtype: signature
    target: One creature
    type: ability
name: Where I Want You
target: One creature
type: feature
usage: Main action
```
