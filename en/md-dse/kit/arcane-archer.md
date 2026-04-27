---
disengage_bonus: "+1"
equipment_text: You wear no armor and wield a bow.
file_basename: arcane-archer
file_dpath: kit
item_id: arcane-archer
item_name: Arcane Archer
name: Arcane Archer
ranged_damage_bonus: +2/+2/+2
ranged_distance_bonus: "+10"
scc: mcdm.heroes.v1/kit/arcane-archer
source: mcdm.heroes.v1
speed_bonus: "+1"
type: kit
---

The Arcane Archer kit allows you to combine magic and ranged weapon strikes. Your lack of armor keeps you mobile, and your magic makes your arrows explode to devastate your foes.

##### Equipment

You wear no armor and wield a bow.

##### Kit Bonuses

**Speed Bonus:** +1

**Ranged Damage Bonus:** +2/+2/+2

**Ranged Distance Bonus:** +10

**Disengage Bonus:** +1

##### Signature Ability

###### Exploding Arrow

*Your ammunition explodes with magical energy.*

| **Magic, Ranged, Strike, Weapon** |               **Main action** |
|-----------------------------------|------------------------------:|
| **📏 Ranged 15**                  | **🎯 One creature or object** |

**Power Roll + Agility, Reason, Intuition, or Presence:**

- **≤11:** 5 + A, R, I, or P fire damage
- **12-16:** 7 + A, R, I, or P fire damage
- **17+:** 10 + A, R, I, or P fire damage

**Effect:** One creature or object of your choice within 2 squares of the target takes fire damage equal to the characteristic score used for this ability's power roll.

```ds-feature
distance: Ranged 15
effects:
    - effect: One creature or object of your choice within 2 squares of the target takes fire damage equal to the characteristic score used for this ability's power roll.
feature_type: ability
flavor: Your ammunition explodes with magical energy.
keywords:
    - Magic
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Ranged 15
    effect: One creature or object of your choice within 2 squares of the target takes fire damage equal to the characteristic score used for this ability's power roll.
    flavor: Your ammunition explodes with magical energy.
    keywords:
        - Magic
        - Ranged
        - Strike
        - Weapon
    name: Exploding Arrow
    subtype: signature
    target: One creature or object
    type: ability
name: Exploding Arrow
target: One creature or object
type: feature
usage: Main action
```
