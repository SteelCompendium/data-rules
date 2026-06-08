---
action_type: Main action
class: "null"
distance: Melee 2
feature_type: ability
file_basename: magnetic-strike
file_dpath: feature/ability/null/level-1
flavor: The force of your blow extends past the limits of your body, pulling your enemy closer.
item_id: magnetic-strike
item_name: Magnetic Strike
keywords:
    - Melee
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Magnetic Strike
scc: mcdm.heroes.v1/feature.ability.null.level-1/magnetic-strike
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Melee 2
effects:
    - effect: "\n*The force of your blow extends past the limits of your body, pulling your enemy closer.*\n\n| **Melee, Psionic, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|------------------------------------|--------------------:|\n| **\U0001F4CF Melee 2**                     | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 5 + A psychic damage; vertical pull 1\n- **12-16:** 8 + A psychic damage; vertical pull 2\n- **17+:** 11 + A psychic damage; vertical pull 3"
feature_type: ability
flavor: The force of your blow extends past the limits of your body, pulling your enemy closer.
keywords:
    - Melee
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: Melee 2
    flavor: The force of your blow extends past the limits of your body, pulling your enemy closer.
    keywords:
        - Melee
        - Psionic
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Magnetic Strike
    scc: mcdm.heroes.v1/feature.ability.null.level-1/magnetic-strike
    subtype: signature
    target: One creature
    type: ability
name: Magnetic Strike
target: One creature
type: feature
usage: Main action
```
