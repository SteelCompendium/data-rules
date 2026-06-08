---
equipment_text: You wear medium armor and wield a polearm.
file_basename: guisarmier
file_dpath: kit
item_id: guisarmier
item_name: Guisarmier
melee_damage_bonus: +2/+2/+2
melee_distance_bonus: "+1"
name: Guisarmier
scc: mcdm.heroes.v1/kit/guisarmier
source: mcdm.heroes.v1
stability_bonus: "+1"
type: kit
---

The [Guisarmier](scc:mcdm.heroes.v1/kit/guisarmier) kit is for those who want to use a polearm for extended reach while remaining protected by sturdy armor. This is the kit that allows you to become the ultimate halberd, longspear, or glaive fighter.

##### Equipment

You wear medium armor and wield a polearm.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) Bonus:** +6 per echelon

**Stability Bonus:** +1

**Melee Damage Bonus:** +2/+2/+2

**Melee Distance Bonus:** +1

##### Signature Ability

###### Forward Thrust, Backward Smash

*In your hands, the haft is as good as the head.*

| **Melee, Strike, Weapon** |                 **Main action** |
|---------------------------|--------------------------------:|
| **📏 Melee 2**            | **🎯 Two creatures or objects** |

**Power Roll + Might or Agility:**

- **≤11:** 4 damage
- **12-16:** 7 damage
- **17+:** 9 damage

```ds-feature
distance: Melee 2
effects:
    - effect: "*In your hands, the haft is as good as the head.*\n\n| **Melee, Strike, Weapon** |                 **Main action** |\n|---------------------------|--------------------------------:|\n| **\U0001F4CF Melee 2**            | **\U0001F3AF Two creatures or objects** |\n\n**Power Roll + Might or Agility:**\n\n- **≤11:** 4 damage\n- **12-16:** 7 damage\n- **17+:** 9 damage"
feature_type: ability
flavor: In your hands, the haft is as good as the head.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 2
    flavor: In your hands, the haft is as good as the head.
    keywords:
        - Melee
        - Strike
        - Weapon
    name: Forward Thrust, Backward Smash
    subtype: signature
    target: Two creatures or objects
    type: ability
name: Forward Thrust, Backward Smash
target: Two creatures or objects
type: feature
usage: Main action
```
