---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield a polearm.
file_basename: stick-and-robe
file_dpath: kit
item_id: stick-and-robe
item_name: Stick and Robe
melee_damage_bonus: +1/+1/+1
name: Stick and Robe
scc: mcdm.heroes.v1/kit/stick-and-robe
source: mcdm.heroes.v1
speed_bonus: "+2"
type: kit
---

Armed with a simple reach weapon, often a quarterstaff, a character using the [Stick and Robe](scc:mcdm.heroes.v1/kit/stick-and-robe) kit is highly mobile thanks to their light armor. This allows your hero to make maximum use of their weapon's length.

##### Equipment

You wear light armor and wield a polearm.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) Bonus:** +3 per echelon

**Speed Bonus:** +2

**Melee Damage Bonus:** +1/+1/+1

**Melee [Distance](scc:mcdm.heroes.v1/rule.combat/distance) Bonus:** +1

**Disengage Bonus:** +1

##### Signature Ability

###### Where I Want You

*When your stick speaks, your enemy moves.*

| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 Melee 2**            | **🎯 One creature** |

**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 + M or A damage
- **12-16:** 7 + M or A damage; slide 1
- **17+:** 10 + M or A damage; slide 3

```ds-feature
distance: Melee 2
effects:
    - effect: "*When your stick speaks, your enemy moves.*\n\n| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF Melee 2**            | **\U0001F3AF One creature** |\n\n**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + M or A damage\n- **12-16:** 7 + M or A damage; slide 1\n- **17+:** 10 + M or A damage; slide 3"
feature_type: ability
flavor: When your stick speaks, your enemy moves.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 2
    flavor: When your stick speaks, your enemy moves.
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
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
