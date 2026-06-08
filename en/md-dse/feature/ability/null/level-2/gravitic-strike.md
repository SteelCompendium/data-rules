---
action_type: Main action
class: "null"
cost: 5 Discipline
cost_amount: "5"
cost_resource: Discipline
distance: Melee 3
feature_type: ability
file_basename: gravitic-strike
file_dpath: feature/ability/null/level-2
flavor: Your fist emanates gravitic force that pulls a distant enemy closer.
item_id: gravitic-strike
item_name: Gravitic Strike
keywords:
    - Melee
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: Gravitic Strike
scc: mcdm.heroes.v1/feature.ability.null.level-2/gravitic-strike
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Discipline
distance: Melee 3
effects:
    - effect: "\n*Your fist emanates gravitic force that pulls a distant enemy closer.*\n\n| **Melee, Psionic, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|------------------------------------|--------------------:|\n| **\U0001F4CF Melee 3**                     | **\U0001F3AF One creature** |\n\n**Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 8 + A psychic damage; vertical pull 3\n- **12-16:** 12 + A psychic damage; vertical pull 5\n- **17+:** 16 + A psychic damage; vertical pull 7"
feature_type: ability
flavor: Your fist emanates gravitic force that pulls a distant enemy closer.
keywords:
    - Melee
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 5 Discipline
    distance: Melee 3
    flavor: Your fist emanates gravitic force that pulls a distant enemy closer.
    keywords:
        - Melee
        - Psionic
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: Gravitic Strike
    scc: mcdm.heroes.v1/feature.ability.null.level-2/gravitic-strike
    target: One creature
    type: ability
name: Gravitic Strike
target: One creature
type: feature
usage: Main action
```
