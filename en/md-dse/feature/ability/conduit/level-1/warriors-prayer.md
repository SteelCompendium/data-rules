---
action_type: Main action
class: conduit
distance: Ranged 10
effect: You or one ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) gains [temporary Stamina](scc:mcdm.heroes.v1/rule.health/temporary-stamina) equal to your [Intuition](scc:mcdm.heroes.v1/rule.character/intuition) score.
feature_type: ability
file_basename: warriors-prayer
file_dpath: feature/ability/conduit/level-1
flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in melee.
item_id: warriors-prayer
item_name: Warrior's Prayer
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Warrior's Prayer
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/warriors-prayer
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: You or one ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) gains [temporary Stamina](scc:mcdm.heroes.v1/rule.health/temporary-stamina) equal to your [Intuition](scc:mcdm.heroes.v1/rule.character/intuition) score.
feature_type: ability
flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in melee.
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    distance: Ranged 10
    effect: You or one ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) gains [temporary Stamina](scc:mcdm.heroes.v1/rule.health/temporary-stamina) equal to your [Intuition](scc:mcdm.heroes.v1/rule.character/intuition) score.
    flavor: Your quickly uttered prayer lends aggressive divine energy to a friend engaged in melee.
    keywords:
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Warrior's Prayer
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/warriors-prayer
    subtype: signature
    target: One creature
    type: ability
name: Warrior's Prayer
target: One creature
type: feature
usage: Main action
```
