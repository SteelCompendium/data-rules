---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: Ranged 10
feature_type: ability
file_basename: the-gods-command-you-obey
file_dpath: feature/ability/conduit/level-2
flavor: You speak with the voice of your saint, commanding your enemies.
item_id: the-gods-command-you-obey
item_name: The Gods Command You Obey
keywords:
    - Magic
    - Ranged
    - Strike
level: "2"
name: The Gods Command You Obey
power_roll_characteristic: Intuition
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/the-gods-command-you-obey
source: mcdm.heroes.v1
target: One creature
tier1: 4 + I holy damage; P < WEAK, before taking damage, the target makes a [free strike](../../../common/main-actions/free-strike.md) against a target you choose
tier2: 7 + I holy damage; P < AVERAGE, before taking damage, the target uses an ability of your choice and you choose any targets for that ability
tier3: 11 + I holy damage; P < STRONG, before taking damage, the target shifts up to their speed to a location you choose, uses an ability of your choice, and you choose any targets for that ability
type: ability
---

```ds-feature
cost: 5 Piety
distance: Ranged 10
effects:
    - roll: Power Roll + Intuition
      tier1: 4 + I holy damage; P < WEAK, before taking damage, the target makes a [free strike](../../../common/main-actions/free-strike.md) against a target you choose
      tier2: 7 + I holy damage; P < AVERAGE, before taking damage, the target uses an ability of your choice and you choose any targets for that ability
      tier3: 11 + I holy damage; P < STRONG, before taking damage, the target shifts up to their speed to a location you choose, uses an ability of your choice, and you choose any targets for that ability
feature_type: ability
flavor: You speak with the voice of your saint, commanding your enemies.
keywords:
    - Magic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: Ranged 10
    flavor: You speak with the voice of your saint, commanding your enemies.
    keywords:
        - Magic
        - Ranged
        - Strike
    level: "2"
    name: The Gods Command You Obey
    power_roll_characteristic: Intuition
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/the-gods-command-you-obey
    target: One creature
    tier1: 4 + I holy damage; P < WEAK, before taking damage, the target makes a [free strike](../../../common/main-actions/free-strike.md) against a target you choose
    tier2: 7 + I holy damage; P < AVERAGE, before taking damage, the target uses an ability of your choice and you choose any targets for that ability
    tier3: 11 + I holy damage; P < STRONG, before taking damage, the target shifts up to their speed to a location you choose, uses an ability of your choice, and you choose any targets for that ability
    type: ability
name: The Gods Command You Obey
target: One creature
type: feature
usage: Main action
```
