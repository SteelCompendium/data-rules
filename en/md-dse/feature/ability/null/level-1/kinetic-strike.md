---
action_type: Main action
class: "null"
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: kinetic-strike
file_dpath: feature/ability/null/level-1
flavor: Your opponent staggers. They cannot ignore you.
item_id: kinetic-strike
item_name: Kinetic Strike
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Kinetic Strike
scc: mcdm.heroes.v1/feature.ability.null.level-1/kinetic-strike
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: "\n*Your opponent staggers. They cannot ignore you.*\n\n| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), Psionic, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |\n|------------------------------------|------------------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**                     | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))\n- **12-16:** 5 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)), slide 1\n- **17+:** 6 + A damage; [taunted](scc:mcdm.heroes.v1/condition/taunted) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn)), slide 2"
feature_type: ability
flavor: Your opponent staggers. They cannot ignore you.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: Your opponent staggers. They cannot ignore you.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Kinetic Strike
    scc: mcdm.heroes.v1/feature.ability.null.level-1/kinetic-strike
    subtype: signature
    target: One creature or object
    type: ability
name: Kinetic Strike
target: One creature or object
type: feature
usage: Main action
```
