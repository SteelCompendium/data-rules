---
action_type: Maneuver
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: Melee 1 or ranged 10
effect: Choose one ally within distance. While the target is affected by this ability, each time they use an ability, that ally can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them after the ability is resolved.
feature_type: ability
file_basename: epic
file_dpath: feature/ability/troubadour/level-9
flavor: Your story tells a tale of the villain's waning power and how the heroes rose to the occasion to stop them.
item_id: epic
item_name: Epic
keywords:
    - Magic
    - Melee
    - Ranged
level: "9"
name: Epic
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/epic
source: mcdm.heroes.v1
target: One creature
tier1: The target takes a bane on ability rolls (save ends).
tier2: The target has a double bane on ability rolls (save ends).
tier3: The target has a double bane on power rolls (save ends).
type: ability
---

```ds-feature
cost: 11 Drama
distance: Melee 1 or ranged 10
effects:
    - effect: Choose one ally within distance. While the target is affected by this ability, each time they use an ability, that ally can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them after the ability is resolved.
    - roll: Power Roll + Presence
      tier1: The target takes a bane on ability rolls (save ends).
      tier2: The target has a double bane on ability rolls (save ends).
      tier3: The target has a double bane on power rolls (save ends).
feature_type: ability
flavor: Your story tells a tale of the villain's waning power and how the heroes rose to the occasion to stop them.
keywords:
    - Magic
    - Melee
    - Ranged
metadata:
    action_type: Maneuver
    class: troubadour
    cost: 11 Drama
    distance: Melee 1 or ranged 10
    effect: Choose one ally within distance. While the target is affected by this ability, each time they use an ability, that ally can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them after the ability is resolved.
    flavor: Your story tells a tale of the villain's waning power and how the heroes rose to the occasion to stop them.
    keywords:
        - Magic
        - Melee
        - Ranged
    level: "9"
    name: Epic
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/epic
    target: One creature
    tier1: The target takes a bane on ability rolls (save ends).
    tier2: The target has a double bane on ability rolls (save ends).
    tier3: The target has a double bane on power rolls (save ends).
    type: ability
name: Epic
target: One creature
type: feature
usage: Maneuver
```
