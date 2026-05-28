---
file_basename: raden
file_dpath: kit
item_id: raden
item_name: Raden
name: Raden
scc: mcdm.heroes.v1/kit/raden
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your [primordial ferocity](scc:mcdm.heroes.v1/feature.trait.fury.level-10/primordial-ferocity) into the form of a rat, becoming mobile and elusive. [Raden](scc:mcdm.heroes.v1/kit/raden) are associated with the wild nature of the rat, before cities became their habitat. This aspect is associated with the rat flood—a surge of corrupted water that draws forth hordes of rats.

##### Signature Ability

###### Driving Pounce

*Your enemies try in vain to fall back from your pouncing attack.*

| **Melee, Strike, Weapon** |               **Main action** |
|---------------------------|------------------------------:|
| **📏 Melee 1**            | **🎯 One creature or object** |

**Power Roll + Agility:**

- **≤11:** 4 + A damage
- **12-16:** 7 + A damage; push 1
- **17+:** 9 + A damage; push 2

**Effect:** You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to the same number of squares that you pushed the target.

```ds-feature
distance: Melee 1
effects:
    - effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to the same number of squares that you pushed the target.
    - roll: Power Roll + Agility
      tier1: 4 + A damage
      tier2: 7 + A damage; push 1
      tier3: 9 + A damage; push 2
feature_type: ability
flavor: Your enemies try in vain to fall back from your pouncing attack.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) up to the same number of squares that you pushed the target.
    flavor: Your enemies try in vain to fall back from your pouncing attack.
    keywords:
        - Melee
        - Strike
        - Weapon
    name: Driving Pounce
    power_roll_characteristic: Agility
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage
    tier2: 7 + A damage; push 1
    tier3: 9 + A damage; push 2
    type: ability
name: Driving Pounce
target: One creature or object
type: feature
usage: Main action
```
