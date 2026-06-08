---
disengage_bonus: "+1"
equipment_text: You wear medium armor and wield a light weapon and a medium weapon.
file_basename: dual-wielder
file_dpath: kit
item_id: dual-wielder
item_name: Dual Wielder
melee_damage_bonus: +2/+2/+2
name: Dual Wielder
scc: mcdm.heroes.v1/kit/dual-wielder
source: mcdm.heroes.v1
speed_bonus: "+2"
type: kit
---

The [Dual Wielder](scc:mcdm.heroes.v1/kit/dual-wielder) kit is for folks who want to excel at using two weapons at the same time. Your fighting style maximizes the power of each weapon you have in hand, making you a whirling dealer of death.

##### Equipment

You wear medium armor and wield a light weapon and a medium weapon.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) Bonus:** +6 per echelon

**Speed Bonus:** +2

**Melee Damage Bonus:** +2/+2/+2

**Disengage Bonus:** +1

##### Signature Ability

###### Double Strike

*Why strike once when you could do it twice?*

| **Melee, Strike, Weapon** |                 **Main action** |
|---------------------------|--------------------------------:|
| **📏 Melee 1**            | **🎯 Two creatures or objects** |

**Power Roll + Might or Agility:**

- **≤11:** 4 damage
- **12-16:** 6 damage
- **17+:** 8 damage

**Effect:** If you use this ability on your turn, you can use it against one target, then use your maneuver and your move action for that turn before using the ability against a second target. You still use the same power roll for both targets.

```ds-feature
distance: Melee 1
effects:
    - effect: If you use this ability on your turn, you can use it against one target, then use your maneuver and your move action for that turn before using the ability against a second target. You still use the same power roll for both targets.
feature_type: ability
flavor: Why strike once when you could do it twice?
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    effect: If you use this ability on your turn, you can use it against one target, then use your maneuver and your move action for that turn before using the ability against a second target. You still use the same power roll for both targets.
    flavor: Why strike once when you could do it twice?
    keywords:
        - Melee
        - Strike
        - Weapon
    name: Double Strike
    subtype: signature
    target: Two creatures or objects
    type: ability
name: Double Strike
target: Two creatures or objects
type: feature
usage: Main action
```
