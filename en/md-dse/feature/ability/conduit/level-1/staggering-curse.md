---
action_type: Main action
class: conduit
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: staggering-curse
file_dpath: feature/ability/conduit/level-1
flavor: A blast of judgment disorients your foe.
item_id: staggering-curse
item_name: Staggering Curse
keywords:
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Staggering Curse
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/staggering-curse
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: "\n*A blast of judgment disorients your foe.*\n\n| **Magic, [Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike)**  |               **Main action** |\n|---------------------------|------------------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc:mcdm.heroes.v1/rule.character/intuition):**\n\n- **≤11:** 3 + I holy damage; slide 1\n- **12-16:** 5 + I holy damage; slide 2\n- **17+:** 8 + I holy damage; slide 3"
feature_type: ability
flavor: A blast of judgment disorients your foe.
keywords:
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: A blast of judgment disorients your foe.
    keywords:
        - Magic
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
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
