---
action_type: Main action
class: conduit
distance: Melee 1
feature_type: ability
file_basename: staggering-curse
file_dpath: feature/ability/conduit/level-1
flavor: A blast of judgment disorients your foe.
item_id: staggering-curse
item_name: Staggering Curse
keywords:
    - Magic
    - Melee
    - '[Strike](../../../../rule/combat/strike.md)'
level: "1"
name: Staggering Curse
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/staggering-curse
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: "\n*A blast of judgment disorients your foe.*\n\n| **Magic, Melee, [Strike](../../../../rule/combat/strike.md)**  |               **Main action** |\n|---------------------------|------------------------------:|\n| **\U0001F4CF Melee 1**            | **\U0001F3AF One creature or object** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Intuition](../../../../rule/character/intuition.md):**\n\n- **≤11:** 3 + I holy damage; slide 1\n- **12-16:** 5 + I holy damage; slide 2\n- **17+:** 8 + I holy damage; slide 3"
feature_type: ability
flavor: A blast of judgment disorients your foe.
keywords:
    - Magic
    - Melee
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: Main action
    class: conduit
    distance: Melee 1
    flavor: A blast of judgment disorients your foe.
    keywords:
        - Magic
        - Melee
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "1"
    name: Staggering Curse
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/staggering-curse
    subtype: signature
    target: One creature or object
    type: ability
name: Staggering Curse
target: One creature or object
type: feature
usage: Main action
```
