---
action_type: Main action
class: conduit
cost: 7 Piety
cost_amount: "7"
cost_resource: Piety
distance: Ranged 10
effect: One ally within distance can spend any number of [Recoveries](../../../../rule/health/recoveries.md).
feature_type: ability
file_basename: soul-siphon
file_dpath: feature/ability/conduit/level-3
flavor: A beam of energy connects a foe to a friend, draining life from one to heal the other.
item_id: soul-siphon
item_name: Soul Siphon
keywords:
    - Magic
    - Ranged
    - Strike
level: "3"
name: Soul Siphon
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-3/soul-siphon
source: mcdm.heroes.v1
target: One enemy
tier1: 7 + I corruption damage
tier2: 10 + I corruption damage
tier3: 15 + I corruption damage
type: ability
---

```ds-feature
cost: 7 Piety
distance: Ranged 10
effects:
    - effect: One ally within distance can spend any number of [Recoveries](../../../../rule/health/recoveries.md).
    - roll: Power Roll + Intuition
      tier1: 7 + I corruption damage
      tier2: 10 + I corruption damage
      tier3: 15 + I corruption damage
feature_type: ability
flavor: A beam of energy connects a foe to a friend, draining life from one to heal the other.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    cost: 7 Piety
    distance: Ranged 10
    effect: One ally within distance can spend any number of [Recoveries](../../../../rule/health/recoveries.md).
    flavor: A beam of energy connects a foe to a friend, draining life from one to heal the other.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "3"
    name: Soul Siphon
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-3/soul-siphon
    target: One enemy
    tier1: 7 + I corruption damage
    tier2: 10 + I corruption damage
    tier3: 15 + I corruption damage
    type: ability
name: Soul Siphon
target: One enemy
type: feature
usage: Main action
```
