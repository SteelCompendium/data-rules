---
file_basename: vuken
file_dpath: kit
item_id: vuken
item_name: Vuken
name: Vuken
scc: mcdm.heroes.v1/kit/vuken
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your primordial ferocity into the form of a wolf, becoming a fleet-footed hunter. Vuken are tied to forests and open steppes, and this aspect is associated with the thunderstorm.

##### Signature Ability

###### Unbalancing Attack

*A wild assault forces your foe onto their back.*

| **Melee, Strike, Weapon** |               **Main action** |
|---------------------------|------------------------------:|
| **📏 Melee 1**            | **🎯 One creature or object** |

**Power Roll + Might:**

- **≤11:** 4 + M damage; A < WEAK, prone
- **12-16:** 7 + M damage; A < AVERAGE, prone
- **17+:** 9 + M damage; A < STRONG, prone

```ds-feature
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 4 + M damage; A < WEAK, prone
      tier2: 7 + M damage; A < AVERAGE, prone
      tier3: 9 + M damage; A < STRONG, prone
feature_type: ability
flavor: A wild assault forces your foe onto their back.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    flavor: A wild assault forces your foe onto their back.
    keywords:
        - Melee
        - Strike
        - Weapon
    name: Unbalancing Attack
    power_roll_characteristic: Might
    subtype: signature
    target: One creature or object
    tier1: 4 + M damage; A < WEAK, prone
    tier2: 7 + M damage; A < AVERAGE, prone
    tier3: 9 + M damage; A < STRONG, prone
    type: ability
name: Unbalancing Attack
target: One creature or object
type: feature
usage: Main action
```
