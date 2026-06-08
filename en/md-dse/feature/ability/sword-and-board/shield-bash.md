---
action_type: Main action
distance: Melee 1
feature_type: ability
file_basename: shield-bash
file_dpath: feature/ability/sword-and-board
flavor: In your hands, a shield isn't just for protection.
item_id: shield-bash
item_name: Shield Bash
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: sword-and-board
name: Shield Bash
scc: mcdm.heroes.v1/feature.ability.sword-and-board/shield-bash
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: "*In your hands, a shield isn't just for protection.*\n\n| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF Melee 1**            | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + M or A damage; push 1\n- **12-16:** 7 + M or A damage; push 2\n- **17+:** 9 + M or A damage; push 3; M < STRONG[, prone](scc:mcdm.heroes.v1/condition/prone)"
feature_type: ability
flavor: In your hands, a shield isn't just for protection.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    flavor: In your hands, a shield isn't just for protection.
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: sword-and-board
    name: Shield Bash
    scc: mcdm.heroes.v1/feature.ability.sword-and-board/shield-bash
    subtype: signature
    target: One creature
    type: ability
name: Shield Bash
target: One creature
type: feature
usage: Main action
```
