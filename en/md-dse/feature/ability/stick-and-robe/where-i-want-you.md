---
action_type: Main action
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
feature_type: ability
file_basename: where-i-want-you
file_dpath: feature/ability/stick-and-robe
flavor: When your stick speaks, your enemy moves.
item_id: where-i-want-you
item_name: Where I Want You
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: stick-and-robe
name: Where I Want You
scc: mcdm.heroes.v1/feature.ability.stick-and-robe/where-i-want-you
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - effect: "*When your stick speaks, your enemy moves.*\n\n| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2**            | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + M or A damage\n- **12-16:** 7 + M or A damage; slide 1\n- **17+:** 10 + M or A damage; slide 3"
feature_type: ability
flavor: When your stick speaks, your enemy moves.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
    flavor: When your stick speaks, your enemy moves.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: stick-and-robe
    name: Where I Want You
    scc: mcdm.heroes.v1/feature.ability.stick-and-robe/where-i-want-you
    subtype: signature
    target: One creature
    type: ability
name: Where I Want You
target: One creature
type: feature
usage: Main action
```
