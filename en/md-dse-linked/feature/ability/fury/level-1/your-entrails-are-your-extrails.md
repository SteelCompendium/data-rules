---
action_type: Main action
class: fury
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: Melee 1
effect: While [bleeding](../../../../condition/bleeding.md) this way, the target takes damage equal to your Might score at the end of each of your turns.
feature_type: ability
file_basename: your-entrails-are-your-extrails
file_dpath: feature/ability/fury/level-1
flavor: Hard for them to fight when they're busy holding in their giblets.
item_id: your-entrails-are-your-extrails
item_name: Your Entrails Are Your Extrails!
keywords:
    - Melee
    - Strike
    - Weapon
level: "1"
name: Your Entrails Are Your Extrails!
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-1/your-entrails-are-your-extrails
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + M damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
tier2: 5 + M damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
tier3: 8 + M damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: Melee 1
effects:
    - effect: While [bleeding](../../../../condition/bleeding.md) this way, the target takes damage equal to your Might score at the end of each of your turns.
    - roll: Power Roll + Might
      tier1: 3 + M damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier2: 5 + M damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier3: 8 + M damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
feature_type: ability
flavor: Hard for them to fight when they're busy holding in their giblets.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 3 Ferocity
    distance: Melee 1
    effect: While [bleeding](../../../../condition/bleeding.md) this way, the target takes damage equal to your Might score at the end of each of your turns.
    flavor: Hard for them to fight when they're busy holding in their giblets.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Your Entrails Are Your Extrails!
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/your-entrails-are-your-extrails
    target: One creature or object
    tier1: 3 + M damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
    tier2: 5 + M damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
    tier3: 8 + M damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    type: ability
name: Your Entrails Are Your Extrails!
target: One creature or object
type: feature
usage: Main action
```
