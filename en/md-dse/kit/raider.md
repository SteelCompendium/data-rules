---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield a shield and a light weapon.
file_basename: raider
file_dpath: kit
item_id: raider
item_name: Raider
melee_damage_bonus: +1/+1/+1
name: Raider
ranged_damage_bonus: +1/+1/+1
ranged_distance_bonus: "+5"
scc: mcdm.heroes.v1/kit/raider
source: mcdm.heroes.v1
speed_bonus: "+1"
stamina_bonus: +6 per echelon
type: kit
---

The Raider kit keeps you protected while granting you full mobility, providing a boost to speed and distance that lets you run around the battlefield like a Viking warrior.

##### Equipment

You wear light armor and wield a shield and a light weapon.

##### Kit Bonuses

**Stamina Bonus:** +6 per echelon

**Speed Bonus:** +1

**Melee Damage Bonus:** +1/+1/+1

**Ranged Damage Bonus:** +1/+1/+1

**Ranged Distance Bonus:** +5

**Disengage Bonus:** +1

##### Signature Ability

```ds-feature
distance: Melee 1 or ranged 10
effects:
    - effect: The target takes a bane on their next power roll made before the end of their next turn.
feature_type: ability
flavor: You execute a brutal strike that leaves your foe reeling. (Previously known as "Shock and Awe")
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1 or ranged 10
    effect: The target takes a bane on their next power roll made before the end of their next turn.
    flavor: You execute a brutal strike that leaves your foe reeling. (Previously known as "Shock and Awe")
    keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
    name: Raider's Awe
    subtype: signature
    target: One creature
    type: ability
name: Raider's Awe
target: One creature
type: feature
usage: Main action
```
