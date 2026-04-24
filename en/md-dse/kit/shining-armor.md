---
equipment_text: You wear heavy armor and wield a shield and a medium weapon.
file_basename: shining-armor
file_dpath: kit
item_id: shining-armor
item_name: Shining Armor
melee_damage_bonus: +2/+2/+2
name: Shining Armor
scc: mcdm.heroes.v1/kit/shining-armor
source: mcdm.heroes.v1
stability_bonus: "+1"
stamina_bonus: +12 per echelon
type: kit
---

The Shining Armor kit provides the most protection a kit can afford, providing you with the sword, shield, and armor necessary to play the prototypical knight.

##### Equipment

You wear heavy armor and wield a shield and a medium weapon.

##### Kit Bonuses

**Stamina Bonus:** +12 per echelon

**Stability Bonus:** +1

**Melee Damage Bonus:** +2/+2/+2

##### Signature Ability

```ds-feature
distance: Melee 1
effects:
    - effect: The target is taunted until the end of their next turn.
feature_type: ability
flavor: The strength of your assault makes it impossible for your foe to ignore you.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    effect: The target is taunted until the end of their next turn.
    flavor: The strength of your assault makes it impossible for your foe to ignore you.
    keywords:
        - Melee
        - Strike
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
