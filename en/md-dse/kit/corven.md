---
file_basename: corven
file_dpath: kit
item_id: corven
item_name: Corven
name: Corven
scc: mcdm.heroes.v1/kit/corven
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your [primordial ferocity](scc:mcdm.heroes.v1/feature.fury.level-10/primordial-ferocity) into the form of a crow, becoming stealthy and quick. [Corven](scc:mcdm.heroes.v1/kit/corven) are tied to the mountain passes and the hot winds that flow through them. This aspect is associated with the warm and fast-rising anabatic wind.

##### Signature Ability

###### Wing Buffet

*Foes who try to close in around you do so at their peril.*

| **Area, Melee, Weapon** |               **Main action** |
|-------------------------|------------------------------:|
| **📏 1 burst**          | **🎯 Each enemy in the area** |

**Power Roll + Agility:**

- **≤11:** 3 damage
- **12-16:** 6 damage
- **17+:** 8 damage

**Effect:** You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the power roll.

```ds-feature
distance: 1 burst
effects:
    - effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the power roll.
    - roll: Power Roll + Agility
      tier1: 3 damage
      tier2: 6 damage
      tier3: 8 damage
feature_type: ability
flavor: Foes who try to close in around you do so at their peril.
keywords:
    - Area
    - Melee
    - Weapon
metadata:
    action_type: Main action
    distance: 1 burst
    effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the power roll.
    flavor: Foes who try to close in around you do so at their peril.
    keywords:
        - Area
        - Melee
        - Weapon
    name: Wing Buffet
    power_roll_characteristic: Agility
    subtype: signature
    target: Each enemy in the area
    tier1: 3 damage
    tier2: 6 damage
    tier3: 8 damage
    type: ability
name: Wing Buffet
target: Each enemy in the area
type: feature
usage: Main action
```
