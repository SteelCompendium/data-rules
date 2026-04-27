---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield several ensnaring weapons and a polearm.
file_basename: retiarius
file_dpath: kit
item_id: retiarius
item_name: Retiarius
melee_damage_bonus: +2/+2/+2
melee_distance_bonus: "+1"
name: Retiarius
scc: mcdm.heroes.v1/kit/retiarius
source: mcdm.heroes.v1
speed_bonus: "+1"
stamina_bonus: +3 per echelon
type: kit
---

The retiarius is often depicted as a lightly armored warrior with a net in one hand and a trident in the other, and this kit gives you the equipment and fighting technique to make that happen. Tie up your foe with a net and then poke them to death!

##### Equipment

You wear light armor and wield several ensnaring weapons and a polearm.

##### Kit Bonuses

**Stamina Bonus:** +3 per echelon

**Speed Bonus:** +1

**Melee Damage Bonus:** +2/+2/+2

**Melee Distance Bonus:** +1

**Disengage Bonus:** +1

##### Signature Ability

###### Net and Stab

*The well-thrown net that follows your main attack leaves your foes right where you want them.*

| **Melee, Strike, Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 Melee 2**            | **🎯 One creature** |

**Power Roll + Might or Agility:**

- **≤11:** 4 + M or A damage; A < WEAK, slowed (EoT)
- **12-16:** 6 + M or A damage; A < AVERAGE, slowed (EoT)
- **17+:** 8 + M or A damage; A < STRONG, restrained (EoT)

```ds-feature
distance: Melee 2
effects:
    - effect: "*The well-thrown net that follows your main attack leaves your foes right where you want them.*\n\n| **Melee, Strike, Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF Melee 2**            | **\U0001F3AF One creature** |\n\n**Power Roll + Might or Agility:**\n\n- **≤11:** 4 + M or A damage; A < WEAK, slowed (EoT)\n- **12-16:** 6 + M or A damage; A < AVERAGE, slowed (EoT)\n- **17+:** 8 + M or A damage; A < STRONG, restrained (EoT)"
feature_type: ability
flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 2
    flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
    keywords:
        - Melee
        - Strike
        - Weapon
    name: Net and Stab
    subtype: signature
    target: One creature
    type: ability
name: Net and Stab
target: One creature
type: feature
usage: Main action
```
