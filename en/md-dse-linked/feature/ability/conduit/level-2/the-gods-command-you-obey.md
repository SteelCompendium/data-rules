---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
feature_type: ability
file_basename: the-gods-command-you-obey
file_dpath: feature/ability/conduit/level-2
flavor: You speak with the voice of your [saint](../../../../rule/world/saint.md), commanding your enemies.
item_id: the-gods-command-you-obey
item_name: The Gods Command You Obey
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "2"
name: The Gods Command You Obey
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/the-gods-command-you-obey
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: "\n*You speak with the voice of your [saint](../../../../rule/world/saint.md), commanding your enemies.*\n\n| **Magic, [Ranged](../../../../rule/combat/ranged.md), [Strike](../../../../rule/combat/strike.md)** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF [Ranged](../../../../rule/combat/ranged.md) 10**          | **\U0001F3AF One creature** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Intuition](../../../../rule/character/intuition.md):**\n\n- **≤11:** 4 + I holy damage; P < WEAK, before taking damage, the target makes a [free strike](../../../common/main-actions/free-strike.md) against a target you choose\n- **12-16:** 7 + I holy damage; P < AVERAGE, before taking damage, the target uses an ability of your choice and you choose any targets for that ability\n- **17+:** 11 + I holy damage; P < STRONG, before taking damage, the target shifts up to their [speed](../../../../rule/character/speed.md) to a location you choose, uses an ability of your choice, and you choose any targets for that ability"
feature_type: ability
flavor: You speak with the voice of your [saint](../../../../rule/world/saint.md), commanding your enemies.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    flavor: You speak with the voice of your [saint](../../../../rule/world/saint.md), commanding your enemies.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "2"
    name: The Gods Command You Obey
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/the-gods-command-you-obey
    target: One creature
    type: ability
name: The Gods Command You Obey
target: One creature
type: feature
usage: Main action
```
