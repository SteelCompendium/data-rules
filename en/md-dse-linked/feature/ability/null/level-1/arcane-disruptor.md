---
action_type: Main action
class: "null"
cost: 5 Discipline
cost_amount: "5"
cost_resource: Discipline
distance: Melee 1
effect: While weakened this way, the target takes damage equal to your Intuition score whenever they use a supernatural ability that costs Malice.
feature_type: ability
file_basename: arcane-disruptor
file_dpath: feature/ability/null/level-1
flavor: Your blow reorders a foe's body, causing pain if they attempt to channel sorcery.
item_id: arcane-disruptor
item_name: Arcane Disruptor
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
level: "1"
name: Arcane Disruptor
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.null.level-1/arcane-disruptor
source: mcdm.heroes.v1
target: One creature
tier1: 8 + **A** psychic damage; M < WEAK, weakened (save ends)
tier2: 12 + **A** psychic damage; M < AVERAGE, weakened (save ends)
tier3: 16 + **A** psychic damage; M < STRONG, weakened (save ends)
type: ability
---

```ds-feature
cost: 5 Discipline
distance: Melee 1
effects:
    - effect: While weakened this way, the target takes damage equal to your Intuition score whenever they use a supernatural ability that costs Malice.
    - roll: Power Roll + Agility
      tier1: 8 + **A** psychic damage; M < WEAK, weakened (save ends)
      tier2: 12 + **A** psychic damage; M < AVERAGE, weakened (save ends)
      tier3: 16 + **A** psychic damage; M < STRONG, weakened (save ends)
feature_type: ability
flavor: Your blow reorders a foe's body, causing pain if they attempt to channel sorcery.
keywords:
    - Melee
    - Psionic
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 5 Discipline
    distance: Melee 1
    effect: While weakened this way, the target takes damage equal to your Intuition score whenever they use a supernatural ability that costs Malice.
    flavor: Your blow reorders a foe's body, causing pain if they attempt to channel sorcery.
    keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
    level: "1"
    name: Arcane Disruptor
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.null.level-1/arcane-disruptor
    target: One creature
    tier1: 8 + **A** psychic damage; M < WEAK, weakened (save ends)
    tier2: 12 + **A** psychic damage; M < AVERAGE, weakened (save ends)
    tier3: 16 + **A** psychic damage; M < STRONG, weakened (save ends)
    type: ability
name: Arcane Disruptor
target: One creature
type: feature
usage: Main action
```
