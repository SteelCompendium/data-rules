---
action_type: Main action
class: conduit
distance: Ranged 10
effect: Choose yourself or one ally within distance. That character can impose a bane on one power roll made against them before the end of their next turn.
feature_type: ability
file_basename: sacrificial-offer
file_dpath: feature/ability/conduit/level-1
flavor: Divine magic tears at your foe and defends a nearby friend.
item_id: sacrificial-offer
item_name: Sacrificial Offer
keywords:
    - Magic
    - Ranged
    - Strike
level: "1"
name: Sacrificial Offer
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/sacrificial-offer
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + I corruption damage
tier2: 4 + I corruption damage
tier3: 6 + I corruption damage
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: Choose yourself or one ally within distance. That character can impose a bane on one power roll made against them before the end of their next turn.
    - roll: Power Roll + Intuition
      tier1: 2 + I corruption damage
      tier2: 4 + I corruption damage
      tier3: 6 + I corruption damage
feature_type: ability
flavor: Divine magic tears at your foe and defends a nearby friend.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    distance: Ranged 10
    effect: Choose yourself or one ally within distance. That character can impose a bane on one power roll made against them before the end of their next turn.
    flavor: Divine magic tears at your foe and defends a nearby friend.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "1"
    name: Sacrificial Offer
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/sacrificial-offer
    subtype: signature
    target: One creature
    tier1: 2 + I corruption damage
    tier2: 4 + I corruption damage
    tier3: 6 + I corruption damage
    type: ability
name: Sacrificial Offer
target: One creature
type: feature
usage: Main action
```
