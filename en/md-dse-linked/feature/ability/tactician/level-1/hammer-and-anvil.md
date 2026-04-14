---
action_type: Main action
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: Melee 1 or ranged 5
effect: If the target is reduced to 0 Stamina before one or both chosen allies has made their strike, the ally or allies can pick a different target.
feature_type: ability
file_basename: hammer-and-anvil
file_dpath: feature/ability/tactician/level-1
flavor: '"Let''s not argue about who''s the hammer and who''s the anvil!"'
item_id: hammer-and-anvil
item_name: Hammer and Anvil
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "1"
name: Hammer and Anvil
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/hammer-and-anvil
source: mcdm.heroes.v1
target: One creature or object
tier1: 5 + M damage; one ally within 10 squares of you can use a strike signature ability against the target as a free triggered action
tier2: 9 + M damage; one ally within 10 squares of you can use a strike signature ability that gains an edge against the target as a free triggered action
tier3: 12 + M damage; two allies within 10 squares of you can each use a strike signature ability that gains an edge against the target as a free triggered action
type: ability
---

```ds-feature
cost: 5 Focus
distance: Melee 1 or ranged 5
effects:
    - effect: If the target is reduced to 0 Stamina before one or both chosen allies has made their strike, the ally or allies can pick a different target.
    - roll: Power Roll + Might
      tier1: 5 + M damage; one ally within 10 squares of you can use a strike signature ability against the target as a free triggered action
      tier2: 9 + M damage; one ally within 10 squares of you can use a strike signature ability that gains an edge against the target as a free triggered action
      tier3: 12 + M damage; two allies within 10 squares of you can each use a strike signature ability that gains an edge against the target as a free triggered action
feature_type: ability
flavor: '"Let''s not argue about who''s the hammer and who''s the anvil!"'
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 5 Focus
    distance: Melee 1 or ranged 5
    effect: If the target is reduced to 0 Stamina before one or both chosen allies has made their strike, the ally or allies can pick a different target.
    flavor: '"Let''s not argue about who''s the hammer and who''s the anvil!"'
    keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "1"
    name: Hammer and Anvil
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/hammer-and-anvil
    target: One creature or object
    tier1: 5 + M damage; one ally within 10 squares of you can use a strike signature ability against the target as a free triggered action
    tier2: 9 + M damage; one ally within 10 squares of you can use a strike signature ability that gains an edge against the target as a free triggered action
    tier3: 12 + M damage; two allies within 10 squares of you can each use a strike signature ability that gains an edge against the target as a free triggered action
    type: ability
name: Hammer and Anvil
target: One creature or object
type: feature
usage: Main action
```
