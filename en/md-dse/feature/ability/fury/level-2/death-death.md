---
action_type: Main action
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Melee 1
feature_type: ability
file_basename: death-death
file_dpath: feature/ability/fury/level-2
flavor: Your unbridled rage strikes terror in their hearts.
item_id: death-death
item_name: Death... Death!
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: Death... Death!
scc: mcdm.heroes.v1/feature.ability.fury.level-2/death-death
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Melee 1
effects:
    - effect: "\n*Your unbridled rage strikes terror in their hearts.*\n\n| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF Melee 1**            | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**\n\n- **≤11:** 3 + M damage; P < WEAK, [dazed](scc:mcdm.heroes.v1/condition/dazed) and [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)\n- **12-16:** 5 + M damage; P < AVERAGE, [dazed](scc:mcdm.heroes.v1/condition/dazed) and [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)\n- **17+:** 8 + M damage; P < STRONG, [dazed](scc:mcdm.heroes.v1/condition/dazed) and [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)"
feature_type: ability
flavor: Your unbridled rage strikes terror in their hearts.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 5 Ferocity
    distance: Melee 1
    flavor: Your unbridled rage strikes terror in their hearts.
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: Death... Death!
    scc: mcdm.heroes.v1/feature.ability.fury.level-2/death-death
    target: One creature
    type: ability
name: Death... Death!
target: One creature
type: feature
usage: Main action
```
