---
action_type: Main action
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: Melee 1
effect: While suppressed, a target takes psychic damage equal to twice your Intuition score at the start of their turns, whenever they use a supernatural ability, or whenever they use an ability that costs Malice.
feature_type: ability
file_basename: arcane-purge
file_dpath: feature/ability/null/level-8
flavor: You focus your null field into a pressure point strike that prevents your foe from channeling sorcery.
item_id: arcane-purge
item_name: Arcane Purge
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
level: "8"
name: Arcane Purge
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.null.level-8/arcane-purge
source: mcdm.heroes.v1
target: One creature
tier1: 13 + A damage; M < WEAK, the target is suppressed (save ends)
tier2: 19 + A damage; M < AVERAGE, the target is suppressed (save ends)
tier3: 24 + A damage; M < STRONG, the target is suppressed (save ends)
type: ability
---

```ds-feature
cost: 11 Discipline
distance: Melee 1
effects:
    - effect: While suppressed, a target takes psychic damage equal to twice your Intuition score at the start of their turns, whenever they use a supernatural ability, or whenever they use an ability that costs Malice.
    - roll: Power Roll + Agility
      tier1: 13 + A damage; M < WEAK, the target is suppressed (save ends)
      tier2: 19 + A damage; M < AVERAGE, the target is suppressed (save ends)
      tier3: 24 + A damage; M < STRONG, the target is suppressed (save ends)
feature_type: ability
flavor: You focus your null field into a pressure point strike that prevents your foe from channeling sorcery.
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 11 Discipline
    distance: Melee 1
    effect: While suppressed, a target takes psychic damage equal to twice your Intuition score at the start of their turns, whenever they use a supernatural ability, or whenever they use an ability that costs Malice.
    flavor: You focus your null field into a pressure point strike that prevents your foe from channeling sorcery.
    keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
    level: "8"
    name: Arcane Purge
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.null.level-8/arcane-purge
    target: One creature
    tier1: 13 + A damage; M < WEAK, the target is suppressed (save ends)
    tier2: 19 + A damage; M < AVERAGE, the target is suppressed (save ends)
    tier3: 24 + A damage; M < STRONG, the target is suppressed (save ends)
    type: ability
name: Arcane Purge
target: One creature
type: feature
usage: Main action
```
