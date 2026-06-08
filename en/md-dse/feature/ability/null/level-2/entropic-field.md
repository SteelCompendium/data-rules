---
action_type: Main action
class: "null"
cost: 5 Discipline
cost_amount: "5"
cost_resource: Discipline
distance: 3 cube within 1
feature_type: ability
file_basename: entropic-field
file_dpath: feature/ability/null/level-2
flavor: You drastically increase the local entropy.
item_id: entropic-field
item_name: Entropic Field
keywords:
    - Area
    - Psionic
    - Weapon
level: "2"
name: Entropic Field
scc: mcdm.heroes.v1/feature.ability.null.level-2/entropic-field
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 5 Discipline
distance: 3 cube within 1
effects:
    - effect: "\n*You drastically increase the local entropy.*\n\n| **Area, Psionic, Weapon** |               **Main action** |\n|---------------------------|------------------------------:|\n| **\U0001F4CF 3 cube within 1**    | **\U0001F3AF Each enemy in the area** |\n\n**Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 6 cold damage; A < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **12-16:** 9 cold damage; A < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **17+:** 13 cold damage; A < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)"
feature_type: ability
flavor: You drastically increase the local entropy.
keywords:
    - Area
    - Psionic
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 5 Discipline
    distance: 3 cube within 1
    flavor: You drastically increase the local entropy.
    keywords:
        - Area
        - Psionic
        - Weapon
    level: "2"
    name: Entropic Field
    scc: mcdm.heroes.v1/feature.ability.null.level-2/entropic-field
    target: Each enemy in the area
    type: ability
name: Entropic Field
target: Each enemy in the area
type: feature
usage: Main action
```
