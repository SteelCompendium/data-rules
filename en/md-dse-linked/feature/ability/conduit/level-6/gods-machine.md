---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: Ranged 10
effect: You conjure a size 2 rolling machine that appears in an unoccupied space within distance. The machine has 50 [Stamina](../../../../rule/health/stamina.md) and immunity all to poison and psychic damage. It disappears at the end of the encounter, if its [Stamina](../../../../rule/health/stamina.md) drops to 0, or if you are [dying](../../../../rule/health/dying.md). When the machine first appears, make the following power roll once, targeting each enemy adjacent to it.
feature_type: ability
file_basename: gods-machine
file_dpath: feature/ability/conduit/level-6
flavor: You conjure a whirring tank made of blades and metal.
item_id: gods-machine
item_name: Gods' Machine
keywords:
    - Magic
    - Ranged
level: "6"
name: Gods' Machine
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/gods-machine
source: mcdm.heroes.v1
target: Special
tier1: 3 damage
tier2: 5 damage
tier3: 8 damage
type: ability
---

```ds-feature
cost: 9 Piety
distance: Ranged 10
effects:
    - effect: You conjure a size 2 rolling machine that appears in an unoccupied space within distance. The machine has 50 [Stamina](../../../../rule/health/stamina.md) and immunity all to poison and psychic damage. It disappears at the end of the encounter, if its [Stamina](../../../../rule/health/stamina.md) drops to 0, or if you are [dying](../../../../rule/health/dying.md). When the machine first appears, make the following power roll once, targeting each enemy adjacent to it.
    - roll: Power Roll + Intuition
      tier1: 3 damage
      tier2: 5 damage
      tier3: 8 damage
feature_type: ability
flavor: You conjure a whirring tank made of blades and metal.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: Ranged 10
    effect: You conjure a size 2 rolling machine that appears in an unoccupied space within distance. The machine has 50 [Stamina](../../../../rule/health/stamina.md) and immunity all to poison and psychic damage. It disappears at the end of the encounter, if its [Stamina](../../../../rule/health/stamina.md) drops to 0, or if you are [dying](../../../../rule/health/dying.md). When the machine first appears, make the following power roll once, targeting each enemy adjacent to it.
    flavor: You conjure a whirring tank made of blades and metal.
    keywords:
        - Magic
        - Ranged
    level: "6"
    name: Gods' Machine
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/gods-machine
    target: Special
    tier1: 3 damage
    tier2: 5 damage
    tier3: 8 damage
    type: ability
name: Gods' Machine
target: Special
type: feature
usage: Main action
```
